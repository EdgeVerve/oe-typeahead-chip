# \<oe-typeahead-chip\>

An input control with dropdown for choosing possible valid values from a remote url and display in the form of chips. The data can be be dynamically fetched by specifying `searchurl` property.

```html
<oe-typeahead-chip 
      label="Country"
      searchurl="api/countries?filter[where][name][regexp]=SEARCH_STRING",
      dataurl='api/countries?filter={"where": {"code": {"inq": VALUE_STRING}}}',
      displayproperty="name",
      valueproperty="code"
      required
      >
</oe-typeahead-chip>
```

This fork of graphql-query-builder adds the EnumValue type, which won't be wrapped in an extra set of double-quotes by the filter builder. Index.js now exports both Query and EnumValue.

Filter with an enum like so: 

``` js
new Query("example").filter({
          orderBy: new EnumValue("name_ASC")
        }).find(
          "id"
          "name"
        )
```

# graphql-query-builder

Please refer to original repo for any more information. This fork was a quick fix and guarantees nothing about code quality or tests.

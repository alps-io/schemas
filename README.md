# schemas
Schema support for ALPS

* JSON Schema [https://alps-io.github.io/schemas/alps.json](https://alps-io.github.io/schemas/alps.json)
* XSD [https://alps-io.github.io/schemas/alps.xsd](https://alps-io.github.io/schemas/alps.xsd)

You can start creating ALPS profiles from these scratch files.

JSON
```json
{
  "$schema": "https://alps-io.github.io/schemas/alps.json",
  "alps": {
    "descriptor": [
      {"id": ""}
    ]
  }
}
```

XML
```xml
<?xml version="1.0" encoding="UTF-8"?>
<alps xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:noNamespaceSchemaLocation="https://alps-io.github.io/schemas/alps.xsd">
    <descriptor id=""/>
</alps>
```

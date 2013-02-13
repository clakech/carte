---
category: Attribute
path: '/foundation/v2/attributes/:attributeCode'
title: 'Get attribute'
type: 'GET'

layout: nil
---

This method allows users to retrieve attribute.

### Request

* The headers must include a **valid authentication token**.

### Response

Sends back an attributes.

```Status: 200 OK```
```{
       name: "Attribute",
       mandatory: true
   }
}```

For errors responses, see the [response status codes documentation](#response-status-codes).
# OpenAPI_November

## About

Trial and error with testing using OpenAPI to document API structures, routes and increase knowledge of YAML.

### OpenAPI Minimal Document Structure

```
openapi: 3.1.0

info:

  title: A minimal OpenAPI document

  version: 0.0.1

paths: {} # No endpoints defined
```

**openapi**

Indicates the version of the OAS that document is using 

**info** (info object)

Provides general information about the API (e.g. description, author or contact information) but the only mandatory fields are *title* and *version*.

- title (string)

A human-readable name for the API

- version (string)

Indicates the version of the API document 

**paths** (Paths object)

This describes all the endpoints of the API, including their parameters and all possible server responses. It can be an empty array for minimal OAS documentation
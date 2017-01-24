# SwaggerGenerator
Tools to help building Swagger documentations
## swaggerGen
Converts JSON mocks to Swagger definitions
* Supports all swagger types
* Detects int32 and int64 formats
  * Added unsafe format to integers that use more than 64 bits
* Detects date and date-time formats according to [ISO 8601](https://xml2rfc.tools.ietf.org/public/rfc/html/rfc3339.html#anchor14)
* Allows nested objects and arrays
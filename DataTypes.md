Currently Exposed support the following data types in table definition:  
* `integer` - translates to DB `INT`
* `long` - `BIGINT`
* `bool` - `BOOLEAN`
* `char` - `CHAR`
* `varchar` - `VARCHAR` with length
* `text` - `TEXT`
* `decimal` - `DECIMAL` with scale and precision
* `enumeration` - `INT` ordinal value
* `enumerationByName` - `VARCHAR`
* `date` - `DATETIME`
* `datetime` - `DATETIME`
* `blob` - `BLOB`
* `binary` - `VARBINARY` with length
* `uuid` - `BINARY(16)`
* `reference` - a foreign key


Note: some types are different for specific DB dialect.
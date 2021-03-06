
# Record Schema Schema

```
https://ns.adobe.com/xdm/data/record
```

Used to indicate the behaviour of record data semantic when composed into data Schemas.

| [Abstract](../../abstract.md) | [Extensible](../../extensions.md) | [Status](../../status.md) | [Identifiable](../../id.md) | [Custom Properties](../../extensions.md) | [Additional Properties](../../extensions.md) | Defined In |
|-------------------------------|-----------------------------------|---------------------------|-----------------------------|------------------------------------------|----------------------------------------------|------------|
| Can be instantiated | Yes | Experimental | No | Forbidden | Permitted | [data/record.schema.json](data/record.schema.json) |
## Schema Hierarchy

* Record Schema `https://ns.adobe.com/xdm/data/record`
  * [Extensibility base schema](../common/extensible.schema.md) `https://ns.adobe.com/xdm/common/extensible`


## Record Schema Example
```json
{
  "@id": "49069bba-3014-420b-a887-3959f87d474a"
}
```

# Record Schema Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [@id](#id) | `string` | Optional | Record Schema (this schema) |
| [xdm:timeSeriesEvents](#xdmtimeseriesevents) | Time-series Schema | Optional | Record Schema (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## @id
### Identifier

A unique identifier for the record.

`@id`
* is optional
* type: `string`
* defined in this schema

### @id Type


`string`
* format: `uri-reference` – URI Reference (according to [RFC3986](https://tools.ietf.org/html/rfc3986))






## xdm:timeSeriesEvents
### Time-series Events

List of time-series based events that relate to schemas based on record.

`xdm:timeSeriesEvents`
* is optional
* type: Time-series Schema

* defined in this schema

### xdm:timeSeriesEvents Type


Array type: Time-series Schema

All items must be of the type:
* [Time-series Schema](time-series.schema.md) – `https://ns.adobe.com/xdm/data/time-series`








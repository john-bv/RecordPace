# Record Pace Protocol
Record Pace is a recording library compatible with PocketMine.

## Binary Header
| Name           | Type          | Description                            |
| -------------- | ------------- | -------------------------------------- |
| Magic          | `string`      | `"recordpace072123"`                   |
| Version        | `string`      | The version for this file. EG: `0.1.0` |
| ID             | `string`      | The ID used to identify this data.     |
| ContextVersion | `u8` (`char`) | The context API version to use.        |


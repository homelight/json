# json
This is a fork of [golang's encoding/json](https://github.com/golang/go/tree/master/src/encoding/json) with an extra method `MarshalSafeCollections` that marshals nil slices and maps into `[]` and `{}` respectfully instead of `null`. Additionally added `SetNilSafeCollection` to the `Encoder` in order to turn on the flag (default: false).

Currently master is a fork of `go1.9.4`.

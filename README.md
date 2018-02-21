# json
This is a fork of [golang's encoding/json](https://github.com/golang/go/tree/master/src/encoding/json) with an extra method `MarshalSafeSlice` that marshals nil slices into `[]` instead of `null`. Additionally added `SetRescueNilSlice` to the `Encoder` in order to turn on the flag (default: false).

Currently master is a fork of `go1.9.4`.

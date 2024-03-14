# Change Log
All notable changes that differ from [google/gnostic](https://github.com/google/gnostic/tree/main/cmd/protoc-gen-openapi) to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)

## [0.7.0-digits] - 2024-03-14

### Fixed
- Add support for int64 in the generator schema by reverting [#355](https://github.com/google/gnostic/pull/355)
- Resolve import conflicts by prioritizing protobuf messages local to the service and using the fully qualified protobuf message name when there is a conflict with a local message. [#1](https://github.com/digits/protoc-gen-openapi/pull/1)

# shuftle-protocol

Protocol Buffers definitions of the gRPC API shared by the Shuftle server and clients.
It's meant to be consumed as a git submodule and each consumer generates its own bindings.

The protocol version in `version.txt` is maintained by release-please from conventional
commits. See `proto/shuftle/version/v1/version.proto` for how clients send it.

Licensed under the AGPL-3.0-only.

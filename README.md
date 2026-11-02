# gRPC Notes Service

A simple gRPC service for managing notes. It allows users to create, read, update, and delete notes using gRPC. Created as a learning project to understand gRPC and Protocol Buffers concepts and implementation.

## API

The `NotesService` gRPC API is defined in `api/proto/notes/v1/notes.proto`. It supports creating, retrieving, updating, deleting, and listing notes. `ListNotes` accepts `page` and `page_size` for pagination.

A `Note` contains an ID, title, content, and creation and update timestamps. Create, get, and update return a note; delete returns an empty response.

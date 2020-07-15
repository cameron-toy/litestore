## Litestore

Litestore is a wrapper for the [Lumino](https://github.com/jupyterlab/lumino) Datastore.

Litestore wraps a dummy adapter and a transaction store with the Datastore to allow for easy Datastore writes, reads, undos, and redos.

Litestore is suitable for single-user extensions and applications where undo/redo functionality, serialization, and/or a local database are required.

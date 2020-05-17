# grm

1. Bridge the go structure, redis key-value value, mysql table data mapping processing, and crud processing of data.

2.go structure and redis key-value value are synchronous processing, mysql permanent storage is asynchronous processing.

3. Each field processing can allow dirty data once, that is, after redis synchronously processes a field, you need to wait for the asynchronous mysql to land before processing the field again.

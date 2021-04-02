# Data

## Best Practices

- Avoid automatic retries for non-idempotent operations.
- Use at least once delivery with idempotent operations.
- Use at most once delivery with non-idempotent operations.
- Use stream processing for data which is not guaranteed to fit into memory.

### Streaming

- Avoid storing messages with different schemas in the same topic or queue.
- Keep messages as small as possible.
- When one message would perform more than one operation, instead have that
  message append a new message for each operation.

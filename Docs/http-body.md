# HTTPBody

The `HTTPBody` type represents an HTTP body in buffer or stream form.

```swift
public enum HTTPBody {
    case BufferBody(Data)
    case StreamBody(Stream)
}
```

### Motivation

Buffer bodies are best suited for HTTP messages with Content-Length headers. Stream bodies are best suited for HTTP messages with Transfer-Encoding set to chunked.
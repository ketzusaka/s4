# HTTPResponseConvertible

The `HTTPResponseConvertible` protocol represents a type that can be converted to and from an S4 HTTP response.

```swift
public protocol HTTPResponseConvertible: HTTPResponseInitializable, HTTPResponseRepresentable {}
```

## Motivation

If you don't want to use S4's native response you can convert it to and from your own response using this protocol.
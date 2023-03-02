# libxbrl

libxbrl is an *experimental* project that aims to provide a free and open-source library for processing
[XBRL](https://en.wikipedia.org/wiki/XBRL).

## Goals

The primary goals for libxbrl are as follows:

- Achieve 100% compliance with [XBRL specifications](https://specifications.xbrl.org/specifications.html) that are at
  recommendation status.
- Provide best-in-class performance while minimizing memory usage.
- Offer an easy-to-use library API for querying XBRL data.
- Ensure compatibility with any language or runtime that supports C interop/FFI, such as C#, C++, Go, Java, Node.js,
  Python, Rust, Swift, and more.
- Support cross-platform usage on Linux, macOS, and Windows operating systems.

## Non-Goals

libxbrl is focused on creating a powerful XBRL processing library within the scope of the XBRL specifications. As such,
it does not include functionality beyond those specifications, such as jurisdiction validations, taxonomy editors,
renderers, or similar features. Instead, applications built with libxbrl should provide these types of features.

## License

libxbrl is licensed under both the MIT License and the Apache License (Version 2.0).

Please refer to [LICENSE-MIT](LICENSE-MIT) and [LICENSE-APACHE](LICENSE-APACHE) for further details.

# Server Side Extension

This repository provides a server-side extension (SSE) protocol based on gRPC that allows you to extend the Qlik built-in expression library with functionality from external calculation engines. You can use external calculations engines from both load script expressions and chart expressions. These SSE plugins are referred to as analytic connections in Qlik Sense.  
SSE is part of the Advanced Analytics Integration (AAI) concept at Qlik.  
This repository includes documentation that describes the SSE protocol, how to use it and how to build your own plugins. Currently we have examples written in a few different languages only but examples in more languages will come later.  

## Status
[![CircleCI](https://circleci.com/gh/qlik-oss/server-side-extension.svg?style=shield)](https://circleci.com/gh/qlik-oss/server-side-extension) [![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcjcross%2Fserver-side-extension.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcjcross%2Fserver-side-extension?ref=badge_shield)
 

**Current Plugin Version and State:** v1.0.0  
**Matching Qlik Sense Version:** Qlik Sense 2017 release (or later). Both desktop and enterprise.  
**Examples:** The examples provided are not meant to be used in production, therefore **no support is provided**.  

[Previous Versions](docs/versions.md)

## Documentation

* [Overview](docs/README.md)
* [Communication flow](docs/communication_flow.md)
* [Generating certificates](generate_certs_guide/README.md)
* [Configuring SSE plugins in Qlik Sense](docs/configuration.md)
* [Writing an SSE plugin](docs/writing_a_plugin.md)
* [Protocol Documentation](docs/SSE_Protocol.md) (API reference)

## Examples

### Python
* [Getting started with the Python examples](examples/python/GetStarted.md)
* [Writing an SSE plugin using Python](examples/python/README.md)

### C++
* [Writing an SSE Plugin using C++](examples/cpp/README.md)
* [A basic example](examples/cpp/basic_example/README.md)

### C#
* [Writing an SSE Plugin using C#](examples/CSharp/README.md)
* The [SSE R-plugin](https://github.com/qlik-oss/sse-r-plugin) is written in C#

## Contributing
Please follow the instructions in [CONTRIBUTING.md](.github/CONTRIBUTING.md).


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcjcross%2Fserver-side-extension.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcjcross%2Fserver-side-extension?ref=badge_large)
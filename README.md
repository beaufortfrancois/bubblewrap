<!---

  Copyright 2019 Google Inc. All Rights Reserved.
 
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at
 
       http://www.apache.org/licenses/LICENSE-2.0
 
   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->
# Bubblewrap
[![Node CI Status](https://github.com/GoogleChromeLabs/bubblewrap/workflows/Node%20CI/badge.svg)](https://github.com/GoogleChromeLabs/bubblewrap/actions?query=workflow%3A%22Node+CI%22)

Bubblewrap is a set of tools and libraries designed to help developers to create, build and update
projects for Android Applications that launch Progressive Web App (PWA) using
[Trusted Web Activity (TWA)](https://developers.google.com/web/android/trusted-web-activity/).

## Requirements
- [Node.js](https://nodejs.org/en/) 10.0 or above

## Getting Started
- To get started with building an application using Bubblewrap, check the [Trusted Web Activity
Quick Start Guide][1] or the [bubblewrap/cli](./packages/cli) documentation.

## Bubblewrap Components

- **[bubblewrap/core](./packages/core):** a javascript library for generating, building and
updating TWA projects.
- **[bubblewrap/cli](./packages/cli):** a command-line version of Bubblewrap.
- **[bubblewrap/validator](./packages/validator):** library to validate the correctness and
compare Trusted Web Activity projects against the quality criteria.

## Contributing

See [CONTRIBUTING](./CONTRIBUTING.md) for more.

## License

See [LICENSE](./LICENSE) for more.

## Disclaimer

This is not a Google product.

[1]: https://developers.google.com/web/android/trusted-web-activity/quick-start

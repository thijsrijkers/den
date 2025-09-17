# Den

Den is an npm-inspired package manager for Go. It allows developers to manage Go module dependencies using a configuration file similar to package.json. The initial focus is on installing modules listed in a config file, with plans to add functionality for exporting and publishing custom Go modules in the future.

## Features

- Install Go modules from a configuration file
- Manage dependencies in a declarative, npm-like workflow
- Designed to be extended for publishing and sharing your own modules
- Simple CLI for easy integration into Go projects

## Installation

Instructions for installing Den will be provided once the first release is ready. The CLI will allow easy execution of common tasks like installing dependencies and managing modules.

## Usage

To use Den, create a configuration file (`package_den.json`) listing your project dependencies. Den will read this file and install the required Go modules automatically.

Future updates will include the ability to package and publish your own modules to the Go ecosystem.

## Roadmap

- Support for exporting and uploading self-made modules
- Version management and semantic versioning support
- Module registry and search functionality
- Improved CLI commands for managing projects

## License

Den is released under the MIT License.

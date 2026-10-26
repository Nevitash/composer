# Composer _(composer)_

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Cross-platform .NET MAUI Blazor Hybrid client application for Composer.

Composer delivers the native desktop and mobile shell for the Composer ecosystem, integrating Blazor web components with native device capabilities across Windows, Android, and iOS.

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

Composer leverages .NET MAUI with Blazor Hybrid webview integration to share presentation logic and Razor UI components seamlessly with the web edition while maintaining access to native platform services.

## Install

Requires .NET 8 or .NET 9 SDK with the MAUI workload installed:

```bash
dotnet workload install maui
```

Restore dependencies:

```bash
dotnet restore composer.csproj
```

## Usage

Run on Windows desktop:

```bash
dotnet build composer.csproj -t:Run -f net8.0-windows10.0.19041.0
```

Run on Android emulator or connected device:

```bash
dotnet build composer.csproj -t:Run -f net8.0-android
```

## Maintainers

[@Nevitash](https://github.com/Nevitash)

## Contributing

PRs accepted. Please open an issue first to discuss substantial feature proposals or design overhauls.

## License

[MIT](LICENSE)

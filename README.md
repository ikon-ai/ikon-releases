# IKON releases

The links below always download the newest version of each IKON product.

## IKON Desktop

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/ikon-desktop) · [studio.ikonai.app/download](https://studio.ikonai.app/download)

- [Windows](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-desktop/IKON-Desktop-windows-x64-setup.exe)
- [macOS](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-desktop/IKON-Desktop-macos-universal.dmg)
- Linux: [AppImage](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-desktop/IKON-Desktop-linux-x86_64.AppImage), [deb](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-desktop/IKON-Desktop-linux-amd64.deb), [rpm](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-desktop/IKON-Desktop-linux-x86_64.rpm)

## IKON Station

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/ikon-station)

- [Windows](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-station/IKON-Station-windows-x64-setup.exe)
- [macOS](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-station/IKON-Station-macos-universal.dmg)
- [Linux AppImage](https://github.com/ikon-ai/ikon-releases/releases/download/ikon-station/IKON-Station-linux-x86_64.AppImage)

## IKON tool

```powershell
irm https://ikonai.com/install.ps1 | iex       # Windows
```

```bash
curl -fsSL https://ikonai.com/install.sh | bash   # macOS and Linux
```

Or from nuget.org: `dotnet tool install ikon --global`.

## IKON C# SDK

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/dotnet-sdk) · [nuget.org](https://www.nuget.org/packages/Ikon.Sdk)

```bash
dotnet add package Ikon.Sdk
```

- [.NET 10](https://github.com/ikon-ai/ikon-releases/releases/download/dotnet-sdk/IKON-DotNet-SDK-net10.0.zip)
- [.NET Standard 2.1](https://github.com/ikon-ai/ikon-releases/releases/download/dotnet-sdk/IKON-DotNet-SDK-netstandard2.1.zip)

## IKON TypeScript SDK

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/typescript-sdk) · [npm](https://www.npmjs.com/package/@ikonai/sdk)

```bash
npm install @ikonai/sdk @ikonai/sdk-libopus
```

- [`@ikonai/sdk`](https://github.com/ikon-ai/ikon-releases/releases/download/typescript-sdk/IKON-TypeScript-SDK.tgz)
- [`@ikonai/sdk-ui`](https://github.com/ikon-ai/ikon-releases/releases/download/typescript-sdk/IKON-TypeScript-SDK-ui.tgz)
- [`@ikonai/sdk-react-ui`](https://github.com/ikon-ai/ikon-releases/releases/download/typescript-sdk/IKON-TypeScript-SDK-react-ui.tgz)
- [`@ikonai/sdk-react-ui-standard`](https://github.com/ikon-ai/ikon-releases/releases/download/typescript-sdk/IKON-TypeScript-SDK-react-ui-standard.tgz)
- [`@ikonai/sdk-libopus`](https://github.com/ikon-ai/ikon-releases/releases/download/typescript-sdk/IKON-TypeScript-SDK-libopus.tgz)

## IKON C++ SDK

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/cpp-sdk) · [Download](https://github.com/ikon-ai/ikon-releases/releases/download/cpp-sdk/IKON-Cpp-SDK.zip)

```cmake
include(FetchContent)
FetchContent_Declare(ikon_sdk URL https://github.com/ikon-ai/ikon-releases/releases/download/cpp-sdk/IKON-Cpp-SDK.zip)
FetchContent_MakeAvailable(ikon_sdk)
```

## IKON Dart SDK

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/dart-sdk) · [pub.dev](https://pub.dev/packages/ikon_sdk) · [Download](https://github.com/ikon-ai/ikon-releases/releases/download/dart-sdk/IKON-Dart-SDK.tar.gz)

```bash
flutter pub add ikon_sdk
```

## IKON Rust SDK

[Release](https://github.com/ikon-ai/ikon-releases/releases/tag/rust-sdk) · [crates.io](https://crates.io/crates/ikon-sdk)

```bash
cargo add ikon-sdk
```

- [`ikon-sdk`](https://github.com/ikon-ai/ikon-releases/releases/download/rust-sdk/IKON-Rust-SDK.crate)
- [`ikon-protocol`](https://github.com/ikon-ai/ikon-releases/releases/download/rust-sdk/IKON-Rust-SDK-protocol.crate)
- [`ikon-teleport`](https://github.com/ikon-ai/ikon-releases/releases/download/rust-sdk/IKON-Rust-SDK-teleport.crate)

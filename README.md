Trust Wallet Core is a cross-platform library that implements low-level cryptographic wallet functionality for all supported blockchains. Most of the code is C++ with a set of strict exported C interfaces. The library provides idiomatic interfaces for all supported languages (currently Swift for iOS and Java for Android).

![iOS CI](https://github.com/rohitsethii/wallet-core/workflows/iOS%20CI/badge.svg)
![Android CI](https://github.com/rohitsethii/wallet-core/workflows/Android%20CI/badge.svg)
![Linux CI](https://github.com/rohitsethii/wallet-core/workflows/Linux%20CI/badge.svg)
![Docker CI](https://github.com/rohitsethii/wallet-core/workflows/Docker%20CI/badge.svg)
![Typescript CI](https://github.com/rohitsethii/wallet-core/workflows/Typescript%20CI/badge.svg)


## Documentation

For more complete documentation, see [developer.trustwallet.com](https://developer.trustwallet.com/wallet-core).

## Supported Blockchains

We support Bitcoin, Ethereum, Binance Chain and 50+ blockchains, you can see the full list [here](docs/coins.md).

## Building

For build instructions, see [developer.trustwallet.com/wallet-core/building](https://developer.trustwallet.com/wallet-core/building).

## WalletConsole Utility

Our project comes with an interactive command-line utility called _WalletConsole_, for accessing key and address management functionality of the library.  It can be started using:

```
$ ./build/walletconsole/walletconsole 
Type 'help' for list of commands.
> help
```

Further details: [developer.trustwallet.com/wallet-core/walletconsole](https://developer.trustwallet.com/wallet-core/walletconsole).

# Using from your project

If you want to use wallet core in your project follow these instructions.

## Android

Add this dependency to build.gradle:

```groovy
dependencies {
    implementation 'com.trustwallet:wallet-core:x.x.x'
}
```
[Replace with version](https://github.com/rohitsethii/wallet-core/releases)

## iOS

We currently support only CocoaPods. Add this line to your Podfile and run `pod install`:

```ruby
pod 'AITrustWalletCore'
```
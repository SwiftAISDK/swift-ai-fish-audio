<!-- Generated distribution; edit the canonical repository. -->
# swift-ai-fish-audio 1.1.3

Independent Swift-native port of Vercel AI SDK. Source and upstream dispositions are in PROVENANCE.json and Porting/.

## Distribution manifest

Add this package to your SwiftPM dependencies:

```swift
.package(url: "https://github.com/SwiftAISDK/swift-ai-fish-audio.git", from: "1.1.3")
```

Products: `SwiftAIFishAudio`.
Contribute and report issues in the canonical SwiftAISDK repository.

## Authored usage guide

# Fish Audio for Swift

`SwiftAIFishAudio` adds Fish Audio to [SwiftAISDK](https://github.com/SwiftAISDK/SwiftAISDK), an independent Swift port of the Vercel AI SDK. It ports `@ai-sdk/fish-audio` and supports transcription and speech.

Provider guide with models, options, streaming and errors:

- [Fish Audio](https://swiftaisdk.github.io/SwiftAISDK/providers/fish-audio/)

## Usage

Add the `SwiftAI` product from `swift-ai-core` and the `SwiftAIFishAudio` product from this package to your target, then create the provider:

```swift
import SwiftAI
import SwiftAIFishAudio

let provider = try AIProviders.fishAudio(configuration: FishAudioProviderSettings())
```

By default the provider reads `FISH_AUDIO_API_KEY` from the environment; values set in `FishAudioProviderSettings` take precedence.

To use every provider through one dependency, add the complete [SwiftAISDK](https://github.com/SwiftAISDK/SwiftAISDK) package instead; see [Install](https://swiftaisdk.github.io/SwiftAISDK/getting-started/install/).

## Contributing

This package is exported from `Packages/swift-ai-fish-audio` in the canonical [SwiftAISDK](https://github.com/SwiftAISDK/SwiftAISDK) repository. Open issues and pull requests there.

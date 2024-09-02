> [!IMPORTANT]
> The [MASShortcut library](https://github.com/shpakovski/MASShortcut) now supports Swift Package Manager, so you might be better off using that instead of this repo.

# Intro

This is a fork of the famous [MASShortcut library](https://github.com/shpakovski/MASShortcut). I have converted it to a Swift Package so that it can be easily installed via Swift Package Manager (SPM). Most of the credit for this goes to [SDGGiesbrecht](https://forums.swift.org/u/SDGGiesbrecht).

With this library you can easily implement Global Keyboard Shortcuts in your macOS app.

# Demo

![](https://i.imgur.com/ItmaRh0.gif)

# Documentation

Detailed documentation can be found [here](https://blog.rampatra.com/how-to-add-global-key-shortcuts-to-your-swift-app-using-masshortcut).

# Limitation

Doesn't support localization. It can only support one language for now. This will change once SPM allows to package resource files from Objective-C projects.

# Live Example

This library is being used in my app [Presentify](https://presentify.compzets.com/). You can get it from the [Mac App Store](https://apps.apple.com/app/id1507246666) or [Setapp](https://go.setapp.com/stp285?utm_medium=vendor_program&utm_source=Ram+Patra&utm_content=link) and go to `Preferences > Keyboard` to see how this looks/works.

# Copyright

MASShortcut is licensed under the 2-clause BSD license.

# Empty Keys UI Framework

Empty Keys UI is multi-platform user interface framework.

[API Docs](https://emptykeys.github.io/UI_Framework/index.html)

[NuGet](https://www.nuget.org/profiles/EmptyKeys)

# Features
## Multi-platform and Multi-Engine
Empty Keys UI is a library for .NET, Mono or .NET Core. It's engine agnostic. Two frameworks/engines are supported out of the box - MonoGame and Xenko. Engine specific libraries are open source - https://github.com/EmptyKeys/UI_Engines

## Code Generator from XAML
Final code is generated from standard XAML (.NET WPF) so you can use Visual Studio, Blend (or any other XAML editor) to create your UI. On top of that code generator detects used fonts and generates XNA Sprite Font definitions.

## Style and Themes
Empty Keys UI comes with built-in themes for quick start (Dark, Light and default dark Empty Keys). You can create more themes and styles by using Controls and Data Templates.

## MVVM support
The Model-View-ViewModel pattern is fully supported and Empty Keys UI comes with base classes and Service Manager for easy use.

## DPI aware
Empty Keys UI is DPI aware. If you change DPI, UI is automatically scaled. This is useful for mobile development (mobile phone, tablet).

## Animations
Empty Keys UI supports XAML animations and image animations. XAML animations are limited to DoubleAnimation, ThicknessAnimation and non-standard custom SolidColorBrushAnimation. System does support easing functions. Image animations are supported with AnimatedImage control and for ImageBrush.

## Free
Library is free for use with MIT License. UI Generator is open source on GitHub. 

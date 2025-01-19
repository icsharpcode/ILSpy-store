# New Language Features
* Add support for C# 12 primary constructors.
* Add support for C# 12 'ref readonly' parameters
* Added support for switch on (ReadOnly)Span<char> using a compiler-generated hash function.
* Added new a.GetValueOrDefault(b) -> a ?? b transform for side-effect-free default values.
* Support types that provide DisposeAsync without implementing IAsyncDisposable.
* Updated pattern detection to Roslyn 4.12

For more details see https://github.com/icsharpcode/ILSpy/releases/tag/v9.0
* Classes:
  * Ascii
  * ASCIIEncoding - Represents an ASCII character encoding of Unicode characters.
  * CodePagesEncodingProvider - Provides access to an encoding provider for code pages that otherwise are available only in the desktop .NET Framework.
  * CompositeFormat - Represents a parsed composite format string.
  * Decoder - Converts a sequence of encoded bytes into a set of characters.
  * DecoderExceptionFallback - Provides a failure-handling mechanism, called a fallback, for an encoded input byte sequence that cannot be converted to an input character. The fallback throws an exception instead of decoding the input byte sequence. This class cannot be inherited.
  * DecoderExceptionFallbackBuffer - Throws DecoderFallbackException when an encoded input byte sequence cannot be converted to a decoded output character. This class cannot be inherited.
  * DecoderFallback - Provides a failure-handling mechanism, called a fallback, for an encoded input byte sequence that cannot be converted to an output character.
  * DecoderFallbackBuffer - Provides a buffer that allows a fallback handler to return an alternate string to a decoder when it cannot decode an input byte sequence.
  * DecoderReplacementFallback - Provides a failure-handling mechanism, called a fallback, for an encoded input byte sequence that cannot be converted to an output character. The fallback emits a user-specified replacement string instead of a decoded input byte sequence. This class cannot be inherited.
  * DecoderReplacementFallbackBuffer - Represents a substitute output string that is emitted when the original input byte sequence cannot be decoded. This class cannot be inherited.
  * Encoder - Converts a set of characters into a sequence of bytes.
  * EncoderExceptionFallback - Provides a failure-handling mechanism, called a fallback, for an input character that cannot be converted to an output byte sequence. The fallback throws an exception if an input character cannot be converted to an output byte sequence. This class cannot be inherited.
  * EncoderExceptionFallbackBuffer - Throws EncoderFallbackException when an input character cannot be converted to an encoded output byte sequence. This class cannot be inherited.
  * EncoderFallback - Provides a failure-handling mechanism, called a fallback, for an input character that cannot be converted to an encoded output byte sequence.
  * EncoderFallbackBuffer - Provides a buffer that allows a fallback handler to return an alternate string to an encoder when it cannot encode an input character.
  * EncoderReplacementFallback - Provides a failure handling mechanism, called a fallback, for an input character that cannot be converted to an output byte sequence. The fallback uses a user-specified replacement string instead of the original input character. This class cannot be inherited.
  * EncoderReplacementFallbackBuffer - Represents a substitute input string that is used when the original input character cannot be encoded. This class cannot be inherited.
  * Encoding - Represents a character encoding.
  * EncodingExtensions - Provides extension methods for the encoding types, such as Encoding, Encoder, and Decoder.
  * EncodingInfo - Provides basic information about an encoding.
  * EncodingProvider - Provides the base class for an encoding provider, which supplies encodings that are unavailable on a particular platform.
  * RedactionStringBuilderExtensions - Redaction utility methods.
  * StringBuilder - Represents a mutable string of characters. This class cannot be inherited.
  * UnicodeEncoding - Represents a UTF-16 encoding of Unicode characters.
  * UTF32Encoding - Represents a UTF-32 encoding of Unicode characters.
  * UTF7Encoding - Represents a UTF-7 encoding of Unicode characters.
  * UTF8Encoding - Represents a UTF-8 encoding of Unicode characters.
* Exception Classes:
  * DecoderFallbackException - The exception that is thrown when a decoder fallback operation fails. This class cannot be inherited.
  * EncoderFallbackException - The exception that is thrown when an encoder fallback operation fails. This class cannot be inherited.
* Structs:
  * Rune - Represents a Unicode scalar value ([ U+0000..U+D7FF ], inclusive; or [ U+E000..U+10FFFF ], inclusive).
  * SpanLineEnumerator - Enumerates the lines of a ReadOnlySpan<T>.
  * SpanRuneEnumerator - Provides an enumerator for the Rune values represented by a span containing UTF-16 text.
  * StringBuilder.AppendInterpolatedStringHandler - Provides a handler used by the language compiler to append interpolated strings into StringBuilder instances.
  * StringBuilder.ChunkEnumerator - Supports simple iteration over the chunks of a StringBuilder instance.
  * StringRuneEnumerator - Provides an enumerator for the Rune values represented by a string.
* Enums:
  * NormalizationForm - Defines the type of normalization to perform.

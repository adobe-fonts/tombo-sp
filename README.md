# Tombo SP

Tombo SP is a special-purpose OpenType/CFF font that is intended to be used to display registration marks for glyphs, which is useful for illustrating glyph widths or the position of glyphs within the em-box. The positioning of the glyphs assumes that the em-box is set 12% below the Latin baseline and is one-em tall, meaning that it is tailored for CJK use.

The glyphs are mapped from U+230C through U+230F, and the 'ccmp' GSUB feature is used to access pre-composed forms of the left- and right-side pairs, meaning that <230D 230F> or <230F 230D> can be used to form the left-side registration marks, and that <230C 230E> or <230E 230C> can be used to form the right-side ones. For user convenience, the pre-composed left- and right-side pairs are also mapped from U+005B and U+005D, respectively.

## Font installation instructions

* [macOS](https://support.apple.com/en-us/HT201749)
* [Windows](https://www.microsoft.com/en-us/Typography/TrueTypeInstall.aspx)
* [Linux/Unix-based systems](https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116)

## Building the font from source

### Requirements

To build the binary font file from source, you need to have installed the [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html) (AFDKO). The AFDKO tools are widely used for font development today, and are part of most font editor applications.

### Building the font

In this repository, all necessary files are in place for building the OpenType/CFF font, and the COMMANDS.txt file provides the command lines that are used.

## Getting Involved

For any suggestions for changes, please [create a new issue](https://github.com/adobe-fonts/tombo-sp/issues) for consideration.

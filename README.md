# Barcode Generator
> Аpplication for generating barcodes in various formats with the possibility of customization and export system
### [Go to App](https://barcodegen.web.app/) ###
![Barcode](https://raw.githubusercontent.com/post-apocalypse/barcode-gen-app/master/src/assets/img/qr.webp?raw=true, 'Barcode')

## Available formats
- EAN 13: The European Article Number is a standard to encode product numbers. The EAN is a special case of a Global Trade Item Number.
- EAN 8: The same as the format above, but was introduced for use on small packages where the EAN-13 barcode would be too large.
- CODE 128 is a high-density linear barcode symbology defined in ISO/IEC. It's used for alphanumeric or numeric-only barcodes.
- ITF-14 is the GS1 implementation of an Interleaved 2 of 5 (ITF) bar code to encode a Global Trade Item Number. ITF-14 symbols are generally used on packaging levels of a product, such as a case box of 24 cans of soup. The ITF-14 will always encode 14 digits.
- MSI — The code can display only the number 0-9 and has no fixed length. Today this type of code is outdated and is no longer used. Because of this most barcode scanners can not recognize this type of code.
- Pharmacode: Pharmaceutical Binary Code is a barcode standard, used in the pharmaceutical industry as a packing control system. It is designed to be readable despite printing errors.

## Examples of barcodes
![Примеры](https://user-images.githubusercontent.com/106645309/185174398-6ed9b96f-746d-4ac9-97db-e88234663c33.png)

## Export options
1. PNG is a raster-graphics file format that supports lossless data compression.
2. JPG is a commonly used method of lossy compression for digital images, particularly for those images produced by digital photography. The degree of compression can be adjusted, allowing a selectable tradeoff between storage size and image quality.
3. SVG is an XML-based vector image format for defining two-dimensional graphics, having support for interactivity and animation.

## Demo
[Barcode Generator](https://user-images.githubusercontent.com/106645309/185779984-e95abb00-842d-4cdf-a416-b68a4ef6b99c.webm)

## Libraries and plugins used in this project
This application is written in [Vue](https://www.npmjs.com/package/vue) together with [Vuex](https://www.npmjs.com/package/vuex) and [Vue Router](https://www.npmjs.com/package/vue-router) from the framework ecosystem.
- [file-saver](https://www.npmjs.com/package/file-saver) for saving generated barcodes.
- [jsbarcode](https://www.npmjs.com/package/jsbarcode) for generating barcodes.
- [jszip](https://www.npmjs.com/package/jszip) for creating archives.
- [maska](https://www.npmjs.com/package/maska) for validating input fields.
___
### Have a question? Text me: [Telegram](https://t.me/apocalypsecore)

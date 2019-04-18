### iText 5.5.14 Fork

Changes made vs iText 5.5.14 Fork:

- Support for color converter interface allowing dual color representation iText BaseColor and AWT Color
- build.sh for local maven build

### **PLEASE NOTE: iText5 is EOL, and has been replaced by [iText7][itext7]**
 
We HIGHLY recommend customers use iText7 for new projects, and to consider moving existing projects from iText5 to iText7 to benefit from the many improvements such as:
 
- HTML to PDF (PDF/UA) conversion
- PDF Redaction
- SVG support
- Better language support: Indic, Thai, Khmer, Arabic, Hebrew. (Close-source addon)
- PDF Debugging for your IDE
- Data Extraction
- Better continued support and bugfixes
- More modular, extensible handling of your document workflow
- Extra practical add-ons
- Encryption, hashing & digital signatures


### [iText][itext] consists of several jars.

The main iText release contains:
- ```itextpdf-x.y.z.jar```: the core library
- ```itext-xtra-x.y.z.jar```: extra functionality (PDF 2!)
- ```itext-pdfa-x.y.z.jar```: PDF/A-related functionality
- ```xmlworker-x.y.z.jar```: XML (and HTML) functionality

iText is hosted on https://github.com/itext/itextpdf

You can find the latest releases here:
- http://github.com/itext/itextpdf/releases/latest

You can also [build iText from source][building].

We also have a tool that can help you debug PDFs:
- ```itext-rups-x.y.z.jar```
RUPS is hosted on http://github.com/itext/rups

If you have an idea on how to improve iText and you want to submit code,
please read our [Contribution Guidelines][contributing].

iText is licensed as [AGPL][agpl] software.

AGPL is a free / open source software license.

This doesn't mean the software is [gratis][gratis]!

Buying a license is mandatory as soon as you develop commercial activities
distributing the iText software inside your product or deploying it on a network
without disclosing the source code of your own applications under the AGPL license.
These activities include:
- offering paid services to customers as an ASP
- serving PDFs on the fly in the cloud or in a web application
- shipping iText with a closed source product

Contact sales for more info: http://itextpdf.com/sales

[agpl]: LICENSE.md
[building]: BUILDING.md
[contributing]: CONTRIBUTING.md
[extrajars]: EXTRAJARS.md
[gratis]: https://en.wikipedia.org/wiki/Gratis_versus_libre
[itext]: http://itextpdf.com/
[itext7]: https://github.com/itext/itext7

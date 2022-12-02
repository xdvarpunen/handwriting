# Stylus Supported File Formats

Stylus supported applications have feature to save drawn result into specific file format. File format can be reused in other applications and transformed into other file formats.

## InkML ("application/inkml+xml", .ink, .inkml)

> InkML is an XML data format for representing digital ink data that is input with an electronic pen or stylus as part of a multimodal system. In the context of the W3C Multimodal Interaction Framework, the markup provides a format for:
>    transferring digital ink data between devices and software components
>    storing hand-input traces for:
>        Handwriting recognition (including text, mathematics, chemistry)
>        Signature verification
>        Gesture interpretation

- https://www.w3.org/2002/mmi/ink
- https://en.wikipedia.org/wiki/InkML
- https://www.w3.org/2002/mmi/ink
- https://www.w3.org/TR/InkML/
- https://www.w3.org/TR/2011/REC-InkML-20110920/

### InkML Toolkit - open source contribution from HP Labs, India

> InkML is an XML data format and a draft W3C standard for platform and device-neutral representation of digital ink data that is input with an electronic pen or stylus. InkML Toolkit (InkMLTk) is targeted at providing a suite of tools for working with InkML documents. The toolkit includes InkML processor libraries implementing the W3C InkML specification and different kind of tools such as Converters (to and from other ink and image formats), InkML viewers including browser plug-ins, and InkML applications such as a graphical editor.
> 
> InkML Toolkit is brought to you by HP Labs India.

- https://inkmltk.sourceforge.net/
- https://web.archive.org/web/20020307044715/
- http://www.hpl.hp.com/india/

## ISF 

> Ink Serialized Format (ISF) is a Microsoft format to store written ink information. The format is mainly used for mobile devices like Personal digital assistants, tablet PCs and Ultra-Mobile PCs to store data entered with a stylus. 

- https://en.wikipedia.org/wiki/Ink_Serialized_Format
- https://learn.microsoft.com/en-us/windows/win32/tablet/ink-serialization-sample
- https://learn.microsoft.com/en-us/uwp/specifications/ink-serialized-format
- https://download.microsoft.com/download/0/B/E/0BE8BDD7-E5E8-422A-ABFD-4342ED7AD886/InkSerializedFormat(ISF)Specification.pdf

## WILL (.will)

- https://cdn.wacom.com/u/marketplace/INK-SDK/will/170801_WILL_Data_Format_Spec.pdf
- https://developer-docs.wacom.com/sdk-for-ink/docs/encoding/
- http://developer-docs.wacom.com/sdk-for-ink/docs/overview/
- http://developer-docs.wacom.com/sdk-for-ink/docs/model/
- https://developer-docs.wacom.com/sdk-for-ink/docs/model/assets/will3/diagram/uim-uml-all-v9.png

## Conversion

- http://forum.wacom.eu/viewtopic.php?f=9&t=4584

### WILL to SVG

- https://github.com/Wyess/will2svg
- https://github.com/ngmsoftware/will2svg

### ISF to InkML

- https://stackoverflow.com/questions/7104169/handling-ink-in-microsoft-ink-sdk
- https://sourceforge.net/projects/inkmltk/

### The Bamboo Spark 

> The Bamboo Spark app creates WILL (Wacom Ink Language Layer) files which can be exported as JPG, PDF or WILL files.

- https://support.wacom.com/hc/en-us/articles/1500006342662-Which-file-formats-does-the-app-support-

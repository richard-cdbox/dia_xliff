# dia_xliff
Export all the text from the .dia file to the XLIFF format (.xlf file), then import it back into the original .dia file.  

**Author:** Richard Sitányi (richard@cdbox.sk)

**File:** dia_xliff.py

**Version:** 1.0

**Date:** 10/22/2025

## Description:
The script extracts all text content from a .dia file (created with the Dia diagram editor) and exports it to an .xlf file (XML Localization Interchange File Format), which can be used in any CAT (Computer-Aided Translation) tool for localization and translation.

After the .xlf file is translated, the script reimports the translated text back into the original .dia file.

## Usage:
**Export:** python dia_xliff.py export <input.dia> <output.xlf> <srcLang> <targetLang>

**Import:** python dia_xliff.py import <input.xlf> <original.dia> <output.dia>

## Note:
The script only works on saved .dia file without compression.

## Compatibility
**Python:** 3.8+

**Formats:**

**.dia** file (The Dia diagram editor’s XML format)

**.xlf** file (XLIFF 2.2)

basic validation of word xml/ooxml documents, based on microsoft documentation, that does not require c# or dotnet framework.

requires xmllint, part of libxml2.

Usage:

./validate path/to/document.docx

sources:

- microsoft:
  https://docs.microsoft.com/en-us/openspecs/office_standards/ms-docx/d0a2e301-0ff7-4e9e-9bb7-ff47070dce0a

- OfficeOpenXML:
  https://www.iso.org/standard/71692.html
  https://standards.iso.org/ittf/PubliclyAvailableStandards/c071692_ISO_IEC_29500-4_2016_Electronic_inserts.zip

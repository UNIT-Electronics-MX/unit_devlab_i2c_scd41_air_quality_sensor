# Product Reference build

The UE0179 SCD41 Air Quality Sensor reference source is maintained in Markdown under
`chapters/`. Document metadata and chapter order are defined in `book.yml`.

## Pinout assets

The released V1.0 pinout is available in English and Spanish. PDF files are
stored in `hardware/`; PNG and JPG images are in `hardware/resources/`.
Chapter 4 uses the English PNG, and Chapter 8 links both language versions.

Other chapters and generated filenames still contain material inherited from
the TEMT6000 template. Review and replace that material before treating the
full Product Reference as product-specific documentation.

## Local validation build

Requirements: Pandoc and WeasyPrint, Google Chrome, or Chromium.

Run from the repository root and direct validation output outside the
repository:

```bash
./tools/product-reference/build.sh /tmp/ue0179-product-reference
```

The build produces Markdown, DOCX, HTML, and PDF files. Generated `docs/`
files are maintained by the publication workflow.

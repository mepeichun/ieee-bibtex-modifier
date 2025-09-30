# IEEE BibTeX Modifier

A web-based tool for automatically modifying BibTeX entries to conform to IEEE-style formatting requirements, specifically focusing on author list shortening and journal name abbreviation.

## Live Demo

Please visit this link for quick use:
https://mepeichun.github.io/ieee-bibtex-modifier/

## Features

- **Author List Shortening**: Automatically truncates long author lists (configurable threshold) to "first author and others" format
- **Journal Name Abbreviation**: Converts full journal names to standard IEEE abbreviations using a customizable mapping table
- **Real-time Preview**: See modifications highlighted in real-time with clear visual diff
- **Export Options**: Copy modified BibTeX to clipboard or download as `.bib` file
- **Customizable Configuration**: 
  - Adjustable author count threshold
  - Editable journal name mapping table
  - Import/export configuration as JSON

## Usage

1. **Input**: Paste your original BibTeX entries in the left text area
2. **Configure**:
   - Set the author threshold (minimum number of authors to trigger shortening)
   - Edit the journal abbreviation mapping table as needed
3. **Process**: Click the "Refine" button to apply modifications
4. **Output**: Review the modified BibTeX in the right panel with highlighted changes
5. **Export**: Use "Copy" or "Download" buttons to save your refined BibTeX

## Configuration

### Author Shortening
- **Threshold**: Minimum number of authors required before shortening (default: 6)

### Journal Abbreviations
The tool includes pre-configured mappings for common IEEE journals. You can:
- Edit existing full name/abbreviation pairs
- Add new journal mappings using the "Add" button
- Export/import your custom mapping configuration as JSON


## License

This is a small tool - feel free to use and modify as needed.
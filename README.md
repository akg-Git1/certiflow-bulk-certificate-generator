# CertiFlow — Bulk Certificate Generator

CertiFlow is a browser-based tool for generating personalized certificates in bulk from a certificate template and participant spreadsheet.

## Live Demo

https://certiflowbyansh.netlify.app/

## Features

- Upload a certificate template in PDF, PNG, or JPG format.
- Import participant data from CSV, XLSX, or XLS files.
- Preview spreadsheet columns and participant records.
- Add, drag, resize, and position text-field boxes visually on the certificate template.
- Customize text font, size, color, alignment, bold, italic, underline, and box dimensions.
- Generate an individual PDF certificate for each participant.
- Download individual certificates together as a ZIP archive.
- Export all generated certificates as one combined PDF.

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- [PDF-Lib](https://pdf-lib.js.org/) — PDF creation and editing
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF template preview
- [SheetJS](https://sheetjs.com/) — spreadsheet parsing
- [JSZip](https://stuk.github.io/jszip/) — ZIP archive generation

## Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/certiflow-bulk-certificate-generator.git
   ```

2. Open the project folder.
3. Start a local static server, or open `index.html` in a modern browser.
4. For best results, use a current version of Chrome, Edge, or Firefox and keep an internet connection available so the libraries loaded from CDN can be accessed.

No application backend or build step is required for this version.

## How to Use

1. Upload a blank certificate template (PDF, PNG, or JPG).
2. Upload a participant spreadsheet (CSV, XLSX, or XLS).
3. Select a spreadsheet column and add a field box.
4. Drag and resize the field box on the template preview.
5. Customize the text styling and repeat for other fields.
6. Generate certificates and download either the ZIP archive or combined PDF.

## Privacy Note

This version reads the selected template and spreadsheet in the browser. The application code does not contain an application server or an upload endpoint for sending participant files to a backend. Third-party JavaScript libraries are loaded from public CDNs.

## Project Structure

```text
certiflow-bulk-certificate-generator/
├── index.html
└── README.md
```

## Author

**Ansh Kumar Gupta**  
B.Tech, Computer Science and Engineering  
United Institute of Technology, Prayagraj

- LinkedIn: https://www.linkedin.com/in/ansh-kumar-gupta-759061332/
- GitHub: https://github.com/akg-Git1
- Live Project: https://certiflowbyansh.netlify.app/

# Export Instructions for Luis Melian's CV

This document provides instructions on how to export the CV files in both English and Spanish formats. Follow the steps below to ensure a successful export.

## Prerequisites

Before exporting the CV, ensure you have the following tools installed:

- **Markdown Processor**: A tool like Pandoc or Markdown to PDF converter.
- **Node.js**: Required for running any scripts if needed.

## Steps to Export

1. **Clone the Repository**:
   Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/yourusername/luis-melian-cv.git
   ```

2. **Navigate to the CV Directory**:
   Change your directory to the CV folder:
   ```
   cd luis-melian-cv/cv
   ```

3. **Export the English CV**:
   To export the English version of the CV, use the following command (assuming you are using Pandoc):
   ```
   pandoc luis-melian-cv-en.md -o luis-melian-cv-en.pdf
   ```

4. **Export the Spanish CV**:
   To export the Spanish version of the CV, use the following command:
   ```
   pandoc luis-melian-cv-es.md -o luis-melian-cv-es.pdf
   ```

5. **Styling the CV**:
   If you want to apply custom styles, ensure that the `styles.css` file is referenced in your export command. For example:
   ```
   pandoc luis-melian-cv-en.md -o luis-melian-cv-en.pdf --css=assets/styles.css
   ```

6. **Check the Output**:
   After running the export commands, check the output directory for the generated PDF files.

## Additional Notes

- Ensure that all dependencies are installed and up to date.
- For any issues during the export process, refer to the documentation of the Markdown processor you are using.

By following these instructions, you should be able to successfully export the CV files in both English and Spanish formats.
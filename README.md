# Luis Melian's CV Repository

This repository hosts the Markdown files for Luis Melian's CV in both English and Spanish, along with the necessary assets and documentation for exporting and deploying the CV.

## Project Structure

```
luis-melian-cv
├── cv
│   ├── luis-melian-cv-en.md       # English version of the CV
│   ├── luis-melian-cv-es.md       # Spanish version of the CV
│   └── assets
│       └── styles.css              # CSS styles for formatting the CV
├── docs
│   └── export-instructions.md       # Instructions for exporting the CV files
├── .github
│   └── workflows
│       └── deploy.yml              # GitHub Actions workflow for deployment
├── .gitignore                       # Files and directories to ignore in Git
└── README.md                        # Documentation for the project
```

## Setup Instructions

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/yourusername/luis-melian-cv.git
   ```

2. Navigate to the project directory:
   ```
   cd luis-melian-cv
   ```

3. Open the `cv` directory to find the CV files in both English and Spanish.

4. To view the CV, you can open the Markdown files in a Markdown viewer or convert them to PDF using a Markdown to PDF tool.

## Usage Guidelines

- The `styles.css` file can be modified to change the appearance of the CV when rendered.
- Follow the instructions in `docs/export-instructions.md` for exporting the CV files to different formats.
- The GitHub Actions workflow in `.github/workflows/deploy.yml` automates the deployment process. Ensure that you have the necessary permissions and configurations set up in your GitHub repository.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements for the CV or the repository.
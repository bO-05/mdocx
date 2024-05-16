# MDocx

Markdown to DOCX Converter. This simple script processes all Markdown (`.md`) files in the `files` folder and generates corresponding DOCX files for each Markdown file that doesn't already have a DOCX file. The script checks all files inside the `files` folder and converts them one by one until all Markdown files are successfully converted.

## Prerequisites

- Python 3.x
- Required Python packages (`markdown2`, `python-docx`, `beautifulsoup4`)

## Installation

1. Clone the repository or download the script and the `requirements.txt` file.

2. Install the required packages using pip:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure that all your Markdown files are placed in a folder named `files` in the same directory as the script.

2. Run the script:

    ```sh
    python generate_doc.py
    ```

3. The script will process each Markdown file in the `files` folder and create a DOCX file for each one that doesn't already have a corresponding DOCX file. The DOCX files will be saved in the same `files` folder.

## Project Structure
```md
/project-root
├── files/
│ ├── example.md
│ └── ...
├── generate_doc.py
├── requirements.txt
└── README.md
```

## Example

Suppose you have a Markdown file named `example.md` in the `files` folder. After running the script, a corresponding `example.docx` file will be generated in the same folder if it doesn't already exist.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
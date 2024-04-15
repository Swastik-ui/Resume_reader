# Resume_reader

To include a README file with instructions on how to run the program, you can create a new file named `README.md` in the same directory as your Python script. Here's an example README file that provides instructions for running your program:

```markdown
# PDF Summarization Program

This program extracts text and metadata from PDF files, generates summaries, and writes the output to a CSV file.

## Installation

1. Install Python (if not already installed): [Python Downloads](https://www.python.org/downloads/)
2. Install required Python packages:

   ```bash
   pip install PyPDF2 sumy
   ```

## Usage

1. Place your PDF files in the same directory as this script.
2. Update the `file_names` list in the script with the names of your PDF files.
3. Run the script:

   ```bash
   python pdf_summarizer.py
   ```

4. The program will process each PDF file, generate a summary, and write the output to `output.csv`.

## Notes

- Make sure the PDF files are accessible and not corrupted.
- The program uses the LSA (Latent Semantic Analysis) summarizer from the sumy library. You can adjust the summarization method or parameters as needed.
```

Feel free to modify the README file to include any additional information or customization specific to your program.

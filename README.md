To include a README file with instructions for running the program, you can create a new file called `README.md` in the same directory as your Python script. Here is an example README file that provides instructions for running your program:

``Markdown
# pdf summarization program

This program extracts text and metadata from PDF files, generates a summary, and writes the output to a CSV file.

## Establishment

1. Install Python (if not already installed): [Python Downloads](https://www.python.org/downloads/)
2. Install required Python packages:

   ``Bash
   pip install PyPDF2 sumy’’


## Use

1. Place your PDF files in the same directory as this script.
2. Update the `file_names` list in the script with the names of your PDF files.
3. Run the script

``Bash
   python pdf_summarizer.py
   ,

4. The program will process each PDF file, generate a summary, and write the output to `output.csv`.

## notes

- Make sure PDF files are accessible and not corrupted.
- The program uses LSA (Latent Semantic Analysis) summaries from the Sumi library. You can adjust the summarization method or parameters as needed.
,

Feel free to modify the README file to include any additional information or customizations specific to your program.


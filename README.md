# PDF Topic Generator 📄💡

Welcome to the PDF Topic Generator project! This Python script generates a PDF document based on topics and page counts specified in a CSV file.

## What is it? 🤔

The PDF Topic Generator is a Python script that automates the creation of PDF documents. It reads data from a CSV file containing topics and their respective page counts, and generates a PDF document with each topic listed along with its corresponding number of pages. This tool is handy for creating topic outlines, study guides, or any document that requires a structured layout based on topic headings.

## Skills Used 🚀

- **PDF Generation**: Utilizes the `fpdf` library for creating PDF documents programmatically, setting font properties, and drawing text and lines.
  
- **Data Manipulation**: Harnesses the power of `pandas` for reading data from a CSV file, iterating over DataFrame rows, and extracting relevant information for PDF generation.
  
- **Control Flow**: Implements control flow logic to iterate over DataFrame rows, add pages to the PDF based on specified page counts, and set footers for each page.

## How to Use 🛠️

1. Ensure you have Python installed on your system.
2. Install the required libraries by running `pip install fpdf pandas`.
3. Prepare your data in a CSV file with columns for topics and their corresponding page counts.
4. Run the script, providing the CSV file path as input.

## Example Usage 📝

```bash
python generate_pdf.py topics.csv
```

This will generate a PDF document based on the topics and page counts specified in `topics.csv`.

## Contributions and Feedback 🙌

Contributions, feedback, and suggestions are welcome! Feel free to open an issue or submit a pull request if you have any ideas for improving this project.

Let's create beautifully organized PDF documents together! 🌟

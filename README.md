# Medical AI Prompter

## Overview

Medical AI Prompter is a machine learning-driven tool designed to automate the extraction and verification of data from academic research, specifically in the field of rare diseases. By leveraging advanced AI techniques, this tool helps researchers ensure that the data they extract from literature is accurate and consistent with the original findings, saving valuable time and reducing errors.

## Key Features

- **Data Extraction**: Seamlessly extracts quantitative and qualitative data from large volumes of academic papers.
- **Automated Verification**: Uses machine learning algorithms to cross-check extracted data with information in the literature, ensuring accuracy.
- **Streamlined Data Management**: Organizes extracted data in a user-friendly format, making it easier to analyze and interpret.

## Why Use Medical AI Prompter?

- **Efficiency**: Eliminate manual review of papers and streamline your research workflow.
- **Accuracy**: Increase confidence in your data with automated verification against existing literature.
- **Scalability**: Ideal for large-scale research projects where managing hundreds of papers is challenging.

# Extraction Tool - Step-by-Step Guide

This tool allows you to extract data from PDF files using Google Colab.

## Step 1: Upload PDF Files to Colab

1. Open **Google Colab**.
2. On the left sidebar, click the **Files** icon (folder icon).
3. Click on **Upload** to add your PDF files to the Colab file system.
4. Ensure that your PDF files are named appropriately (e.g., `one.pdf`, `1.pdf`). The names should correspond to the file names you will reference in the code.

## Step 2: Open the Notebook and Set Up the Environment

1. Open the Jupyter notebook file (`Extraction Tool.ipynb`).
2. Run the **first cell** to import necessary libraries and set up the environment. This prepares the tool for extracting data from the uploaded PDFs.

## Step 3: Specify PDF Name for Extraction

1. In the notebook, locate the cell where you need to specify the PDF file name.
2. Change the PDF file name in the code to match the file you want to extract data from. For example:
   ```python
   pdf_name = "one.pdf"
   ```
3. Run the cell to extract data from the specified PDF file.

## Step 4: View the Extracted Data

1. Once the data is extracted, you can view the output directly in the notebook's output section.
2. If you need to extract from multiple files, repeat **Step 3** by changing the `pdf_name` to another file (e.g., `pdf_name = "2.pdf"`).

## Step 5: Repeat for Additional PDFs

- To process another PDF, simply update the PDF file name in the code to the next file you want to extract from.
- Example:
   ```python
   pdf_name = "2.pdf"
   ```
- Run the extraction process again to view the new data.

## Step 6: Clean Up (Optional)

1. Once you're done extracting data, you can remove the uploaded files from the Colab file system by clicking the **trash icon** next to the file name in the left sidebar.

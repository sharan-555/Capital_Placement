# Capital_Placement
The assignmet consists of 3 tasks
Task1: PDF Data Extraction
Objective: Extract details from CVs in PDF format.
Dataset: Kaggle Resume Dataset
Instructions:
    Download the Kaggle "resume dataset".
    Build a PDF extractor using Python, leveraging libraries such as PyPDF2 or PDFMiner.
    Extract the key details:
    Category (Job role)
    Skills
    Education (Degree, Institution)
*************************************************************************************************************************
Task2:Job Description Data Understanding

Objective: Fetch and comprehend job descriptions from the Hugging Face dataset.
Dataset: Job Descriptions from Hugging Face
Instructions:
    Use the Hugging Face datasets library to fetch the job descriptions. For this task, consider extracting 10-15 job descriptions.
*************************************************************************************************************************
Task3:Candidate-Job Matching
Objective: Match extracted CV details against the fetched job descriptions based on skills and education.

Tools Suggested: Use the Transformers library by Hugging Face. BERT or DistilBERT can be a starting point for embedding extraction.

Instructions:
Tokenize and preprocess both the job descriptions and the extracted CV details from the PDFs.
Convert the tokenized text into embeddings using a pretrained model like DistilBERT from Hugging Face.
For each job description, calculate the cosine similarity between its embedding and the embeddings of the CVs.
Rank CVs based on this similarity for each job description.
List the top 5 CVs for each job description based on the highest similarity scores.





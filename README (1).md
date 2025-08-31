# Resume Screening Project

## Description

This project automates screening of resumes by extracting text from PDF and DOCX files, analyzing the content, and ranking candidates based on how well their resumes match a job description and their years of experience.

**Note:**  
- Resumes were originally accessed directly from Google Drive.  
- For testing, sample resumes are provided in the `Resumes` folder in this repository.

## How to Use

1. Put your resumes (PDF or DOCX) in the `Resumes` folder.  
2. Modify the `job_description_text` in the code with your job requirements.  
3. Run the script to see the top matching candidates ranked by combined similarity and experience score.

## Requirements

Install required Python packages:

``pip install python-docx PyPDF2 nltk scikit-learn docx2txt pandas numpy``

## Output

The script prints a ranked list of candidates showing:

- Candidate name  
- Similarity score with job description  
- Extracted years of experience  
- Combined ranking score  

## License

This project is open source and free to use.


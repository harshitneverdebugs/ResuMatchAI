# Resume Shortlisting and Ranking System

This project implements a resume shortlisting and ranking system that utilizes keyword matching and semantic similarity scoring to help recruiters identify suitable candidates based on their resumes.

## Features

- **Data Cleaning**: The system processes resumes by removing unnecessary characters, URLs, and special symbols to ensure cleaner text data.
- **Keyword Search**: Users can input specific keywords to filter resumes, allowing for targeted searches based on qualifications or skills.
- **Semantic Similarity Scoring**: The system ranks shortlisted resumes based on their similarity to a reference resume, using advanced embedding techniques to measure semantic relationships.

## Requirements

To run this project, the following Python libraries are required:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **seaborn**: For data visualization (optional).
- **sentence-transformers**: For computing sentence embeddings and similarity scoring.

Make sure to install the necessary packages via pip if you haven't already.

## Getting Started

1. **Mount Google Drive**: The project requires access to a CSV file containing resume data stored in Google Drive. Begin by mounting your Google Drive to access the dataset.

2. **Load the Dataset**: The project loads the resume dataset, allowing you to inspect its contents and structure.

3. **Data Exploration**: You can explore the dataset for missing values and understand the distribution of categories in the resumes.

4. **Clean Resumes**: The system cleans the resume text using regular expressions to ensure that the data is free of unwanted text and is in a uniform format.

5. **Shortlist Resumes**: Users are prompted to input keywords for filtering resumes. The system will display the shortlisted resumes that contain any of the specified keywords.

6. **Rank Resumes**: The shortlisted resumes are ranked based on their similarity scores, calculated using a pre-trained model. This allows recruiters to quickly identify the most relevant candidates.

## Conclusion

The Resume Shortlisting and Ranking System provides a comprehensive solution for filtering and ranking resumes based on keywords and semantic similarity. This tool can significantly streamline the recruitment process, enabling faster and more effective candidate selection.

## Future Enhancements

Potential future enhancements for this project include:

- Adding a user interface for a more intuitive experience.
- Integrating additional machine learning models for improved ranking accuracy.
- Allowing for bulk uploading and processing of resumes.
- Saving the ranked resumes to a file for easy access and review.

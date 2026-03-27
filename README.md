Text File Plagiarism Checker App

A web application that compares two text files and detects similarity using text-based comparison techniques. 

Check out the live website https://plagiarism-app-1.onrender.com/

Features
* Upload two text files for comparison
* Automatic text processing and normalization
* Calculates similarity using cosine similarity
* Displays plagiarism level:
    * Highly Plagiarised
    * Medium Plagiarised
    * Negligible
* Simple and user-friendly interface

Tech Stack
* Python
* Flask
* Scikit-learn
* HTML, CSS

File Input Format
* Both uploaded files should be text files (.txt)
* Files should contain readable textual content

How It Works
1. User uploads two text files
2. App reads and decodes file content
3. Converts text to lowercase for uniform comparison
4. Converts text into vectors using CountVectorizer
5. Computes cosine similarity between the two texts
6. Calculates similarity score (in percentage)
7. Classifies result:
    * Score > 70 → Highly Plagiarised
    * Score > 40 → Medium Plagiarised
    * Otherwise → Negligible
8. Displays the plagiarism result

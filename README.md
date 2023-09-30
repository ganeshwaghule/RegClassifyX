# RegClassifyX: Post Approval Variations Classifier
RegClassifyX is a sophisticated tool designed to classify post-approval variations in the pharmaceutical industry. It utilizes a pre-trained Multinomial Naive Bayes classifier along with TF-IDF Vectorizer to predict the Variation Category based on the user-inputted Change Description. The tool generates a structured and detailed report in PDF format, which can be downloaded by the user.

# Author
1. Ganesh Waghule
2. Ashwini Kumawat

# Process Flowmap of RegClassifyX


# Features
**1. User-Friendly Input:** Accepts user input for Change Description.

**2. Advanced ML Model:** Employs a pre-trained Multinomial Naive Bayes classifier & TF-IDF Vectorizer.

**3. Accurate Predictions:** Uses a comprehensive dataset for accurate Variation Category predictions.

**4. Structured Reporting:** Generates a detailed report containing Change Description, Change Type, Predicted Variation Category, Reference, Author, and a Note.

**5. PDF Conversion & Download:** Converts the generated report to PDF format and allows users to download it.

# Workflow
**1. Start:** Initiates the process.
**2. Input (Change Description):** User inputs the Change Description.
**3. Load Pre-Trained Model:** Loads the Multinomial Naive Bayes classifier & TF-IDF Vectorizer.
**4. Load Dataset:** Loads the dataset containing Change Descriptions, Change Types, and Variation Categories.
**5. Identification:** Identifies the Variation Category based on the user input using the pre-trained model and dataset.
**6. Generate Report:** Creates a structured report with a timestamp.
**7. Output as PDF:** Converts the generated report to PDF format.
**8. Download PDF:** Allows the user to download the generated PDF report.

# Dataset
The dataset used in this tool contains detailed information about Change Descriptions, Change Types, and Variation Categories in the pharmaceutical industry. It serves as a foundational reference for making accurate predictions.

# Model
RegClassifyX utilizes a pre-trained Multinomial Naive Bayes classifier in conjunction with a TF-IDF Vectorizer to analyze and predict the Variation Category based on the provided Change Description.

# Installation on Google Colab
**1. Open Google Colab:** Navigate to Google Colab.
**2. Upload Notebook:** Click on Upload and select the notebook file from your system.
**3. Mount Google Drive:** Follow the instructions in the notebook to mount your Google Drive.
**4. Run Cells:** Execute the cells in sequence to load the model, dataset, and run the tool.
**5. Input Change Description:** Enter the Change Description when prompted and view the generated report.

# Disclaimer
This tool is an illustrative example of applying AI and ML models for classifying post-approval variations. Users are advised to use this tool with due diligence and consideration, understanding that the predictions are based on the provided dataset and pre-trained model.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.

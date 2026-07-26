# 🛡️ PIIMa - Protect sensitive patient medical records easily

[Download PIIMa for Windows](https://github.com/Alexander4930/PIIMa)

## 📋 About the project

PIIMa helps you remove sensitive personal information from Turkish medical documents. Medical files often contain data like names, ages, or identification numbers. This software detects this data and hides it before you share or store the files. It helps organizations follow privacy laws like KVKK and HIPAA by keeping patient identities private.

The tool currently finds and masks structured data such as identification numbers and contact details. We continuously improve the system to identify patient names and other text-based identifiers.

## 💻 System requirements

Before you install PIIMa, ensure your computer meets these standards:

*   Operating System: Windows 10 or Windows 11.
*   Processor: An Intel Core i5 or AMD Ryzen 5 or better.
*   Memory: You need at least 8 GB of RAM.
*   Storage: You need 500 MB of free space on your hard drive.

## 🚀 How to install and run PIIMa

Follow these steps to get the software on your machine:

1.  Visit the [PIIMa download page](https://github.com/Alexander4930/PIIMa).
2.  Look for the latest version under the Releases section.
3.  Click the file ending in .exe to start the download.
4.  Open the folder where you saved the file.
5.  Double-click the PIIMa installer file.
6.  Follow the instructions on your screen to complete the setup.
7.  Find the PIIMa icon on your desktop and double-click it to start the application.

If Windows shows a security warning, click "More info" and then select "Run anyway." This happens because the app is new and your computer does not recognize the publisher yet.

## 🔧 How to process your documents

Once the app opens, you will see a simple control panel. Use these steps to remove sensitive data:

1.  Click the "Open File" button.
2.  Select the document you wish to clean from your folders.
3.  Choose the folder where you want to save the new, cleaned version of the file.
4.  Click the "Start Process" button.
5.  Wait for the progress bar to finish.
6.  Open your output folder to view the file with hidden identifiers.

The software creates a new copy of your document. It never changes or deletes your original files. You stay in full control of your records at all times.

## 🔐 Privacy and security

PIIMa processes your documents directly on your computer. Your data never leaves your machine. We do not use cloud servers or third-party services to check your files. All work happens within your local environment. This approach ensures that your sensitive medical information stays between you and your computer.

The application uses advanced logic to spot privacy risks. It relies on a process called named entity recognition. This allows the tool to look at every word in a document and determine if it belongs to a category like a medical ID or a phone number. By focusing on Turkish language patterns, PIIMa provides accurate results for local clinical documents.

## 💡 Troubleshooting common issues

If you encounter problems, check these solutions:

*   The program does not open: Ensure you have the latest updates for your Windows system.
*   The window looks cut off: Check your display settings in Windows to ensure your scale is set to 100%.
*   The app freezes: Close any programs that use large amounts of memory before you run PIIMa again.
*   Unsupported file types: Currently, PIIMa works best with text files and standard document formats. If your file does not show up in the open dialog, try converting it to a plain text file first.

## 🧪 Testing the accuracy

We built this tool to meet strict standards. You can help us by checking the output files after the process finishes. If the software misses a piece of personal data, please report it through the GitHub issues page. Each report helps the team improve the logic for future versions. Your feedback directly impacts how well the tool handles complex clinical notes.

## 📂 Project details

PIIMa is a tool for developers and medical professionals alike. By using the Rust programming language, it achieves high speed and safety. We designed it to run on-device, which removes the need for internet connectivity during the tagging process. This design choice makes it ideal for hospitals and clinics that require offline privacy.

Keywords: benchmark, clinical-nlp, deidentification, healthcare, hipaa, kvkk, named-entity-recognition, nlp, on-device, phi, pii, privacy, rust, turkish
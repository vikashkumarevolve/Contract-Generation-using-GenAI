# Contract-Generation-using-GenAI

Overview
This project is a contract generation tool powered by Generative AI (GenAI) and Azure OpenAI that allows users to dynamically create legal contracts based on their input. The tool supports various types of agreements such as Non-Disclosure Agreements (NDAs), Employment Agreements, Partnership Agreements, and Rent Agreements.

With a user-friendly interface built on Streamlit, the tool enables users to generate contracts, refine them using GPT-based models, and download the output as a Word document (DOCX).

Features
Automated Contract Generation:

Users can input contract details like company name, partner/tenant details, contract terms, and more.
Contracts are generated dynamically based on flexible templates.
AI-Powered Refinement:

The contracts aren’t just templates! The tool integrates with Azure OpenAI’s GPT model to intelligently refine and enhance contracts with precise legal language.
DOCX Export:

Contracts can be seamlessly downloaded as Word documents, making them easy to edit and share.
Error Handling:

The tool ensures smooth execution with robust error handling. If a directory doesn’t exist, it’s created automatically, ensuring that all contracts are securely saved.
Why Use This Tool?
Efficiency: Automatically generate legal documents, reducing the time and effort involved in manual contract creation.
Consistency and Accuracy: By leveraging AI, contracts are generated with consistent legal language, reducing errors.
Scalability: Whether you're generating one contract or hundreds, the tool scales effortlessly to meet your needs.
Customization: Tailor contracts to your specific requirements while maintaining compliance with legal standards.
Future Enhancements
E-Signature Integration: To allow for seamless signing of contracts after generation.
Version Control: To track changes and manage multiple contract versions.
Multi-language Support: To generate contracts in different languages.
Tech Stack
Azure OpenAI: For refining contract language using GPT models.
Streamlit: Provides the user interface for input and interaction.
Python-Docx: Used to export the contracts as Word documents (DOCX).
Python: Backbone of the application, handling contract generation, AI integration, and document export.
How to Use
Clone the repository and navigate to the project directory.
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:
bash
Copy code
streamlit run contract_generator.py
Input the details for your contract (e.g., company name, tenant/partner details) and click "Generate Contract".
Once the contract is generated, click Download Contract as DOCX to save the document.

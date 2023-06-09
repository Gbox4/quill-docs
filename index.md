# Quill Documentation
This document describes usage of QuillAI's web application for financial research, which can be logged into here(app.quillai.co).
What follows are key features and recommended usage patterns of QuillAI. Contact kartik@quillai.co with questions or requests for new features. 

This documentation is live, and it changes with updates to Quill's platform. Users will be notified of all updates to the platform. Happy Quilling!

## Chat
Chat is the primary interface for interacting with uploaded data tables and Quill's pre-processed quantitative data. The pre-processed data includes prices and various numerical ratios for all stocks listed on the NYSE and NASDAQ, as well as numerical line item data from SEC 10-K and 10-Q filings. 

To start a chat session, click the yellow '+' icon and select a dataset using the dropdown menu. Any datasets you have uploaded in the data tab will appear as options here, in addition to the pre-processed datasets. 

### The Chat interface
![Image not found!](/quill-docs/Screen Shot 2023-05-29 at 1.27.33 PM.png)

The chat interface is a place to ask questions and perform manipulations on your chosen data. Treat it like a ChatGPT specially trained on the chosen dataset. The bottom-left corner contains three icons: 
1. Available Columns (Three Bars Icon) - This icon displays all available columns in the dataset.
2. Verbose Output (Hat Icon) - This icon toggles a verbose output option, which displays an English description of the actions taken by Quill when running your prompt.
3. Follow-On (Arrow Icon) - This icon indicates to Quill that your prompt is a follow-on to the previous prompt. Toggle it to retain information from one response to the next.

You can ask for summary statistics, generate tables, and turn those tables into graphs. Chat's functionalities are table-based, so prompts such as "show 5 rows of the dataset" and "build a table with ...", or follow-on prompts such as "add a column to that table with ..." perform well.

Prompting Quill produces a response. At the top-right of the response box, a code icon '</>' allows you to view the code generated by Quill to run your prompt on the chosen dataset. The top-left contains thumbs up and thumbs down icons to upvote or downvote a response; this is optional and helps Quill fine-tune its algorithms to better answer your future questions. The trash icon allows you to delete a prompt.

## Brief
Brief is the primary interface for interacting with text-based data on Quill. Brief allows you to intelligently search your inputted data for key sentences matching the semantic meaning of your search phrase. To input data, paste any length of text into the input box. Support for PDF uploads is coming soon.

![Image not found!](/quill-docs/Screen Shot 2023-05-29 at 1.50.10 PM.png)

Entering a search phrase produces a response highlighting the key sentences of the original document which relate to that search phrase. Clicking on the key sentences highlights the position in the original document from which they were identified.

## Data
The Data tab is the primary interface for uploading custom datasets for use in the Chat tab. Use the '+' icon to add a dataset, which you can then access in the Chat tab when creating a new chat session.

![Image not found!](/quill-docs/Screen Shot 2023-05-29 at 2.56.33 PM.png)

## Contact
For questions and feature requests, contact kartik@quillai.co.



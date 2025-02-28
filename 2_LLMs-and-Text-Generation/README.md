## Project: Build Your Own Custom Chatbot

### Code

| Criteria                | Submission Requirements                                                                                                                                    |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data Wrangling          | Project dataset is loaded into a `pandas` dataframe containing at least 20 rows. Each row in the dataset contains a text sample in a column named `"text"` |
| Custom Query Completion | The project successfully sends a custom query with information from the project dataset to the OpenAI model and gets a response                            |

### Scenario

| Criteria                                                                      | Submission Requirements                                                                                                                                                                                                                                                                                    |
|-------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Demonstrate that custom prompts enhance the performance of the OpenAI model   | The notebook includes at least two questions that result in different answers when using the custom prompt compared to a basic prompt to the same model. <br><br>This means that there should be 4 total Q&A pairs: 2 questions with the custom answers and those same 2 questions with the basic answers. |
| Select a dataset for generating custom prompts and explain the rationale      | The notebook includes at least one sentence explaining why the chosen dataset is appropriate for this application.                                                                                                                                                                                         |

### Suggestions to Make Your Project Stand Out

1. Use a `while` loop and the built-in `input` function to allow the user to type questions repeatedly rather than having to edit the content of strings in the code cells.
2. Take a closer look at your dataset and perform additional data cleaning to remove irrelevant content or augment the content.

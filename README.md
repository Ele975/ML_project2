The aim of the project is to apply machine learning techniques to build a question-answering system, and then make the system voice interactive, by connecting it to a speech-to-text and text-to-speech models.

Briefly describe the chosen dataset (EDOS or SQuAD2.0):
- What type of documents does it contain and how many documents are there?
- Calculate and visualise statistics for the collection, e.g. distributions over document length and vocabulary size.

Play around with documents using some of code from the course. You could, for example:
- train a Word2Vec embedding on the documents and investigate its properties.

Each of the datasets comes with a particular task that you can perform, so:
- train a model to perform that task (by fine-tuning Transformers / LSTMs / linear models on the training data).
- evaluate the different methods and compare their performance across a representative test set.

3. Add voice interactivity:
Make use of text-to-speech and speech-to-text models to add voice interaction
- Investigate how effective and reliable the voice interactive components are.
- If they are not particularly reliable, how might you change them to make them more robust?

# fema-experiments

* An LLM chatbot I created that reads in the FEMA Strategic Plan and answers questions about it. Based on the `distilbert-base-uncased-distilled-squad` model.
* An example of working with the OpenFEMA API to load data from its PA Project Details dataset, while respecting its 1000 record throttle.
  It takes advantage of PySpark to allow loading a large dataset, and will update the dataset as new records become available.

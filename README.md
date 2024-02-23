# US-census-data-assessment
## US Census Bureau 2017 Basic Monthly CPS Analysis with Apache Spark and Pandas
This repository contains a Jupyter notebook, the US Census Bureau's 2017 Basic Monthly CPS dataset, and the data documentation. The Jupyter notebook analyzes the dataset using Apache Spark with Python or Scala and answers four key questions about the dataset.
Dataset
The dataset consists of individual responses captured by the U.S. Census Bureau's 2017 Basic Monthly CPS. The dataset is available in the form of a dat file which was downloaded from the official U.S. Census Bureau website. The data documentation provides information on the structure of the dataset and how to decode any encoded values.
## Usage
- Clone this repository to your local machine.
- Extract the `.dat` file in the zip folder.
- Open the Jupyter notebook and run the cells to load the dataset, perform the necessary transformations, and answer the four main questions listed in the original assessment document.
Results will be displayed in the notebook and can be saved as needed.
Questions
#### The Jupyter notebook answers the following four questions:     
- What is the count of responders per family income range (show top 10)?     
- What is the count of responders per geographical division/location and race (show top 10)?     
- How many responders do not have telephone in their house, but can access a telephone elsewhere and telephone interview is accepted (show top 10)?     
- How many responders can access to a telephone, but telephone interview is not accepted (show top 10)?

**Note:** Where a value is encoded, the Jupyter notebook decodes the value and returns the actual value.
Feel free to explore the Jupyter notebook and modify it according to your needs. Pull requests are welcome!

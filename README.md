# binary-independence-model

## a notebook and python code aimed at demonstrating information retrieval using binary independence model

##example usage
implementing this code is as easy as importing the BIMModel class, then search the query, with the limit of documents you want to retrieve

from model import BIMModel

bim_model = BIMModel()
bim_model.search_query("secondary emission of electrons by positive ion bombardment of the cathode", 10)

##how to run code
### python ( .py files ) codes
* 1.	Change the path and labels_path variable  in the datahandler class and the query path in the model class
* 2.	Change the limiter variable of datahandler class to the size of your dataset
* 3.	Install all necessary packages
*  4. create python file and implement the BIMModel.search_query(search_query, N_retrieved_docs)


### notebook
* 1. take a small course on how to use jupyter notebook/google colab


# Code is provided in google colab and in *.ipynb
## Using Google Colab 
To Access google colab, you will need a gmail/google account.
You can access and run code on google colab by following links in the *.txt files, but you will
need to download the data files from this repository for run through.  

###############

## Using *ipynb's 
These files were ported over from the google colab.  It is more difficult to keep track of
where you are when compared to Google Colab and tensorflow and keras need to be installed 

pip install keras
pip install seaborns
pip install pandas
pip install numpy 
pip install tensorflow 

In adition to installing these libraries, tensorflow requires a manual binary build from their server for any Windows Computer.  


#


 
You will not be able to initially run through all the cells, as it will ask for a file input early on, and when it tries to save it will error/pause  because of authentication. 

NNXL models are also included in these .ipynbs because the scalation code was bugged by giving too good of results...this is implemnteded at the END

WARNING:  Boston forward Select in python takes a VERY long time, you can skip over this part to use the the columns we already discovered being best for hte NNXL for BOSTON. 

Seattle forward select takes ~20 mins and there is no shortcut included in this file.  



PLEASE FOLLOW THE LINKS ON EACH .txt FILE TO SEE IPYNB/PYTHON CODE!

Compiled results and analysis are found in the ./ResultsAndSummary directory.  

Abstract of probem and initial roadmap found in Abstract.docx

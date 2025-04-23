# Text Analysis and the Humanities
This is a Workshop introducing Humanities Students to the Main Concepts of Computational Text Analysis. 
In here you can find material and code to analyse the Scottish Statistical Accounts Data and see computational method in practice.

## Content of the Repository
The repository contains both the code and the material you are going to need to play around with the dataset. 
If you only want to visualise the notebook without running its content you can visualise it at [this address](Addlink.html).

## Prerequisites
Some basic familiarity with Python Notebooks is assumed, but no previous knowledge of text analysis is required.


## Learning Outcomes

- Working knowledge of principal methods to clean and wrangle text-based data
- Awareness of the pre-processing steps of text analysis, such as tokenisation and stop words removal
- Working knowledge of basic techniques of text analysis, such as word frequencies and keywords in context
- Awareness of unstructured data visualisation techniques

  
## How to use it

### 1. On Noteable 
1. Open the following link in a new tab https://noteable.edina.ac.uk/login
2. Log in with your EASE credential
3. Select _Standard Python 3_ and press start
4. On the top bar, go to Git> Clone a Repository
5. Enter the link to this repo 'https://github.com/DCS-training/Text-Analysis-and-the-Humanities'
6. Press Clone
7. On the left side, you can now see a folder with the same name as the repo with a series of files within it. Double click on the 'NotebookTextAnalysis.ipynb'


### 2. Run the notebooks via Google Colab

1. Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. If you are not already logged in, you will be prompted to log-in via Gmail
3. Go to the GitHub header, click on Open Colab
4. Select GitHub
5. Enter the link to this repo 'https://github.com/DCS-training/Text-Analysis-and-the-Humanities'
6. Click on 'NotebookTextAnalysis.ipynb' to open the notebook


### Using the Notebook
The Notebook contains paragraphs of explanatory text interspersed with grey cells containing code blocks. To run a code block and see the result:

1.  Place your cursor within the cell
2.  Click the 'Run' button on the top menu
4.  The results of running this code will appear below
5.  If the results don't appear immediately, check the icon in the browser tab. AN egg-timer icon indicates it is processing the code.
6.  It is best to follow the Notebook from top to bottom as some code blocks will depend on results from previous cells
7.  You can edit code blocks yourself and run them to see the results of your changes

## Data 
The data in here has been collected from the Scottish Statistical Accounts Data https://collectionsmanager.is.ed.ac.uk/handle/10683/119269 and the National Records of Scotland https://www.nrscotland.gov.uk/statistics-and-data/geography/our-products/other-national-records-of-scotland-nrs-geographies-datasets/historic-civil-parishes-pre-1891. 

The Statistical Accounts of Scotland are a series of documentary publications, related in subject matter though published at different times, covering life in Scotland in the 18th and 19th.

The Old (or First) Statistical Account of Scotland was published between 1791 and 1799 by Sir John Sinclair of Ulbster. The New (or Second) Statistical Account of Scotland published under the auspices of the General Assembly of the Church of Scotland between 1834 and 1845. These first two Statistical Accounts of Scotland are unique records of life during the agricultural and industrial revolutions in Europe.

### Data Structure
The original publication has been scanned and OCRed and each single record has been collected in a .txt file. The name of each file contain information about the document itself. For example StAS.2.15.91.P.Orkney.Cross_and_Burness

- StAs.2.15.91 -> Second Statistical Account
- P -> Parish (Contain information from the Parish)

- Orkney -> Area of interest (Scotland has been divided in 33 Areas)

- Cross_and_Burness -> Parish

We are going to see how to use this to extract information about all our text later, but the first thing we need to do is to create a single dataframe (table) that will contain all the texts otherwise, it will be very difficult to manage the data.

**NB** The data are hosted on a separate repository 'https://github.com/DCS-training/EFIDeepDive'. This is to keep the cloning of this repo for teaching faster. We are going to import the dataset in our environment directly via the notebook.

## Licence of the material
All the material collected here is covered by a CC-BY-NC 4.0 License



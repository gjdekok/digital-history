# What should every historian know about DH?

This document evaluates the knowledge and understanding that both students and faculty members of the Leiden University Institute for History should possess when it comes to the field of Digital History. It is structured using the five steps in the research process as documented on the [Programming Historian](https://programminghistorian.org/en/lessons/). For every step, we include skills that every historian needs to have in this digital age. Then we list some skills that can be taught to Digital History practitioners or specialists. 

## 1. Acquire
This step refers to the process of locating and gathering primary and secondary sources to use in the research. For the (digital) historian, this often involves searching for and accessing digital resources. These may include online (digitized) archives, databases and websites.

### Relevant skills for every historian
* Knowing how to use digital repositories and archives through web-based interfaces
* Knowing how to refer to digital sources (preferably by means of persistent identifiers)
* Knowledge about several file formats (e.g. PDF, JPEG, CSV)
* The difference between structured and unstructured data
* Basic knowledge about copyright and intellectual property laws
* Basic knowledge about data privacy and ethical considerations

### More advanced skills
* Acquiring data through web scraping or data mining
* Communicating with APIs
* Working with Linked Open Data (LOD)
* Writing SQL or SPARQL queries to extract structured data
* Extracting relevant data from structured file formats such as XML or JSON-LD
* Knowledge about emulation to access digital materials made for older hardware or software

## 2. Transform
After acquiring the relevant data, it is often necessary to transform the data before analyzing it. This may include bringing order to unstructured data or doing data cleaning.

### Relevant skills for every historian
* Creating a simple (relational) database scheme
* Using third-party software (e.g. Excel or SPSS) for basic exploratory data analysis to check for inconsistencies, errors or missing data. This may include visualizing the data.
* Using third-party software to sort the data or to format the data (i.e. converting text to numerical values or converting different date formats).
* Normalize data to a predefined vocabulary or list of terms

### More advanced skills
* Using OpenRefine to enrich or clean data
* Doing advanced exploratory data analysis using R or Python packages such as Pandas and Matplotlib
* Use R or Python for data formatting
* Georeference data for displaying on a map
* Using OCR and HTR to extract text from images
* Model the data using common ontologies

## 3. Analyze
After having acquired and transformed a bunch of data, it is ready for the analysis. Because computers work with numerical representations of data, this often includes doing statistical work. Increasingly, computers can interpret natural language (through computational methods), which expands the possibilities.

### Relevant skills for every historian
* Basic descriptive statistics
* Contextualize digital data and reconstruct the provenance trail to understand it
* Basic familiarity with digital tools and software (spreadsheet software, data visualization software)

### More advanced skills
* Advanced statistics (including regression and clustering) using R or Python libraries such as Scikit-Learn
* Using Natural Language Processing techniques to analyze textual data
* Using Jupyter Notebooks
* Writing SQL or SPARQL queries to combine data from different datasets

## 4. Present
This step refers to the process of communicating research findings and arguments, both to an academic and to a general audience. Digital tools can be used to create engaging and accessible presentations.

### Relevant skills for every historian
* Using presentation tools such as Prezi and Powerpoint
* Basic knowledge about the structure of the Web and HTML
* Using social media to effectively communicate research results

### More advanced skills
* Creating webpages for historical research using content management systems such as Wordpress or Drupal
* Writing HTML and using CSS and JavaScript
* Using frameworks such as Shiny, Flask or Django to build a webapp to display interactive historical analyses
* Using git repositories to publish code

## 5. Sustain
The final step of the research process refers to the process of ensuring long-term access and preservation of digital research materials.

### Relevant skills for every historian
* Knowledge about the disadvantages of using proprietary file formats for long-term storage (such as Microsoft Excel) and the advantages of using open formats (such as CSV/TSV)
* Submitting data to (academic) repositories such as Zenodo or DANS
* Working with regular backups
* Attaching relevant metadata to every dataset
* Basic knowledge of the FAIR principles (Findable Accessible Interoperable Reusable)

### More advanced skills
* Transforming data to Linked Open Data so that other researchers can easily find it
* Creating clear documentation (in Markdown format) for code to allow for reuse by others
* Choosing a license along with a distribution of code
* Knowledge about digital forensics to retrieve lost data
* Adherence to cybersecurity standards to safeguard sensitive information or to make sure a data publication cannot be tampered with

![XKCD](https://imgs.xkcd.com/comics/digital_data.png)

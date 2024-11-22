# DOI XML file generator from Excel
## Instalation
- Download and install python from https://www.python.org
- In cmd open repo directory and use:
> pip install -r requirements.txt

## Usage
Generate excel file from Easy Chair and move the file to the folder with the XML-generator.ipynb file.

### Jupter
- In cmd open repo directory and use:
> jupyter notebook
or
> jupyter lab

In order to generate an XML file, set the values ​​in the Variables tab, and then select Cell > Run all from the menu. 

![Cell > Run all ](imgs/1.png)

After the file is generated, the dois.xml and formatted_{filename from Easy Chair}.xlsx files will appear in the folder. There can only be one dois.xml file in the folder - delete it to recreate it.

File formatted_{filename from Easy Chair}.xlsx will not be updated as long as it exists. This means that when the code is restarted, no changes will be made to it.

In addition, markdown files for subpages with abstracts will be created in the gitbook folder.



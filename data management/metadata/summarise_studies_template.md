# Blood Pressure and Arterial Function (BPAF) Laboratory metadata

Metadata provides a summary of all the data generated in a study. It allows:

- someone without access to the data to know what data exists.
- someone with access to the data to understand what data exists, the folder structure, and what variables there are with descriptions of those variables.

## Writing metadata

- json format. Template provided in this folder (000000TPLT.json)
- recommend using [Microsoft Visual Code Studio](https://code.visualstudio.com) with extensions:
  - **[json](https://marketplace.visualstudio.com/items?itemName=Meezilla.json)** For a valid json file, provides a tree view of the data.
  - **[Prettify JSON](https://marketplace.visualstudio.com/items?itemName=mohsen1.prettify-json)** Assists with indentation of json files.

## Reading metadata
- json files are in theory human readable (and are a little more readable using the [json](https://marketplace.visualstudio.com/items?itemName=Meezilla.json) exetension listed above.)
- json files are also computer (programming) readable. The [json](https://docs.python.org/3/library/json.html) library in Python allows for working with json files. The script "summarise_studies.ipynb" in this folder is a Python notebook script to scrape the metadata files in this folder and output this README.md file with a top level summary of the studies.

## List of studies

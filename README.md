## TETRATEAM
This project is created in order to implememnt a data product using descriptive analytics to provide information about exceptional events or anormal behavior that may affect significantly the amount of money that the store must invest when buying credit to the "ABC" company.
 
This repository is for monitoring the project and sensitive data will not be uploaded to it.

The objectives are:
* **Identification of unusual sales spikes** 
* **Detection of seasonal outliers**
* **Detection of unforeseen events**
* **Discovery of store-specific outliers** 

### Solution strategy

.. image:: https://www.researchgate.net/publication/332001318/figure/fig5/AS:962182305050646@1606413546639/Java-Android-application-UML-of-big-data-frameworks-for-strengthening-of-the-security.png
   :width: 1050
   :alt: Java Android application UML of big data frameworks
   :align: center

---
## Installation procedure

##### 1. Download the project
You can download the project as a zip file using the download botton at the beginning. Additionally, you can clone the project with git using the url of it.

##### 2. Download rye
Follow the steps of the [guide](https://rye-up.com/guide/installation/)
remember to add it to the path

##### 3. Install the dependencies
Using the cmd locate the folder the project is and type the next command:
```
rye sync
```
it will strat to install all the dependencies in the .toml file.

Finally you can start the project typing:
```
rye run dev
```
## TETRATEAM
This project is created in order to implememnt a data product using descriptive analytics to provide information about exceptional events or anormal behavior that may affect significantly the amount of money that the store must invest when buying credit to the "ABC" company.
 
This repository is for monitoring the project and sensitive data will not be uploaded to it.

The objectives are:
* **Identification of unusual sales spikes** 
* **Detection of seasonal outliers**
* **Detection of unforeseen events**
* **Discovery of store-specific outliers** 

### Solution strategy
<picture> <img src="https://i.ibb.co/R3yZPhN/Whats-App-Image-2023-08-17-at-8-36-16-PM.jpg" width = 500px></picture>

---
## Installation procedure

##### 1. Download the project
You can download the project as a zip file using the download button at the beginning. Additionally, you can clone the project with git using the project's url.

##### 2. Download rye
Follow the steps of the [guide](https://rye-up.com/guide/installation/)
remember to add it to the path

##### 3. Install the dependencies
Using the cmd locate the folder where the project is and type the next command:
```
rye sync
```
it will start to install all the dependencies in the .toml file.

Finally you can start the project typing:
```
rye run dev
```

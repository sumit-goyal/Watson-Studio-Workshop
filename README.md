# IBM Watson Studio hands on


It is easy to get started with Watson Studio. First of all, you need to login into [Watson Studio](https://eu-de.dataplatform.cloud.ibm.com). If you do not have a Watson Studio account use the [Account Setup](https://github.com/sumit-goyal/Watson-Studio-Workshop/wiki/Account-setup) guide to help you create one quickly.


# Create a Project
After logging in you will see the overview page which gives you information about your previous activity. It also gives you options to create a new project or search for data in the enterprise catalog.


![Watson Studio Landing page](./docs/images/Landing-Page-Tile.png?raw=true "Title")

1. Choose  `Create a project` ("Standard" is good).
2. On the New project screen, add a name and optional description for the project.

![New Project Page](./docs/images/new-project-form.png?raw=true "New Project Form")

3. Choose an existing object storage service instance or [create a new one](https://github.com/sumit-goyal/Watson-Studio-Workshop/wiki/Account-setup).
4. You can leave rest of the settings on default.
5. Click Create.

Your new project is created and you can start adding resources to it.

![New Project Created](./docs/images/new-project-created.png?raw=true "New Project Created")


# Create a Notebook

Download and unzip the [.zip file](https://github.com/sumit-goyal/Watson-Studio-Workshop/archive/master.zip). It has the Jupyter Notebooks and datasets that you need during the hands on session.

1. Select the `Assets` tab in the Project Menu
2. Click on the `+ Add to project` menu item and select `Notebook` to create a new notebook.

![New Project Page](./docs/images/add-to-project.png?raw=true "Title")

3. On the `New Notebook` page select the `From file` tab as you wil be creating a New Notebook from a file.

4. Browse the `.ipynb` file in the .zip folder you just downloaded.
The download .zip has two Notebooks.

* [Getting started with Notebooks.ipynb](https://github.com/sumit-goyal/Watson-Studio-Workshop/blob/master/notebooks/Getting%20started%20with%20Notebooks.ipynb) - Use this notebook to get started with using Jupyter Notebooks in Watson Studio.
* [Use Spark and Python to Predict Equipment Purchase.ipynb](https://github.com/sumit-goyal/Watson-Studio-Workshop/blob/master/notebooks/Use%20Spark%20and%20Python%20to%20Predict%20Equipment%20Purchase.ipynb) - Use this Notebook if you are familiar with Jupyter Notebooks and basic concepts of machine learning.

5. Select the runtime called `Default Python 3.5 XS (2 vCPU and 8 GB RAM)` from the dropdown on the right if you chose the first notebook (Getting started with Notebooks) and the runtime called `Default Spark Python 3.5 XS (Driver with 1 vCPU and 4 GB RAM, 2 executors with 1 vCPU and 4 GB RAM each)` for the second notebook as it requires an Apache Spark runtime.

![Select Runtime](./docs/images/Select-Runtime.png?raw=true "Title")

6. Click `Create Notebook` in the bottom right and your notebook will be created. You are all set to work with your notebook. The notebook has all the further instructions.


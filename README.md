# IBM Watson Studio hands on


It is easy to get started with Watson Studio. First of all, you need to login into [Watson Studio](https://eu-de.dataplatform.cloud.ibm.com). If you do not have a Watson Studio account use the [Account Setup](https://github.com/sumit-goyal/Watson-Studio-Workshop/wiki/Account-setup) guide to help you create one quickly.


# Create a Project
After logging in you will see the overview page which gives you information about your previous activity. It also gives you options to create a new project or search for data in the enterprise catalog.


![Watson Studio Landing page](./docs/images/ws-landing-page.png?raw=true "Title")

1. Choose  `Create a project` ("Standard" is good).
2. On the New project screen, add a name and optional description for the project.

![New Project Page](./docs/images/new-project-form.png?raw=true "New Project Form")

3. Choose an existing object storage service instance or [create a new one](https://github.com/sumit-goyal/Watson-Studio-Workshop/wiki/Account-setup).
4. You can leave rest of the settings on default.
5. Click Create.

Your new project is created and you can start adding resources to it.

![New Project Created](./docs/images/new-project-created.png?raw=true "New Project Created")

# Upload the dataset

No wonder the word "Data Science" starts with data. Now, we will upload a dataset to the project you just created. We will be usin the dataset called 

# Refine the dataset

We will use the tool called Data Refinery in Watson Studio to refine our dataset.

# Create a Notebook

Download and unzip the [.zip file](https://github.com/sumit-goyal/Watson-Studio-Workshop/archive/master.zip). It has the Jupyter Notebooks and datasets that you need during the hands on session.

1. Select the `Assets` tab in the Project Menu
2. Click on the `+ Add to project` menu item and select `Notebook` to create a new notebook.

![New Project Page](./docs/images/add-to-project.png?raw=true "Title")

3. On the `New Notebook` page select the `From URL` tab as you wil be creating a New Notebook from a file.

4. Put the URL `https://github.com/sumit-goyal/Watson-Studio-Workshop/blob/master/notebooks/Part%201_%20Use%20Spark%20and%20Python%20to%20Predict%20Equipment%20.ipynb` in the field `Notebook URL` and enter a name for the notebook.

![Create Notebook](./docs/images/new-notebook-from-url.png?raw=true "Title")

5. Select the runtime `Default Spark Python 3.6 XS (Driver with 1 vCPU and 4 GB RAM, 2 executors with 1 vCPU and 4 GB RAM each)` for the notebook as it requires an Apache Spark runtime.

![Select Runtime](./docs/images/select-runtime-spark.png?raw=true "Title")

6. Click `Create Notebook` in the bottom right and your notebook will be created. You are all set to work with your notebook. The notebook has all the further instructions.

# AutoAI (Optional)






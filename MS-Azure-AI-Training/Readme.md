# Course Context:

## Learning Objectives:

* Fundamentals of AI Concepts
* Fundamentals of Machine Learning
* Fundamentals of Azure AI services

## Fundamentals of AI Concepts:

### Common AI workloads:

<img width="872" height="338" alt="image" src="https://github.com/user-attachments/assets/015f7b2d-bbac-4864-95c1-e42912ed92b7" />

### Principles of Responsible AI:

<img width="791" height="334" alt="image" src="https://github.com/user-attachments/assets/ee266a9f-0821-42b0-b406-4b9472832f7d" />

### Types of Machine Learning:

<img width="742" height="338" alt="image" src="https://github.com/user-attachments/assets/ef7ac4ff-2e91-45bb-89df-061b2dd122d7" />

<img width="937" height="400" alt="image" src="https://github.com/user-attachments/assets/3f6655c6-0100-4652-afdb-af8f156666cc" />

<img width="890" height="413" alt="image" src="https://github.com/user-attachments/assets/0d808d20-7096-418e-8fe9-ef1ba5d7dfbb" />

<img width="638" height="299" alt="image" src="https://github.com/user-attachments/assets/27c9d64a-55a3-4c69-a76c-703eaa322f44" />

<img width="623" height="304" alt="image" src="https://github.com/user-attachments/assets/44372714-5a74-496d-8784-8d7246120ead" />

## Azure Machine Learning Service:

Azure Machine Learning (Azure ML) is a cloud-based platform for building, training, and deploying machine learning models. Below is a high-level overview of the main steps involved in a typical Azure ML workflow:

**1. Set Up Your Workspace:**

* Create an Azure ML workspace: This is the top-level resource for Azure ML.
* Create or link resources:
  * Compute instances (for development)
  * Compute clusters (for training)
  * Storage account
  * Container registry (optional)

**2. Data Preparation:**

* Connect to data: Use Azure Blob Storage, Azure SQL, Data Lake, etc.
* Upload data: To the Azure ML datastore if it's local.
* Explore & clean data:
  * Use notebooks or Azure ML Designer.
  * Use pandas, PySpark, or built-in data profiling tools.

**3. Develop and Train Model:**

**Option A:** Code-first (Python SDK or CLI)

* Create a script for training (e.g., train.py).
* Define an experiment and submit the run.
* Use MLflow to track experiments.

**Option B:** Low-code (Designer)

* Drag-and-drop components (data input, transformations, models, evaluations).
* Train using UI pipelines.

**4. Model Evaluation and Tuning:**

* Evaluate metrics (accuracy, precision, recall, etc.).
* Hyperparameter tuning (via HyperDrive or AutoML).
* Visualize results in the Azure ML portal.

**5. Register the Model:**

* After a successful run, register the trained model in the workspace.
* Use model = run.register_model() in SDK.

**6. Deploy the Model:**

* Choose compute target:
  * ACI (Azure Container Instances) for testing/dev
  * AKS (Azure Kubernetes Service) for production
* Create an inference script (e.g., score.py)
* Define environment (conda/pip dependencies)
* Deploy as a real-time or batch endpoint

**7. Consume the Model:**

* Call the deployed endpoint using REST API.
* Integrate with apps (e.g., Power BI, web apps).

**8. Monitor and Manage:**

* **Monitor:** Inference latency, failure rate, drift detection.
* **Manage versions:** Models, datasets, pipelines.
* **Audit and governance:** Track lineage and access control.

### AI services in Microsoft Azure: 

<img width="620" height="168" alt="image" src="https://github.com/user-attachments/assets/8e81ab09-2551-4f41-be98-7e4b8ab49c62" />

### Azure AI Services:

<img width="609" height="234" alt="image" src="https://github.com/user-attachments/assets/b2af4b71-370d-448f-b79b-323e22fe5610" />

<img width="891" height="334" alt="image" src="https://github.com/user-attachments/assets/01ac9c53-7523-4b77-b5f7-36f5c2064804" />


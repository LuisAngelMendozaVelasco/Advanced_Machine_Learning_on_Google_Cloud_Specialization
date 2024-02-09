# AI Platform Notebooks

Besides BigQuery, the other piece of technology you will use in the first lab is AI Platform Notebooks. AI Platform Notebooks is the next generation of hosted notebook on GCP, and has replaced Cloud Datalab. This is a managed Jupyter notebook environment that you can use to run Python code. It handles authentication to GCP, so that you can easily access BigQuery. 

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/qP0TKaS-Eemn4xL11vEQ3A_b708a3fd9166a17c09bab5b168a178e7_Screen-Shot-2019-07-12-at-9.02.49-AM.png?expiry=1707609600000&hmac=rKMJbsPKdBBAFYwtnZvB2bIYv5hvaCBCzriPCQcimdk)

AI Platform Notebooks are developed in an iterative collaborative process. You can write code in Python, hit the run button, and the output shows up right on the page itself. Along with the code, you can write commentary in Markdown format and share the notebook with your colleagues. 

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/OKt0WqS_EemW8A5odpwTWA_6385bd2483273f5d620bc922895d7bd5_Screen-Shot-2019-07-12-at-9.07.42-AM.png?expiry=1707609600000&hmac=_bi5GX7tn0ZOp3RVYFhVIJmAJwnD54QrwgGUD6l5ZAo)

This is what the interface looks like. Notice how there are code sections interleaved with markup and output. This interleaving is what makes this style of computing so useful. Data analysis and machine learning are commonly carried out in notebooks like this.  The code is in the blue section. You can execute the code by either clicking the Run button or by pressing Shift + Enter. The red section displays output from the command. Notice that the output here isn’t just command line output; it’s charts and tables as well. The yellow section contains markup, so you can explain why you’re doing what you’re doing in plain-text.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/xFEelaS_EemLSgpXQLYWKg_ee2255569c5eda592edd09fcfc2b7d5d_Screen-Shot-2019-07-12-at-9.10.41-AM.png?expiry=1707609600000&hmac=fNeYFYrpAHjCkpdtRyKew-idujEDsZic6ua15AvFZFc)

AI Platform Notebooks work with the same technologies that you’re comfortable with, so you can start developing now, and then work on scale later. For example, we’ll be doing an exercise where we read from a .csv file. You could then process in Pandas and Apache Beam before training a model in TensorFlow, and then improve the model through training.

Eventually though, when you are ready to scale, you can use Google Cloud Storage to hold your data initially, process it in Cloud Dataflow on an ephemeral cluster, and then run distributed training and hyper-parameter optimization in Cloud AI Platform. 
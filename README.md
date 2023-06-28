# Quantium GenAI Hackathon

This repo contains resources for participants of the Quantium GenAI Hackacthon

## Summary 

Peer into the future of business solutions on the cloud! 

This is an opportunity to experiment with Generative AI on Google Cloud, and build new solutions to real business problems.

Below are the links to your team's project:

- [AI Artisans](https://console.cloud.google.com/home/dashboard?project=ai-artisans-lui5ep)
- [AI Billionaires](https://console.cloud.google.com/home/dashboard?project=ai-billionaires-1hpilb)
- [Artificial Appetite](https://console.cloud.google.com/home/dashboard?project=artificial-appetite-2zny4y)
- [Automating My Job Away](https://console.cloud.google.com/home/dashboard?project=automating-my-job-away-op4aoo)
- [Bing Chillin](https://console.cloud.google.com/home/dashboard?project=bing-chillin-o81m8v)
- [Chat PNC](https://console.cloud.google.com/home/dashboard?project=chat-pnc-rpms7t)
- [Checkout Max Ultra Pro](https://console.cloud.google.com/home/dashboard?project=checkout-max-ultra-pro-16xmw0)
- [Classy Tendies](https://console.cloud.google.com/home/dashboard?project=classy-tendies-l02wp3)
- [CWC](https://console.cloud.google.com/home/dashboard?project=cwc-fsvzhn)
- [Data Dreamers](https://console.cloud.google.com/home/dashboard?project=data-dreamers-1ejypr)
- [eNGS](https://console.cloud.google.com/home/dashboard?project=engs-sv83is)
- [FatGPT](https://console.cloud.google.com/home/dashboard?project=fat-gpt-s4rvy2)
- [GENius and Inspiring](https://console.cloud.google.com/home/dashboard?project=genius-and-inspiring-a209r3)
- [Grad Engineers and Eric](https://console.cloud.google.com/home/dashboard?project=grad-engineers-and-eric-zz6zih)
- [HackAIholics](https://console.cloud.google.com/home/dashboard?project=hack-ai-holics-uoh83p)
- [KISS AI](https://console.cloud.google.com/home/dashboard?project=kiss-ai-obec7a)
- [LINNAEAN](https://console.cloud.google.com/home/dashboard?project=linnaean-nlnh4q)
- [Maui](https://console.cloud.google.com/home/dashboard?project=maui-ame4zo)
- [New Chicago](https://console.cloud.google.com/home/dashboard?project=new-chicago-w6bq87)
- [PII AI](https://console.cloud.google.com/home/dashboard?project=pii-ai-6inigd)
- [Q-Smart](https://console.cloud.google.com/home/dashboard?project=q-smart-b5l0ti)
- [Rishy and the Dutty](https://console.cloud.google.com/home/dashboard?project=rishy-and-the-dutts-mu80km)
- [SASQUAD](https://console.cloud.google.com/home/dashboard?project=sasquad-t5mdly)
- [S.M.A.R.T](https://console.cloud.google.com/home/dashboard?project=smart-oxapj5)
- [Team Hamburger](https://console.cloud.google.com/home/dashboard?project=team-cheeseburger-xqeh6i)
- [The Q RedWinery](https://console.cloud.google.com/home/dashboard?project=the-q-red-winery-07eyc2)
- [Walnuts](https://console.cloud.google.com/home/dashboard?project=walnuts-y10usz)
- [wiq.SAGA](https://console.cloud.google.com/home/dashboard?project=wiq-saga-90qv8n)
- [wiq.Trends](https://console.cloud.google.com/home/dashboard?project=wiq-trends-0423zp)

## Your Project

Each team recieves a dedicated Google Cloud project `<team-name-random-suffix>`, with the Project Owner permission.

By default, the following servers/APIs are enabled:

- "aiplatform.googleapis.com"
- "artifactregistry.googleapis.com"
- "bigquery.googleapis.com"
- "compute.googleapis.com"
- "cloudbuild.googleapis.com"
- "cloudfunctions.googleapis.com"
- "datacatalog.googleapis.com"
- "dataflow.googleapis.com"
- "datastudio.googleapis.com"
- "dlp.googleapis.com"
- "eventarc.googleapis.com"
- "logging.googleapis.com"
- "sourcerepo.googleapis.com"
- "run.googleapis.com"
- "pubsub.googleapis.com"
- "monitoring.googleapis.com"
- "notebooks.googleapis.com"
- "eventarcpublishing.googleapis.com"
- "storage.googleapis.com"

## gcloud CLI Guide

To run the following commands in your browser, open Cloud Shell through the Google Cloud Console.

- `gcloud init` will initialise, authorise and configure the gcloud CLI
- `gcloud auth login` withh authorise access to the gcloud CLI for your current account
- `gcloud config set project <PROJECT_ID>` will set the default project to work on

To run these commands locally, [install the gcloud CLI](https://cloud.google.com/sdk/docs/install).

### Vertex AI commands
You can manage your Vertex AI Entities through the gcloud CLI. For example:
- `gcloud ai operations describe 1234 --project=example --region=us-central1` will describe the operation `1234` from project `example` in the region `us-central1`
- `gcloud ai models upload --container-image-uri="gcr.io/example/my-image" --display-name=my-model --project=example --region=us-central1` will upload the model `my-image` under project `example` in the region `us-central1`

For a full list of Vertex AI commands, [see here](https://cloud.google.com/sdk/gcloud/reference/ai).

## Quotas

Each project has quotas to restrict your consumption of shared resources, including hardware, software and network components.

These quotas are measured **per region**. This means that your project could have 60 requests per minute in one region, and 60 requests per minute in another supported region. 


### Vertex AI Quotas
| Request Quota | Value |
|----|---|
| base_model:chat-bison requests per minute | 60 |
| base_model:code-bison, which includes codechat-bison, requests per minute | 15 |
| base_model:code-gecko requests per minute | 15 |
| base_model:text-bison requests per minute | 60 |
| base_model:textembedding-gecko requests per minute | 600 |
| Resource management requests* per minute | 600 |
| Job or long-running operation requests per minute | 60 |
| Online prediction requests per minute (public endpoints only) | 30,000 |
| Online prediction request throughput per minute | 1.5 GB |
| Online explanation requests per minute | 600 |
| Vertex AI Vizier requests per minute | 6,000 |
| Vertex AI Feature Store online serving requests per minute | 300,000 |
| Vertex ML Metadata requests per minute | 12,000 |


## Resources

Additional information and resources are available at the links below:

- [Introduction to Vertex AI](https://cloud.google.com/vertex-ai/docs/start/introduction-unified-platform)
- [Vertex AI Workbench Managed Notebooks (More secure)](https://cloud.google.com/vertex-ai/docs/workbench/managed/introduction)
- [Vertex AI Workbench User-Managed Notebooks (More configurable)](https://cloud.google.com/vertex-ai/docs/workbench/user-managed/introduction)
- [Vertex AI Jupyter Notebook tutorials](https://cloud.google.com/vertex-ai/docs/tutorials/jupyter-notebooks#vertex-ai-workbench)
- [Howto for JupyterLab Notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)
- [Vertex AI Quotas and Supported Regions](https://cloud.google.com/vertex-ai/docs/quotas#image)


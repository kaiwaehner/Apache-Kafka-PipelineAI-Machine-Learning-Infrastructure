# Machine Learning Infrastructure leveraging Apache Kafka Ecosystem, PipelineAI, Kubernetes and Docker

## Attention: This is not a finished implementation; just getting started with PipelineAI and making notes here right now. 

TODO
- planning
- demo
- step-by-step-guide

### INSTALL Pipeline CLI

I installed Pipeline CLI successfully on my Mac in a new conda environment as described here:
https://github.com/PipelineAI/pipeline/tree/master/docs/quickstart/community

Here are my steps:

python => Shows: Python 3.7.0 (default, Jun 28 2018, 07:39:16)
conda create -n PipelineAI
conda create -n PipelineAI
conda install -n PipelineAI pip
which pip => Shows: /Users/kai.waehner/anaconda2/envs/PipelineAI/bin/pip
pip install cli-pipeline==1.5.207 --default-timeout=120 --ignore-installed --no-cache --upgrade

=> This successfully installs cli-pipeline.

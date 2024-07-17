# About this repo
All the things related to hackaton about aptomers and protein interaction (notebooks, scripts and event small datasets)

# Workflow

1) Pull this repo before you start some work and push it, when you have done something
2) Attach meaningful messages to your commits, give your notebooks and other files clear names 
2) Branch, if you modified something, that other person also modified
3) Before uploading the notebook, please, restart it and run all the cells to make sure, that all is ok
4) Notebooks should be well formatted: structure it with headings in Markdown and briefly explain what is going on

### Proposed notebook structure
- Imports and set up
- Get the data (read file into df, make API requests etc)
- Prepare the data (clean etc)
- `Do something meaningful`
- `Do something else`
- Save the results (export some data if needed, save important figs etc)

However, this is optional, and you can adapt this structure to your needs.

### Paths

In many  notebooks there are some path constants, which should be changed to run the notebook, because  you can store data in different places. Please, create such constants and add them to the beginning of your notebook into `Imports ant set up` section (like `HTML_PATH`). Also, save things like seeds etc into constants for reproducability.

### Environment

We use conda to manage environments. To reproduce it, use `env.yml` file.

# Data

Data MAY BE stored here, but not large files (> 100 Mb). If you place some large files in this folder locally, please, add it to `.gitignore`.

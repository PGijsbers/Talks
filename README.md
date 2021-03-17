# Talks
Repository with my talks:

 - ODSC 2021, Tutorial on Automated Machine Learning
 - ECML-PKDD 2020 (to be added)
 - ODSC 2019 Europe, Tutorial on Automated Machine Learning
 
## Instructions
Some talks are based on notebooks.
You look at the pre-rendered html files (in the talk's `rendered` folder), or run the notebooks yourself.
I highly encourage you to run the notebook and experiment with code changes to learn more about the topics discussed.

With Python installed it's encouraged to first make a virtual environment in the talk directory (if you installed conda, see [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html))

```bash
python -m venv venv/
```

activate the environment

```bash
source venv/bin/activate  # unix
venv\Scripts\activate     # Windows
```

You can then install the requirements and run the notebook

```
pip install -r requirements.txt
jupyter notebook
```

This will open your browser from on the notebook page, and you can open the notebook you wish to run.

-----
For practical purposes I might add files to this repository that were not made or presented by me (e.g. joint presentations).
A folder's README will specify which files, if any, were not created by me.

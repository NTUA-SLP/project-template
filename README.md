# project-template
Template repo for the term project in patreco2


# Prerequisites

* Working version of Python 3.8.* on your system
* Working version of pip on your system


# Repo structure

```
├── cache  # Store cache files (e.g. for embeddings) here. # DO NOT COMMIT CACHE FILES TO GIT
├── config  # Store configuration files here
├── data  # Download your datasets here. DO NOT COMMIT DATA TO GIT
├── experiments  # Store logs, checkpoints etc. here. DO NOT COMMIT CHECKPOINTS / LOGS TO GIT
├── package_name_rename_this_to_the_name_of_your_project  # Your (reusable) source code goes here
└── scripts  # Top-level scripts (e.g. train.py, test.py etc.) go here
```

# Repo setup

* Rename the folder `package_name_rename_this_to_the_name_of_your_project` to the name of your
project.

* Edit `pyproject.toml`. Change the `name` entry to the package name you've given to your project
  and the `authors` entry to a list with the `Name <email>` format of all the team members


You need to install poetry for the dependency management

```
pip install poetry  # or sudo pip3 install poetry if you use the system python
```


Then run

```
poetry install
```

To create a clean virtual environment with all the major dependencies


**Attention**: Do not change the package versions in `pyproject.toml` except there is a really good
reason for it. If you do first communicate with your TA.

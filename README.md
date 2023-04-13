# Automated-Tests

This directory contains an example of how to perform automated unit tests using pytest library and GitHub Actions.

Read with attention the files descriptions.

Unit_tests.ipynb: This is the Colab notebook used to create the scripts initially.

tests.py: Is the Python script that contains the unit tests.

requirements.txt: Contains the libraries that need to be installed when the action is triggered.

.github/workflows: This is the folder where the GitHub action is stored. Inside the workflows directory, main.yml file is stored. 

main.yml: This file is responsible for defining the action that must be executed. In this example everytime some user makes a push request to the application, tests.py will be executed.


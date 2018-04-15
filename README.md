# Data Analyst Nanodegree - Project 4

##Analyze A/B Test Results
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these.

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

The data and the Jupyter Notebook, which are all of the files you need to complete the project, are provided for you. Note that portions of the notebook reference back to quizzes that are linked in this lesson to ensure you are on the right track.

Although the quizzes in this lesson are not necessary to successfully complete the project (though they are helpful), all of the items on the [Project Rubric](https://review.udacity.com/#!/rubrics/1214/view) must meet specifications to successfully complete the project.

## Setup

Various setups are possible to reproduce, these notes assume minimal setup done prior.

1. Download and install [Anaconda](https://www.continuum.io/downloads), if necessary.
2. Switch to the project directory.
3. Use the [environment.yml](environment.yml) file in this directory to create an Anaconda environment called dand-project4
\
```bash
  conda env create -f environment.yml
```
\
4. Activate that environment with the following command 
```bash
  conda activate dand-project4
```
\
5. Start the notebook by issuing this command
```bash
  jupyter notebook Analyze_ab_test_results_notebook.ipynb	
```

This should open the notebook and allow you to start the analysis.  The terminal window where you start the notebook will remain running as you manipulate the notebook a browser.  To stop the notebook, hit `Control-C`.   To deactive the Anaconda environment after stoping the notebook, use this command
```bash
  conda deactivate
```

Once the environment has be setup, you can restart the analysis by beginning at step 4. (`source activate dand-project4`), above.


# PROJECT NAME

## Background
 Project Ramen (I just had ramen) aims to improve instant ramen by using data science to figure
- the optimal acceptable toppings needed
- to make ramen more environmentally sustainable
- make ramen a more nutritionally viable staple

## Table of Contents
- [Team Members](#team-members)
- [Skills](#skills)
- [Deliverables](#deliverables)
- [Data](#data)
- [Project Phases](#phases)

## Team Members
- Minh Mai
  - Core Volunteer, Instant Ramen Enthusiast
  - [minh5](http://github.com/minh5)
  - Knows the API, useful for answer questions about datasets, and giving recommendations on where to eat ramen

## Skills
Mostly the data science Python stack: familiarity with Pandas and Numpy. Also any webscraping and working with APIs will work as well. For one deliverable, we will need someone with the ability to write clearly.

## Deliverables
The main deliverables for this project are:
- Identify alternatives in sourcing ingredients for ramen
  - Led by Minh
  - Ideally build a recommendation system to recommend alternatives to current ingredients used
  - Skills needed: Python, particularly frameworks such as PyTorch, Tensorflow, and Keras
  - Link to github branch
- Document attentional toppings people put on ramen
  - Led by Minh
  - This is used to create a dataset of toppings people put on ramen for later analysis
  - Skills needed: clear writing skills, ability to query the API, and parse data from text
  - Beginner friendly
  - link to github branch

## Data
#### Access
The Ramen Research Dataset (RRD) is a collection of CSVs or JSON, depending on how the end user access them. The data can be accessed through the Ramen Research API or through static files on S3. In order to access the API, you will need to generate an access token [here](fakelink.com).

The data in S3 is partition by day with the following directory structure: `s3://ramen-research/data/<model>/<year>/<month>/<day>/`.

The `model` in the S3 url path correspond to the appropriate data model when making a request to the API. For more information, please refer to the [documentation](iamreallyhungry.com).

#### Configuration
After retrieving the data, it is important to set up the development environment for reproducible analysis. Before diving into the data, please make sure you configure the following:
- a Python3+ virtualenv, if you are unsure what this means, please refer to [virtualenv](virtualenv-pip-lib.com)
- install the Python management system, [pip](pip.com)
- install the following Python libraries by running `pip install -r requirements.txt -c constraints.txt`
- For deliverable 1: please make sure you do ....

### Datasets
The dataset used depend on the corresponding data model available, for the purpose of this project we only used the Ingredients, Sourcing, and Consumption data models.
- Ingredients data set contains information regarding the ingredients used in ramen production
  - columns: col1, col2, ...., etc.
  - This data set is used to produce the following deliverable:
    -  Deliverable 1
    -  Deliverable 2
    -  ....

## Phases
Phases usually follow this lifecycle. It may vary from project to project but the general phases
- [Research and Design](#research-and-design)
- [Testing and Implementation](#testing-and-implementation)
- [Feedback and Wrap-up](#feedback-and-wrap-up)

### Research and Design
TODO

### Testing and Implementation
TODO

### Feedback and Wrap-up
TODO

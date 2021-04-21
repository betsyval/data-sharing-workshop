---
title: Practical application
teaching: 10
exercises: 180
questions: []
objectives:
  - Implement what we've learned into our own workflow.
keypoints: []
day: 1
order: 225000
missingDependencies: []
dependencies: []
originalRepository: mjaquiery/jspsych-born-open-data
summary: We have a large block of time dedicated to implementing born open data
  saving into your own project. The instructors and helpers will be around to
  answer questions and help with any issues you run into.

---
## Putting it to Use

The goal of today is to leave with a workflow which implements born open data in your own workflow, and with an understanding of how to implement this into your other projects as they are developed. In order to do this, spend a few minutes thinking about your workflow and which phase of it can benefit from the use of OSF. 

For this session, you'll need a project of your own - perhaps one of:
* A copy of a recent project where you've already collected data
* A project currently under development

You'll work at your own pace, with support from your peers and the workshop instructors and helpers to implement a born open workflow in your project.
There are some points below for reference:

### Creating an OSF Project and Component

* Use [https://osf.io/](https://osf.io/) and not the testing server!

* Make sure you have a dedicated component for the data
* Set the data storage region to `Germany - Frankfurt`
* You can set its license/visibility separately to the main project

* You can create a DOI so you can cite your data easily


* Separate public from private data!
    * Private data might be Prolific/MTurk participant IDs
    * Any free-text responses



### Data dictionary
* Variable
* (friendly) Name
* Type
* Description

* Save as `data_dictionary.csv` and upload to your data component storage

### Testing!

* Complete your experiment (or a trial version) and ensure the data upload successfully.
* Make sure you let the participant know if something goes wrong.

### Best practice

* Test saving data before you let participants begin the experiment.
* Include useful error messages when things go wrong so participants can help you debug errors.
* Give participants an alternate way of providing their data if you fail to upload automatically (e.g. output a text box with the CSV data they can copy+paste into an email to you)

* As a bonus: why not provide participants with a link to see their data on the OSF?


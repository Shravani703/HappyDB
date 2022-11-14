##My final Tableau dahsboard that explores what influences happiness:
https://public.tableau.com/app/profile/shravani.bheema/viz/WhatMakesPeopleHappy/Dashboard1

##About the dataset:
HappyDB is a corpus of 100,000+ crowd-sourced happy moments. The goal of the corpus is to advance the state of the art of understanding the causes of happiness that can be gleaned from text. Please see also our [web site](http://rebrand.ly/happydb)


## Data Collection

We conducted a large scale collection of happy moments over 3 months on Amazon Mechanical Turk (MTurk.) For every task, we asked the MTurk workers to describe 3 happy moments in the past 24 hours (or past 3 months.)

Here are the instructions of the data collection task.

```
What made you happy today?  Reflect on the past {24 hours|3 months}, and recall three actual events 
that happened to you that made you happy.  Write down your happy moment in a complete sentence.
Write three such moments.

Examples of happy moments we are NOT looking for (e.g events in distant past, partial sentence):
    - The day I married my spouse
    - My Dog
```


## HappyDB Statistics

Basic statistics of HappyDB are shown in the table.


| Collection period | 3/28/2017 - 6/16/2017 |
| ------------- | ------------- |
| # happy moments | 100,922 |
| # distinct users | 10,843 |
| # distinct words | 38,188 |
| Avg. # happy moments / user | 9.31 |
| Avg. # words / happy moment | 19.66 |


## How to Download

You can download the dataset by using `git` command or simply downloading the file from the repository.

```
$ git clone <git-repository-path>
```

## Directory Structure

After you clone or download the repository, you will see the following file structure.

```
happydb
└── data
    ├── cleaned_hm.csv
    ├── demographic.csv
    ├── original_hm.csv
    ├── senselabel.csv
    ├── topic_dict
    │   ├── entertainment-dict.csv
    │   ├── exercise-dict.csv
    │   ├── family-dict.csv
    │   ├── food-dict.csv
    │   ├── people-dict.csv
    │   ├── pets-dict.csv
    │   ├── school-dict.csv
    │   ├── shopping-dict.csv
    │   └── work-dict.csv
    └── vad.csv
```

HappyDB consists of a set of CSV files. Here are schema descriptions of the files.

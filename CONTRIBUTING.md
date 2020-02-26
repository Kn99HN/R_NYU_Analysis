# Contributing

#### Table of Contents
- [Setup](#user-content-setup)
- [Development](#user-content-development)
- [Project Overview](#user-content-project-overview)
- [Issue](#user-content-issue)
- [Pull Request](#user-content-pull-request)

## Setup
You'll need to install a few applications to contribute to this project:

- Git
- Python3
- Anaconda/jupyterlab+notebook
- Reddit API key

### Using Anaconda
[Install Intellij from the website][anaconda-download]
[anaconda-download]: https://www.anaconda.com/distribution/

<!-- @HelpWanted Add command line installation instructions for more OSes -->
### Command Line

Installing jupyterlab
```
pip install jupyterlab
```
Then install notebook
```
pip install notebook
```
Then run
```
jupyter notebook
```

### API key
- Register for an API key on [Reddit][reddit-api].
- Create a new file `key.json` to store the API key. Change the name when reading from the key.json file as appropriate

[reddit-api]: https://www.reddit.com/wiki/api

## Project Overview
The following ASCII file structure diagram shows the most important packages and files, with comments.
``` bash
.
├── CONTRIBUTING.md
├── README.md
├── datasets            // datasets of nyu subreddit stored in SQlite database
│   └── R_NYU.db
├── index.html          // final overview of the project
├── key.json            // key.json stores the reddit API key
└── notebooks
    ├── Analysis.ipynb //All analysis of the data is in here
    ├── FinalNotebook.ipynb //Final notebooks
    └── Setting\ Up.ipynb //Setting up to scrape, query and parse data
```

## Development

### Repository
- Fork this repository by clicking `fork` on the right side.
- Choose where you want to save the project locally on your computer then run `git clone [Your URL/Git here]`.
- We recommend to develop your feature through another branch other than the `master` branch.
So, run `git checkout -b [name of your branch here]` and develop the feature. You can switch between
branches by the same command by removing `-b`.
- Once you finish, you can run the normal `git add`, `git commit` & `git push`.
- Make a [PR](#user-content-pull-request) when the feature is fully finished or if you would like
feedback on your changes.

## Issue
Remember to include enough information if you're reporting a bug.
Asking question through an issue is totally fine as well.

## Pull Request
It would be best to develop your feature with a new branch other than master.
Every PR will be considered.

### Before Creating a PR
- Making sure that the code compiles and
test your code.

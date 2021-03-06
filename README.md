# niso-workshop-2017
MkDocs site with ORCID API materials for [NISO Training Program: Working with Scholarly Information Resource RESTful APIs (Fall 2017)](http://www.niso.org/news/events/2017/working_scholarly_restful_apis/)

# Running the MkDocs site locally
## Pre-requisites
* [Python](https://www.python.org) 2.6 or higher
* [pip](http://pip.readthedocs.io/en/stable/installing/)
* [MkDocs](http://www.mkdocs.org/#installation)

## Start development environment
1. Clone project

        cd ~/git
        git clone git@github.com:ORCID/niso-workshop-2017.git
  
2. Start local server

        cd niso-workshop-2017
        mkdocs serve

3. View local site at [http://127.0.0.1:8000](http://127.0.0.1:8000)
4. Add/edit pages per http://www.mkdocs.org/user-guide/writing-your-docs (mkdocs server will reload changes automatically)

## Deploy code to Github pages
Pushes code to gh-pages branch per http://www.mkdocs.org/user-guide/deploying-your-docs/#github-pages

1. cd to local project directory

        cd ~/git/niso-workshop-2017
  
2. Make sure you're on the master branch

        git checkout master

2. Deploy code to Github pages

        mkdocs gh-deploy

3. View live site at [https://orcid.github.io/niso-workshop-2017](https://orcid.github.io/niso-workshop-2017)

# Current Website In Charge

Teodora Baluta. If you mess up and push something that breaks the website, you must immediately inform Teodora. But first you should follow all the instructions below to ensure that you don't break things in the first place.

If you have trouble with new website, please feel free to find Jiong.

# Overview
- New Website v4.8, please refer to https://sourcethemes.com/academic/docs/ if you want to make more modifications.
- Now the website is built with Hugo v0.66 (*extended*). It's not compatible with latest v0.72.0-DEV due to changed API. The admin will update it once the Academic template supports higher stable version of Hugo.

# Instruction to install dependencies

Prerequisites:

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo](https://gohugo.io/getting-started/installing/#fetch-from-github)

Important: At present, the website is compatible with Hugo v0.66 (*extended*). Make sure you are using the correct version. It is recommended to [install from source](https://gohugo.io/getting-started/installing/#fetch-from-github). Using apt-get may install an older version.

1. Clone the repo: 

       git clone git@github.com:meelgroup/meelgroup-website.git
    
2. Initialize the theme:

       cd meelgroup-website
       git submodule update --init --recursive

3. View your new website on localhost:
      
       hugo server

    Now you can go to [localhost:1313](http://localhost:1313).
  

4. Remove the public folder

        rm -rf public

5. Commit and Push your changes to this repository

6. While running for the first time, do this
        

        git submodule add --force  -b master git@github.com:meelgroup/meelgroup.github.io.git public        

7. To deploy, run:
       
       
       chmod +x deploy.sh
       ./deploy.sh 
       
   If you have made changes and running the `deploy.sh` script still says that no changes were made, run the command in Point 6 again, and then run `./deploy.sh`.

# Instruction for adding Papers
- To add a new paper(*<name_of_paper>*). Create a directory *<name_of_paper>* in 'content\publication\' and then add index.md and cite.bib in this directory, similar to others. 
- Here is an example: themes\academic\exampleSite\content\publication\conference-paper.

# Instruction for adding your photos
- Create a directory in `content\authors` and then add `_index.md` and your avatar in this directory, similar to others. 

# Instruction for adding Widgets
- To create widgets and their md file in `content/home`(For eg. see `people.md` that adds `people` widget.)
- You'll also need to change `config\_default\` to make any global configuration changes. If you have trouble, please find Jiong.

# What to do if you see strange errors in the News or Software section

These sections are not a part of the Academic theme by default and hence, any updates to the theme will not be reflected in these sections by default. This may break the website. To solve this, you must identify what changes have been made to other secions of the theme, and replicate them in corresponding files of the custom sections.

## NOTE:
- The *md* files also take plain html. So if you want, you can hack html to make small changes.

- Also when you run `deploy.sh`, the website rebuilds from the repo, 
**So you may want to confirm your changes before running the script. 
 Hence it's recommended that after making the changes you first run it on localhost using `hugo server`**

- Since the website rebuilds from the repo, never make changes directly to the [website](https://github.com/meelgroup/meelgroup.github.io), else they will be overwritten in the next build.

- In case you have pushed the wrong code, you can do a `git reset HEAD~1` , push back again and rerun the script to reach back to the initial state.


- If you're having trouble installing `hugo` and intend to make small changes only, you can also do the following:

       ```
       # Fork the repo https://github.com/meelgroup/meelgroup-website 
       git clone https://github.com/<your_name>/<your_website_name>
       cd <your_website_name>
       git checkout -b <new_branch>
       # Make whatever changes,  git add and commit
       # Now go to github and initiate a Pull-Request 
       # Now the Maintainer would accept the PR and merge it with the master 
       ```
        


For more documentation see [this](https://github.com/gcushen/hugo-academic).


- If there is a string including char ':' in your \*.md file, it should be surrounded by double-quotes ("). For example, if the title of your paper is `Manthan: A Data-Driven Approach for Boolean Function Synthesis.`, you need to write `"Manthan: A Data-Driven Approach for Boolean Function Synthesis."` in your \*.md file. Otherwise, the colon (:) will affect the parsing of \*.md file.


- If failing to build the website resulting from PNG checksum, you can fix it by editing and saving it as a new file. 


## Ecosystem

* **[Academic Admin](https://github.com/sourcethemes/academic-admin):** An admin tool to import publications from BibTeX or import assets for an offline site
* **[Academic Scripts](https://github.com/sourcethemes/academic-scripts):** Scripts to help migrate content to new versions of Academic

## License

Copyright 2017-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)

# Instruction to install dependencies

Prerequisites:

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo](https://gohugo.io/getting-started/installing/#quick-install)

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

# Instruction for adding Papers
- To add a new paper(*<name_of_paper>*). Add *<name_of_paper.md>* like other md files and for adding bib information add *<name_of_paper.bib>* in `static/files/citations/`.

# Instruction for adding Widgets
- To create widgets and their md file in `content/home`(For eg. see `people.md` that adds `people` widget.)
- You'll also need to change `config.toml` to make any global configuration changes.

# Instruction for adding your photos
- See `content/home/people.md`. 

- Add your name (if you happen to have a homepage you can link your name to that url) under appropriate group and `jpg/png` image in `/static/img/` directory. After that add html(see existing entries) with `src` changed to your image location.

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



## License

Copyright 2017 [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)

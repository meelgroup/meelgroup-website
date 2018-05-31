# Instruction to install dependencies

Prerequisites:

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo](https://gohugo.io/getting-started/installing/#quick-install)

1. Clone the repo: 

       `git clone https://github.com/meelgroup/meelgroup-website`
    
2. Initialize the theme:

       cd meelgroup-website
       git submodule update --init --recursive

3. View your new website on localhost:
      
       hugo server

    Now you can go to [localhost:1313](http://localhost:1313).
  
4. To deploy run:
       
       chmod +x deploy.sh
       ./deploy.sh 

# Instruction for adding Papers
- To add a new paper(say of name *<paper>*). Add *<paper.md>* like other md files and for adding bib information and *<paper.bib>* in `static/files/citations/`.

- To create widgets and their md file in `content/home`

- For more documentation see [this](https://github.com/gcushen/hugo-academic).

## License

Copyright 2017 [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)

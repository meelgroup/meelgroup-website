# Overview
- New Website v4.8, please refer to https://sourcethemes.com/academic/docs/ if you want to make more modifications.
- Now the website is built with Hugo v0.66 (*extended*). It's not compatible with latest v0.72.0-DEV due to changed API. The admin will update it once the Academic template supports higher stable version of Hugo.

# Instruction for adding Papers
- To add a new paper(*<name_of_paper>*). Create a directory *<name_of_paper>* in 'content\publication\' and then add index.md and cite.bib in this directory, similar to others. 
- Here is an example: themes\academic\exampleSite\content\publication\conference-paper.

# Instruction for adding your photos
- Create a directory in 'content\authors' and then add _index.md and your avatar in this directory, similar to others. 

# Notes
- If there is a string including char ':' in your \*.md file, it should be surrounded by double-quotes ("). For example, if the title of your paper is `Manthan: A Data-Driven Approach for Boolean Function Synthesis.`, you need to write `"Manthan: A Data-Driven Approach for Boolean Function Synthesis."` in your \*.md file. Otherwise, the colon (:) will affect the parsing of \*.md file.
- If failing to build the website resulting from PNG checksum, you can fix it by editing and saving it as a new file. 

## Ecosystem

* **[Academic Admin](https://github.com/sourcethemes/academic-admin):** An admin tool to import publications from BibTeX or import assets for an offline site
* **[Academic Scripts](https://github.com/sourcethemes/academic-scripts):** Scripts to help migrate content to new versions of Academic

## License

Copyright 2017-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)

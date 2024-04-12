+++
# A Projects section created with the Portfolio widget.
widget = "people"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 16  # Order that this section will appear.

title = "Software"
subtitle = "<br>"

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

| Name              					| Input             	 | Type                  			| Project Webpage						| Note      	|
|:---:                					|:---:                	 | :---:                   			|:---:								|:---:        	|
|[Arjun](https://github.com/meelgroup/arjun/)           | CNF                    | Preprocessor					| [Source](https://github.com/meelgroup/arjun/)			| Minimal independent set calculator and CNF minimizer|
|[ApproxMC](https://github.com/meelgroup/approxmc/)     | CNF                    | Approximate Counter				| [Source](https://github.com/meelgroup/approxmc/)		| Supports projected model counting |
|[ExactMC](https://github.com/meelgroup/KCBox)          | CNF                    | Exact Counter				| [Source](https://github.com/meelgroup/KCBox)			| Supports weighted model counting|
|[GANAK](https://github.com/meelgroup/ganak/)           | CNF                    | Exact Counter				| [Source](https://github.com/meelgroup/ganak/)			| Supports projected model counting|
|[PBCount](https://github.com/grab/pbcount)             | Pseudo-Boolean Formula | Exact Counter				| [Source](https://github.com/grab/pbcount)			| Supports weighted model counting|
|[ApproxMC-PB](https://github.com/meelgroup/approxmcpb/)| Pseudo-Boolean Formula | Approximate Counter				| [Source](https://github.com/meelgroup/approxmcpb/)		| Supports projected model counting|
|[sharpASP](https://github.com/meelgroup/sharpASP)      | Answer set program     | Exact Counter				| [Source](https://github.com/meelgroup/sharpASP)		| Exact count of the number of answer sets|
|[ApproxASP](https://github.com/meelgroup/ApproxASP2)   | Answer set program     | Approximate counter				| [Source](https://github.com/meelgroup/ApproxASP2)		| approximately counts the number of answer sets
|[pepin](https://github.com/meelgroup/pepin/)           | DNF                    | Approximate Counter				| [Source](https://github.com/meelgroup/pepin/)			| Supports weighted model counting|
|[Crane](https://github.com/dilkas/crane)               | First Order Formula    | Exact Counter				| [Source](https://github.com/dilkas/crane)			| Supports weighted model counting|
|[CSB](https://github.com/meelgroup/csb/)               | SMT (bit vector)       | Approximate Counter and Sampler		| [Source](https://github.com/meelgroup/csb/)			| Approximate counting, almost uniform and uniform-like smapling |
|[SkolemFC](https://github.com/meelgroup/skolemfc/)     | QBF                    | Approximate Counter				| [Source](https://github.com/meelgroup/skolemfc/)		|Counts number of Skolem functions|
|[AMUSIC](https://github.com/jar-ben/amusic)            | CNF                    | Approximate MUS Counter			| [Source](https://github.com/jar-ben/amusic)			|Counts minimal unsatisfiable subsets of CNF|
|[Weighted-to-unweighted](https://github.com/meelgroup/weighted-to-unweighted)   | Weighted CNF				  | Utility               | [Source](https://github.com/meelgroup/weighted-to-unweighted)      | Converts weighted CNF to unweighted CNF|
|[UniGen](https://github.com/meelgroup/unigen/)         | CNF                    | Almost Uniform sampler			| [Source](https://github.com/meelgroup/unigen/)		| Supports Projected Sampling |
|[CMSGen](https://github.com/meelgroup/cmsgen/)         | CNF                    | Uniform-like sampler				| [Source](https://github.com/meelgroup/cmsgen/)		| Supports Projected Sampling |
|[WAPS](https://github.com/meelgroup/waps)              | CNF                    | Exact Uniform sampler			| [Source](https://github.com/meelgroup/waps)			| Supports weighted and Projected Sampling |
|[INC](https://github.com/grab/inc-weighted-sampler)    | CNF                    | Incremental uniform sampler			| [Source](https://github.com/grab/inc-weighted-sampler)        | Supports weighted Sampling|
|[Manthan](https://github.com/meelgroup/manthan)        | QBF                    | Skolem Function Synthesizer			| [Source](https://github.com/meelgroup/manthan)		| Synthesize Skolem function given a specification |
|[Barbarik](https://github.com/meelgroup/barbarik)      | CNF Sampler            | Sampler Tester          			| [Source](https://github.com/meelgroup/barbarik)		| Supports weighted sampler testing |
|[Teq](https://github.com/meelgroup/teq)                | NNF                    | Probabilistic Circuit Closeness Tester       | [Source](https://github.com/meelgroup/teq)			| Tests whether two Probabilistic Circuits (in NNF) are close |

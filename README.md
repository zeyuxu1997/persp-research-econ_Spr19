# MACS 30250 - Perspectives on Computational Research in Economics (Spring 2019)

|  | [Dr. Richard Evans](https://sites.google.com/site/rickecon/) | TA: [Zunda (Winston) Xu](https://github.com/zundaxu) |
|--------------|--------------------------------------------------------------|----------------------------------------------------|
| Email | rwevans@uchicago.edu | zunda@uchicago.edu |
| Office | 208 McGiffert House |                    |
| Office Hours | M 3:00-5:00pm | TBA |
| GitHub | [rickecon](https://github.com/rickecon) | [zundaxu](https://github.com/zundaxu) |

* **Meeting day/time**: MW 1:30-2:50pm, Saieh Hall, Room 242
* **Lab day/time**: W 4:30p-5:30p, Saieh Hall, Room 247
* TA: Zunda Xu
* Office hours also available by appointment

## Course description

This course focuses on applying computational methods to conducting social scientific research in economics through a student-developed research project. Students will identify a research question of their own interest that involves a direct reference to economic theory, use of data, and a significant computational component. The students will collect data, develop, apply, and interpret statistical learning models, and generate a fully reproducible research paper. We will identify how computational methods can be used throughout the research process, from data collection and tidying, to exploration, visualization and modeling, to the final communication of results. The course will include modules on theoretical and practical considerations, including topics such as epistemological questions about research design, writing and critiquing papers, and additional computational tools for analysis.

## Grades

|     Assignment              | Points | Quantity | Total points | Percent |
|-----------------------------|--------|----------|--------------|---------|
| Proposal                    |    10  |      1   |        10    |   6.2%  |
| Literature review           |    15  |      1   |        15    |   9.4%  |
| Methods/initial results     |    15  |      1   |        15    |   9.4%  |
| Peer evaluations of posters |     2  |      5   |        10    |   6.2%  |
| Poster presentation         |    30  |      1   |        30    |  18.8%  |
| Final paper                 |    40  |      1   |        40    |  25.0%  |
| Problem sets                |    10  |      4   |        40    |  25.0%  |
| **Total Points**            |        |          |       160    | 100.0%  |

Students will turn assignments in via their own public GitHub fork of the main class repository (e.g., `https://github.com/YourGitHubHandle/persp-research-econ_Spr19`). The directory structure of this repository should be the following.

* `github.com/YourGithubHandle/persp-research-econ_Spr19/`
  * ProblemSets
    * PS1
    * PS2
    * PS3
    * PS4
  * Proposal
  * LitReview
  * MethodsResults
  * Poster
  * FinalPaper


## Late Problem Sets

Late problem sets will be penalized 2 points for every hour they are late. For example, if an assignment is due on Monday at 1:30pm, the following points will be deducted based on the time stamp of the last commit.

| Example PR last commit | points deducted |
| ---------------------- | --------------- |
| 1:31pm to 2:30pm       | -2 points       |
| 2:31pm to 3:30pm       | -4 points       |
| 3:31pm to 4:30pm       | -6 points       |
| 4:31pm to 5:30pm       | -8 points       |
| 5:31pm and beyond      | -10 points (no credit) |


## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.


## Course schedule

| Date | Day | Topic | Reading | Assignment |
|------|-----|-------|---------|------------|
| Apr  1 | M | Overview/reproducibility in science | [Slides](Slides/Reprod_slides.pdf) |  |
| Apr  3 | W | Abstract/intro/conclusion | [Slides](Slides/IntroAbsConcl_slides.pdf) |  |
| Apr  8 | M | Theory section of paper | [Slides](Slides/TheorySection_slides.pdf) |  |
| Apr 10 | W | Proposal presentations |  | [Proposal slides & present](https://github.com/UC-MACSS/persp-research-econ_Spr19/blob/master/Assignments/project-proposal.md) |
| Apr 15 | M | Data/methods section of paper | [Slides](Slides/DataSection_slides.pdf) |  |
| Apr 17 | W | Computational results section of paper | [Slides](Slides/ResultsSection_slides.pdf) |  |
| Apr 22 | M | Kernel density estimation | [Notebk](Notebooks/KDE/KDE.ipynb) | [PS1](Assignments/PS1/PS1.pdf) |
| Apr 24 | W | Parallel computing | [Notebk](Notebooks/Parallel/parallel.ipynb) |  |
| Apr 29 | M |  |  | [Literature review section](https://github.com/UC-MACSS/persp-research-econ_Spr19/blob/master/Assignments/lit-review.md) |
| May  1 | W | Parallel computing | [Dask Tutorial](https://github.com/dask/dask-tutorial) |  |
| May  6 | M | Workshop papers/office visits | [Schedule](https://github.com/UC-MACSS/persp-research-econ_Spr19/blob/master/OfficeVisits/README.md) |  |
| May  8 | W | Dynamic programming with interpolation | [Notebk](Notebooks/DynProgIntpl/DynProgIntpl.ipynb) | [PS2](Assignments/PS2/PS2.pdf) |
| May 13 | M | Dynamic programming with interpolation |  |  |
| May 15 | W | Overlapping generations models | Notes | PS3 |
| May 20 | M | Overlapping generations models |  |  |
| May 22 | W | Workshop papers/office visits |   | Methods/initial results section |
| May 27 | M | **No class (Memorial Day Holiday)** |  |  |
| May 29 | W | Effective presentations, poster,slides | Notes  |  |
| Jun  3 | M | Markov and hidden Markov models | Notes | PS 4 |
| Jun  5 | W | In-class poster presentations |  | Poster |
| Jun  9 | Su | Final papers due at 11:59pm |  | Papers due |


## References and Readings

* Miguel, E., C. Camerer, K. Casey, J. Cohen, K. M. Esterling, A. Gerber, R. Glennerster, D. P. Green, M. Humphreys, G. Imbens, D. Laitin, T. Madon, L. Nelson, B. A. Nosek, M. Petersen, R. Sedlmayr, J. P. Simmons, U. Simonsohn, and M. Van der Laan, "[Promoting Transparency in Social Science Research](http://science.sciencemag.org/content/343/6166/30)," *Science* (3 Jan. 2014).
* Casadevall, Arturo and Ferric C. Fang, "[Reproducible Science](https://iai.asm.org/content/78/12/4972)," *American Society for Microbiology: Infection and Immunity*, 78:12, pp. 4972-4975 (2010).
* Christensen, Garret S. and Edward Miguel, "[Transparency, Reproducibility, and the Credibility of Economics Research](https://www.aeaweb.org/articles?id=10.1257/jel.20171350)," *Journal of Economic Literature*, 56:3 pp. 920-980 (Sep. 2018).
* Ince, Darrel C., Leslie Hatton, and John Graham-Cumming, "[The Case for Open Computer Programs](https://www.nature.com/articles/nature10836)," *Nature*, 482, pp. 485-488 (23 Feb. 2012).
* Niemeyer, Kyle, "[*Nature* Editorial: If you want reproducible science, the software needs to be open source](https://arstechnica.com/science/2012/02/science-code-should-be-open-source-according-to-editorial/)," *Ars Technica* (26 Feb. 2012).



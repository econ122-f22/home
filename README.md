Course schedule for ECON 122 (F22)
================

Michael Gelman (<mgelman@cmc.edu>), Claremont McKenna College

Office hours:

- In person: Mo/We 1:00-2:00 PM Bauer 216
- Virtual: Sign up [here](https://calendly.com/michael-gelman) 

Tutor sessions (BC 22):

- **Mo 06:00-08:00 PM** - Oleksandr (Alex) Horban 
- **Th 08:00-10:00 PM** - William DeForest 

Textbook 1: [Modern Data Science with R](https://mdsr-book.github.io/) (1st edition)  
Textbook 2: [An Introduction to Statistical Learning](https://link.springer.com/book/10.1007/978-1-4614-7138-7)

-   [Syllabus](ECON122_F2022_DataScience_StatisticalLearning.pdf)
-   [GitHub reference quick guide](https://github.com/econ122-f22/github-classroom-for-stduents)
-   [GitHub reference full guide ](https://happygitwithr.com/index.html)
-   Additional free resource: [R for Data Science](http://r4ds.had.co.nz/)

------------------------------------------------------------------------
### Assignments due

- [Test assignment](https://classroom.github.com/a/CQuhTy99) (due **09/02**) 
- [Problem Set 1](https://classroom.github.com/a/xSowMRmz) (due **09/12**)
  - Solutions [.Rmd](PS/PS1-solution.Rmd) [.md](PS/PS1-solution.md)
- [Problem Set 2](https://classroom.github.com/a/HzJQu66N) (due **09/23**)
  - Solutions [.Rmd](PS/PS2-solution.Rmd) [.md](PS/PS2-solution.md)
- [Team Project 1](https://classroom.github.com/a/EtptlYnq) (due **09/27**)
- [Problem Set 3](https://classroom.github.com/a/0uDT9Ba8) (due **10/04**)
- [Problem Set 4](https://classroom.github.com/a/Uzal8iu4) (due **10/10**)
------------------------------------------------------------------------

### Week 1 (08/29)

**Monday** (intro, GitHub, test assignment) 

-   before class:
    - Try to set up R, RStudio, Git, GitHub account (See [GitHub reference quick guide](https://github.com/econ122-f22/github-classroom-for-students) and See [GitHub reference full guide](https://happygitwithr.com/index.html))
-   in class: 
    -   day 1 slides: [.Rmd](docs/day1_IntroSlides.Rmd) [.html](https://econ122-f22.github.io/home/day1_IntroSlides.html)
    -   continue setting up software
    -   [test assignment](https://classroom.github.com/a/CQuhTy99)

**Wednesday** (reproducibility, R Markdown)

-   before class:
    -   complete test assignment and push **both** .rmd and .md files to GitHub.
    -   read MDSR Chapter 1 and Appendix D
    -   Start looking at PS 1
-   in class: 
    -   day 2 slides: [.Rmd](docs/day2_RMarkdownSlides.Rmd) [.html](https://econ122-f22.github.io/home/day2_RMarkdownSlides.html)
    -   day 2 activity: [.Rmd](activities/day2_MarkdownActivity.Rmd) [.md](activities/day2_MarkdownActivity.md)
    
------------------------------------------------------------------------

### Week 2 (09/05)

**Monday** 

- Labor day!!

**Wednesday** (R objects, R functions)

-   before class:
    -   read MDSR Appendix sections B.4, B.5 and C.2
    -   read Grolemund/Wickham sections [20.2 Vector Basics](http://r4ds.had.co.nz/vectors.html#vector-basics), [20.3 Types of Vectors (focus on logical, numeric)](http://r4ds.had.co.nz/vectors.html#important-types-of-atomic-vector), and [20.5 Lists](http://r4ds.had.co.nz/vectors.html#lists)
    -   Reminder: PS 1 due on Monday
-   in class: 
    -   day 3 slides [.Rmd](docs/day3_RObjectsSlides.Rmd) [.html](https://econ122-f22.github.io/home/day3_RObjectsSlides.html)
    -   day 3 activity: [.Rmd](activities/day3_RObjectsActivity.Rmd) [.md](activities/day3_RObjectsActivity.md)
        -  solutions: [.Rmd](activities/solutions/day3_RObjectsActivity_Solution.Rmd) [.md](activities/solutions/day3_RObjectsActivity_Solution.md)

------------------------------------------------------------------------

### Week 3 (09/12)

**Monday** (`ggplot2` graphics)

-   before class:
    -   read MDSR sections 3.1 and 3.2. Section 3.3 contains some `dplyr` work that I will save for discussion in chapter 4.
    -   read Grolemund/Wickham [sections 3.1 - 3.5](http://r4ds.had.co.nz/data-visualisation.html)    
-   in class: 
    -   day 4 slides: [.Rmd](docs/day4_ggplotSlides.Rmd) [.html](https://econ122-f22.github.io/home/day4_ggplotSlides.html)
    -   day 4 activity: [.Rmd](activities/day4_ggplotActivity.Rmd) [.md](activities/day4_ggplotActivity.md)
        -  solutions: [.Rmd](activities/solutions/day4_ggplotActivity_solution.Rmd) [.md](activities/solutions/day4_ggplotActivity_solution.md)

**Wednesday** (more `ggplot2` and interactive graphics)

-   before class:
    -   little more ggplot: read Grolemund/Wickham [sections 3.6 - 3.10](http://r4ds.had.co.nz/data-visualisation.html)
    -   just read pages 324-325 in MDSR to get a feel for map projections. For now we will just be working with simple maps that only need lat/long and build-in map boundaries.
    -   quick read MDSR sections 11.1-11.3 in chapter 11 to get a "big picture" idea of some of the interactive graphing options in R.
    -   Start on PS 2 
-   in class: 
    -   discuss group projects
    -   day 5 slides: [.Rmd](docs/day5_moreggplotsSlides.Rmd) [.html](https://econ122-f22.github.io/home/day5_moreggplotsSlides.html)
    -   day 5 interactive graphics slides: [.Rmd](docs/day5_IntroInteractive.Rmd) 
    -   day 5 activity: [.Rmd](activities/day5_ggplotActivity_2.Rmd) [.md](activities/day5_ggplotActivity_2.md)
        -  solutions: [.Rmd](activities/solutions/day5_ggplotActivity_2_solution.Rmd) [.md](activities/solutions/day5_ggplotActivity_2_solution.md)

------------------------------------------------------------------------

### Week 4 (09/19)

**Monday** (Introduction to `dplyr`)

-   before class:
    -   read MDSR sections 4.1 and 4.2
-   in class: basic data wrangling with `dplyr`
    -   day 6 slides: [.Rmd](docs/day6_DataWrangling1Slides.Rmd) [.html](https://econ122-f22.github.io/home/day6_DataWrangling1Slides.html)
    -   day 6 activity: [.Rmd](activities/day6_DataWrangling1Activity.Rmd) [.md](activities/day6_DataWrangling1Activity.md)
        -  solutions: [.Rmd](activities/solutions/day6_DataWrangling1Activity_Solution.Rmd) [.md](activities/solutions/day6_DataWrangling1Activity_Solution.md)
        

**Wednesday** (Work on Team Project 1)

-   before class:
    -   Make sure you have your Team Project 1 partners
-   in class: 
    -   Work with partners on Team Project 1
    -   Ask any questions related to material up to this point

------------------------------------------------------------------------

### Week 5 (09/26)

**Monday** (Joins in `dplyr`)

-   before class:
    -   read MDSR section 4.3 and 4.4
    -   get started with PS 3
-   in class:
    -   day 7 slides: [.Rmd](docs/day7_DataWrangling2Slides.Rmd)  [.html](https://econ122-f22.github.io/home/day7_DataWrangling2Slides.html)
    -   day 7 activity: [.Rmd](activities/day7_DataWrangling2Activity.Rmd) [.md](activities/day7_DataWrangling2Activity.md)
          - solutions: [.Rmd](activities/solutions/day7_DataWrangling2Activity_Solution.Rmd) [.md](activities/solutions/day7_DataWrangling2Activity_Solution.md)
    
**Wednesday** (Data intake)

-   before class
    -   read MDSR sections 5.5.3 and 5.5.4 (we'll come back to the other sections after the exam)
    -   read Grolemund/Wickham [chapter 16](http://r4ds.had.co.nz/dates-and-times.html#introduction-10) - focus on sections 16.2 and 16.3.
-   in class
    -   day 8 slides: [.Rmd](docs/day8_DataIntakeSlides.Rmd) [.html](https://econ122-f22.github.io/home/day8_DataIntakeSlides.html)
    -   day 8/9 activity: [.Rmd](activities/day0809_TidyDataActivity.Rmd) [.md](activities/day0809_TidyDataActivity.md)
          - solutions: [.Rmd](activities/solutions/day0809_TidyDataActivity_Solution.Rmd) [.md](activities/solutions/day0809_TidyDataActivity_Solution.md)

------------------------------------------------------------------------

### Week 6 (10/03) 

**Monday** (`tidy` data: reshaping with `gather` and `spread`)

-   before class:
    -   read MDSR sections 5.1-5.3
-   in class:
    -   day 9 slides: [.Rmd](docs/day9_TidyDataSlides.Rmd) [.html](https://econ122-f22.github.io/home/day9_TidyDataSlides.html)
    -   continue day 8/9 activity

**Wednesday** (Strings and regular expressions)

-   before class:
    -   read Grolemund/Wickham [chapter 14](http://r4ds.had.co.nz/strings.html) on strings and regular expressions
    -   finish up homework 4 - due Monday
        -   to tackle problem 4 Q2, make sure to review the `lubridate` examples in the day 8 slides and [WG section 16.2.2](http://r4ds.had.co.nz/dates-and-times.html#from-individual-components).
-   in class: 
    -   [exam explanation](exam1.md)
    -   day 10 slides: [.Rmd](docs/day10_StringsSlides.Rmd) [.html](https://econ122-f22.github.io/home/day10_StringsSlides.html)
    -   day 10 activity: [.Rmd](activities/day10_stringsActivity.Rmd) [.md](activities/day10_stringsActivity.md)
        - solutions: [.Rmd](activities/solutions/day10_stringsActivity_Solution.Rmd) [.html](https://econ122-f22.github.io/home/day10_stringsActivity_Solution.html)
        
------------------------------------------------------------------------

### Week 7 (10/10)
        
**Monday** (Iteration)
-   before class:
    -   read MDSR section 5.4
-   in class:
    -   day 11 slides: [.Rmd](docs/day11_IterationsSlides.Rmd)  [.html](https://econ122-f22.github.io/home/day11_IterationsSlides.html)
    -   day 11 activity: [.Rmd](activities/day11_IterationActivity.Rmd) [.md](activities/day11_IterationActivity.md)
        - solutions: [.Rmd](activities/solutions/day11_IterationActivity_Solution.Rmd) [.md](activities/solutions/day11_IterationActivity_Solution.md)

**Wednesday**
-   before class:
    -   study for exam 1
-   in class:
    -   take exam 1

------------------------------------------------------------------------

### Week 8 (10/17)

**Monday**

  - Fall Break!!
  
**Wednesday** 

  - No class!!
      - Professor going to Belgium for a conference at the [National Bank of Belgium](https://www.nbb.be/en/publications-and-research/research-cooperation/research-conferences/international-biennial-research). Let me know if you have any requests
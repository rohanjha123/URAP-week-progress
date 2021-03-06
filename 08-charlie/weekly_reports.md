### Week 11 Progress (12/04/20)

Assigned Tasks:

1) Created my own reproduction
2) Shiny app readme updates/formatting
3) Updated names of reproductions

Completed Tasks:

1) Fixed my previous input of someone else's reproduction (made a minor error)
2) Created my own reproduction
   * Read the paper
   * Inputted my reproduction online
2) Formatting changes to shiny app readme
   * Added explanation of `knitr::purl("code/05_final_opa.Rmd", "code/shiny_app/all_analysis.R")`
   * Can't figure out how to have the readme show a photoshop file
3) Updated names of reproductions

### Week 10 Progress (11/27/20)

Assigned Tasks:

1) Input results from previous reproductions
2) Shiny app readme formatting

Completed Tasks:

1) Inputted the results of one reproduction
2) Formatting changes to shiny app readme
   * Was asked to reference `knitr::purl("code/05_final_opa.Rmd", "code/shiny_app/all_analysis.R")`
         * But this was commented out? Or is my version not up to date?
3) Read through welfare tax shiny app

To Do:

1) Input my own reproduction
2) Make wealth tax shiny app improvements

### Week 9 Progress (11/20/20)

1) Attended weekly meeting on Monday

Assigned Tasks:

1) Improvement on wealth tax shiny app
2) Read through ACRE guidelines
3) Input results from previous reproductions
4) Shiny app description

Completed Tasks:

1) Read through ACRE guidelines, better understood ACRE
    * In the guidelines, there is different formatting for lists (bullet points, numbers, letters). All three are used with little to no consistency. For example...
      * In 2.3.1, there are bullet points with a sublist of letters
      * In 3.1.1, there are numbers with a sublist of numbers
      * In chapter 6, there are numbers with a sublist of letters
      * In 6.1, there are numbers with a sublist of bullet points
      * These are just examples of inconsistencies with listing, are these inconsistencies intentional? Should I fix them?
    * Not sure what the table/chart at the beginning is trying to show?
2) Inputted the results of one reproduction
3) Read through wealth tax and thought of improvements for shiny app
    * Problem with spacing on shiny app
    * Move credits
    * Maybe not thick lines?

To Do:

1) Input the results of another reproduction
2) Input my own reproduction
3) Shiny app description edit
4) Wealth tax shiny app readme

### Week 8 Progress (11/13/20)

1) Attended weekly meeting on Monday
2) Worked on readme 
3) Deleted shinyapp readme that was in the code folder

Assigned Tasks:

1) Edit readme for shiny app
   * Add introduction at top
   * Fix formatting of functions/file names using ``
   * Discuss how the different documents interact w/chart

Completed Tasks:

1) Edited readme for shiny app
   * Added introduction
   * Fixed typos
   * Made a simple chart for the last section (relationship between the documents)

Questions:

- Should the names of files be the only thing with `()` (i.e. `ui.R`) or should it also contains functions (i.e. `sim.data`)? Currently I have it for both.
- Should more explanation be added to the last section?

To Do:

- Can make more edits on readme, but also feel ready to move on to new work

### Week 7 Progress (11/6/20)

1) Attended weekly meeting on Monday
2) Realised that my code was not updated, fixed that 
3) Deleted shinyapp readme that was in the code folder, not the shiny app folder

Assigned Tasks:

1) Edit readme for shiny app
   * Add new section for server.R
   * Edit slider section
   * Discuss how the different documents interact

Completed Tasks:

1) Edited readme for shiny app
   * Added a walkthrough about how to add/delete sliders
   * Created server.R walkthrough (thank you Aleksandra!)
   * Made a simple chart for the last section (relationship between the documents)
2) Worked more on understanding how server.R, ui.R, and all_analysis.R interact with each other

To-Do:

1) Go more in-depth with the function explanations
2) Add an image to the readme (need Fernando's help/permission I believe)

### Week 6 Progress (10/30/20)


**Have had a lot of midterms this week and last, so I am using one of my off-weeks this week**

1) Attended weekly meeting on Monday

Assigned Tasks:

1) Edit readme for shiny app
   * Add new section for server.R
   * Add a walkthrough about how to add/delete sliders
   * Move to shiny app folder and rename

Completed Tasks:

1) Edit readme for shiny app
   * Added a walkthrough about how to add/delete sliders
   * Moved to shiny app folder and rename
2) Worked on understanding how server.R, ui.R, and all_analysis.R interact with each other

To-Do:

1) Add new section for server.R (probably help from Aleksandra)


### Week 5 Progress (10/23/20)

1) Attended weekly meeting on Monday

Assigned Tasks:

1) Create readme for Shiny App

Completed Tasks:

1) Created a very rough draft for the readme
    * Questions I had are in the readme
    * Would be great to get someone to provide edits


### Week 4 Progress (10/16/20)

1) Attended weekly meeting on Monday
2) Finished shiny tutorial (last week spent on tutorials)

Assigned Tasks:

1) Add suggestions to 00_bones.rmd
2) Explain invisible( list2env()) in readme tutorial

Completed Tasks:

1) Worked with Aleksandra on the 00_bones.rmd edits
    * Typo edits
    * Question about having results earlier
    * Fixed rendering issue for one of the equations
2) Wrote up explanation for "invisible" in the readme file
    * Not sure where to put it, asked Aleksandra
    * Will create a pull request this weekend
    * WEEKEND EDIT: Added explanation to readme file

Work time - 8 hours

### Week 3 Progress (10/9/20)

1) Attended weekly meeting on Monday
2) Shiny tutorials
3) Trying to understand how the code produces the shiny app
    * Worked through the first section, I think I understand exactly how the code creates the document.
    * What does the "invisible" function actually do? For example: "invisible( list2env(chunk_earnings1(),.GlobalEnv) ). I looked this up online and it didn't       clarify it for me
4) Told Aleksandra my edits/recommendations for the readme document
5) Worked on understanding the package situation
    * Uninstalled all packages
    * Reproduced the dynamic document
    * Tried to knit
    * The packages that I had to manually install were:
      * bookdown
      * tidyverse
      * here
      * kableExtra

Work time - 8 hours

### Week 2 Progress (10/2/20)

1) Attended weekly meeting on Monday
2) Kept familiarizing myself with Github
3) Downloaded RStudio
4) Familiarized myself with RStudio
5) Installed Shiny, experimented with Shiny apps, pasted simple Shiny app code to see how it worked
6) Deworming
    * Read a summary of deworming
    * Reproduced the dynamic document
    * Read through the dynamic document and the deworming readme to try to understand the code
    * Installed all of the neccesary packages to run 05_final_opa.rmd
7) Worked through Sophia's demos for Diagramme, RShiny

Questions:

1) Don't think I have any yet, struggling to understand the dynamic document but working my way through.

Work time - 8 hours

### Week 1 Progress (9/25/20)

1) Read the onboarding readme file
2) Created folder and weekly report file
3) Read the open policy analysis framework paper
4) Reviewed the Wealth Tax open policy analysis paper, experimented with the interactive aspects
5) Read the Warren and minimum wage documents

Work time - About 6-8 hours

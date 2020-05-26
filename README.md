# Project Title

DSC160 Data Science and the Arts - Final Project - Generative Arts - Spring 2020

Project Team Members: 
- Joseph Del Val, jdelval@ucsd.edu
- Nathan Tsai, nhtsai@ucsd.edu
- Jacob Benson, jtbenson@ucsd.edu
- Hanbyul Ryu, h9ryu@ucsd.edu
- Gabriel Zalles, gzalles@ucsd.edu

## Abstract

(10 points) 

Our project is to take a closer look at what artistic features define a group of similar artists or a specific art movement/period. We aim to take groups of artists and their works to train a model and generate a unique result representing the artists. As for our training data to start this project, it will consist of the collected paintings of all of the artists we have in question, such as the works of Dali, Van Gogh, and Picasso. Our result will be a collection of sets of GAN-generated images, each from their particular artist. These sets will ideally each have specific artistic features that define them, thus defining that artist.. We hope to see clear distinctions between the generated images from each artist / movement enough to where one could identify the artist based on the features of the generated image.
	There may be some challenges in doing this, however. Many artists may have not composed a large number of paintings, making their works alone quite unsuitable for a training set for a GAN. If we are to combine several artists into one “movement” on which we run the     GAN, this dataset may end up quite heterogeneous. Moreover, some artists have had many distinct periods within their works, which can add some additional heterogeneity to the data. But, overall, this project is culturally interesting because it will reveal to us the discerning features of each art movement. Personally we were interested in what images would be created based on at least a large majority of each artist's complete works, considering each one went through many different phases and styles of work. This project will build off of the GAN material we have already covered in class and on assignment 3, and build off code such as the GAN notebook from class, and the scrape wikiArt notebook from class. https://github.com/rkjones4/GANGogh
## Data and Model

(10 points) 

In the final submission, this section will describe both the data you use for this project and any pre-existing models/neural nets. For each you should provide the name, a textual description, and a link. If there is a paper (for neural net) link that as well.
- Such and such Neural Net. The short description of this neural net. 
  - [link to code]().
  - [Title of Paper with Link](). 
- Training data. Short description of training data including bibliographic info. [link to data]().

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- code for data acquisition/scraping
- code for preprocessing
- training code (if appropriate)
- generative methods

Link each of these items to your .ipynb or .py files within this seection, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section should summarize your results and will embed links to documentation to significant outputs. This should document both process and show artistic results. This can include figures, sound files, videos, bitmaps, as appropriate to your generative art idea. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally innovative?
- How does your generative computational approach differ from traditional art/music/cultural production? 
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- What are the ethical concerns for this form of generative art? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

All references to papers, techniques, previous work, repositories you used should be collected at the bottom:
- Papers
- Repositories
- Blog posts

## Project Report Grading Rubric

The idea is that this project report should be a manageable amount of work, but that if you want to turn your project into a paper, everything in the project report will need to be done anyways.  If you feel that your project won't fit into this rubric, please talk to me.  There are many ways to make contributions to a field!

**Length**: 4 to 8 pages, not including appendices or bibliography.  Don't be afraid to keep the text short and to the point, and to include large illustrative figures.  You can include as many proofs, extra details, experiments, etc. as you want in the appendices.

1. **Abstract (4 points)** that summarizes the main idea of the project and its contributions.
     - Should be understandable to anyone in the course.
     - You don't need to say everything you did, just what the main idea was and one or two takeaways. 

2. **Introduction (4 points)** that states the problem being addressed and why we might want to solve it. 

3. **Figure or diagram (8 points)** that shows the overall model or idea. The idea is to make your paper more accessible, especially to readers who are starting by skimming your paper.  You must create a new figure, not just use someone else's, even with attribution!

     - For the project, taking a picture of a hand-drawn diagram is fine, as long as it's legible.
     - For camera-ready diagrams, we recommend using Tikz, a LaTeX package.
     - Try to be clear whether arrows indicate computational flow, or conditional dependencies, or both.

4. **Formal description (16 points)** of the model / loss function / conjecture / problem domain.
Include at least one of:
     - An algorithm box.
     - Equations describing your model.
     - A theorem or formally stated conjecture.
     - A formal description of a problem domain.
     
     Highlight how your model is different from other approaches, or what the main relevant considerations are for the domain. This can be done by comparing it to an existing model, perhaps by using another diagram or in words.  E.g. if you are proposing a new algorithm that only changes one line in an existing algorithm, highlight that one line, or do a side-by-side comparison.

5. **Related work (16 points)** section and bibliography.
     - If your project builds on previous work, clearly distinguish what they did from what your new contribution is.
     - Also, include a 1-2 sentence summary of other closely related papers.
     - I realize you might not know about all related papers (or have time to carefully read all related papers), and that's OK for this project.
     - Using bibtex is annoying at first, but Google Scholar can give you the bibtex entries.

6. **Comparison or demonstration (16 points)**. Include at least one of: 
     - A demonstration of a theorem or conjecture. For example, an example or counter-example.
     - A comparison of data generated by your model to a baseline model.  Qualititative evaluation is OK.
     - An experiment demonstrating a property that your model has that a baseline model does not.  Experiments should also include a description of how you prepared your datasets, how you trained your model, and any tricks you used to get it to work.
     - If doing a review, include a table comparing the properties of the different approaches.

     Toy data is OK!  The point is to help the reader understand why or when we would want to use one approach over another, or to understand something better.  Try to summarize the main takeaways.

7. **Limitations (12 points)** of your approach.
	- Describe some settings in which we'd expect your approach to perform poorly, or where all existing models fail.
	- Try to guess or explain why these limitations are the way they are.
	- Give some examples of possible extensions, ways to address these limitations, or open problems.

8. **Conclusions (4 points)**
	- State the results achieved in relation to the problem described in the introduction.
	- Repeat the main takeaways from your paper.
	
9. **Novelty (20 points)** In order to encourage novel directions over lit reviews.  Novelty is graded on a sliding scale and is subjective, but here are a few guidelines:
	- 0 points: A literature review with no new content.  This is completely OK as a project, but it won't earn an A+.
	- 5 to 15 points: A novel combination of method and type of data, or motivate and formally pose a new problem.  You get novelty points for making tweaks to a method to take advantage of the structure of a new dataset or domain.  Think of a reason why the experiment turned out the way it did, and check if this was actually the reason.
	- 20 points: Novel method with motivation (not just making a random tweak for no reason), or analysis with a new result.  Is the reason you say it is going to work actually the reason why it works?


**Extra guidelines:**

- You're free to play with the format of your paper, as long as all the above content is there and easy to find.
- Put long mathematical derivations that interrupt the flow of the paper in an appendix.  This is also a good place to put extra generated examples.
- We encourage you to attach your code, although this is not required.
- Axes should be labeled.
- Text in figures should be about the same size as the text in the rest of the paper.
- For figures, try to use a vector graphics format such as pdf, eps or svg so that your figures don't look blurry.

Positive examples:
[PixelVAE: A Latent Variable Model for Natural Images](https://arxiv.org/pdf/1611.05013v1.pdf)
Your project report doesn't have to be as polished as this, of course!
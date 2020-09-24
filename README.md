# Misc
Various code snippets or jupyter notebooks I've put together for fun.

Most likely this is code that isn't super clean and perhaps not directly clonable and runnable, especially with respect to dependencies. When I've got some time to circle back I'll try and give explicit directions on any dependency issues.
TLDR: Check this code at your own risk ;).

## projects uploaded here:
- coding_interview: Was a coding interview that I had for a Machine Learning internship position in the drug discovery space.
  - 'coding_interview_completed.ipynb' has my implementation and 'coding_interview_original.ipynb' has the original questions
  - Highlights include:
    - Problem 1: simple Palindrome algorithm question
    - Problem 2: parsing in files
    - Part 2: multi-class classification machine learning problem on pokemon data set.
- Relay_Tx_stuff: This directory has some scripts that I was allowed to put up on my Github from my 3-month Machine Learning internship at Relay Therapeutics. Confidential data, molecules, etc have been excluded purposefully.
  - "metrics_evaluation_checkpoints_model.ipynb": I'm evaluating a Chemprop (D-MPNN graph neural network) model that was built for FRED Docking scores on the ENAMINE REAL data set.
    - The goal of this undertaking was to train on a million molecules (with their FRED scores) and then test on much much more (here I test on ~10 million, but the idea would be to test on the full ENAMINE REAL data set that will consist of up to 12 billion molecules).
    - I used some standard metrics for evaluating the performance of this regression model and also show the utility of the model in being able to recover well the highly negative scored (the more negative the better) molecules.

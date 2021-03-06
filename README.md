# DukeDataPlus-Summer18-Proj17
Code and references for Duke's Data+ Project 17 (Summer 2018) -- Complex Decisions, Real Numbers: Medical Decision-Making.

You can find our project description here: https://bigdata.duke.edu/projects/complex-decisions-real-numbers-medical-decision-making.

Thanks to Duke's Data+ and Bass Connections programs for providing the support for this research.

If you have any questions, feel free to email us at:
- samantha.garland@duke.edu
- grant.kim@duke.edu
- pseshadri@g.hmc.edu

Files:
- Stop_Word_Rules: A comprehensive list of all the stop words we used, the process we used to come up with that list, and the categories these words belong to.
- Master Pipeline: Our main file. It runs through the text pre-processing, the cross-validated models (using Leave One Out -- baseline, baseline + advice, and baseline + LDA topic distributions from transcripts, performance metrics, and finally our final LDA model using all the transcripts.
- Master Pipeline with Convo 1 and 2 - final: The same master pipeline, now with the LDA model trained on the combined conversations then applied separately to conversations 1 and 2.
- References: The scientific papers we used along the way.

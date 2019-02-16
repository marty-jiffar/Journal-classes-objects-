# Paper Tracking

Program idea source: https://classes.cs.uchicago.edu/archive/2018/fall/12100-1/pp/journal.html

This program models a system for academic papers that tracks reviews, submissions, etc. There are four classes: Journal, Paper, Review, and Reviewer.

get_papers_above(self, score) "return[s] a list containing the Paper objects that have an average review score of score or higher."

"A reviewer has a name, a university affiliation, and a list of areas of interest. A single area of interest can be modelled as a string, just like the areas of specialization in the Paper class.
The areas of interest should be provided when a Reviewer object is created, but it must also be possible to add and remove areas of interest.
Given a Paper object, we would like to know whether the reviewer is a good match for that paper. That is, we want to know whether the review has at least one area of interests that overlaps with the areas listed for the paper."

Test code included:
"1. Constructs a Journal object,
2. Constructs Reviewer objects,
3. Constructs Paper objects,
4. Adds reviews to papers,
5. Checks whether a reviewer is a good matches for a few papers, and
6. Add and remove areas from reviewers re-check whether they are good matches for a few papers."

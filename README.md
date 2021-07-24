
  <h1 align="center"> The Pagerank-Index </h1>

  <p align="center">
    Student project on course Scientific Computing, Master Degree Studies, University of Belgrade, Faculty of Mathematics
    <br />
   
 <!-- ABOUT THE PROJECT -->
## About The Project

This project is reimplementation of the analysis undertaken in paper:
> <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4545754/#" > "The Pagerank-Index: Going beyond Citation Counts in Quantifying Scientific Impact of Researchers",  Upul Senanayake, Mahendra Piraveenan, Albert Zomaya </a>

In this paper authors <i> introduce the pagerank-index, which is designed to address the drawbacks of existing indices</i> (e.g. h-index) <i> by utilizing the underlying citation network dynamics. The index is calculated by running the well known pagerank algorithm on the evolving citation network to give scores to papers. </i>
They <i> develop and employ a realistic simulation system which synthesizes the evolution process of citation and collaboration networks in an emerging field.</i>
They also <i> demonstrate the utility of the new index by applying it to two real-world data sets. </i>

In this project, a system that stores a citation network and calculates mentioned indices is implemented, mentioned simulation system is developed mostly following instructions from the paper and the indices are also applied to one of two real-world datasets the authors uploaded to the GitHub (see <a href=#references> References </a>). Some additional observations were made with the obtained results.

<!-- LANGUAGES AND TECHNOLOGIES USED -->
## Languages and technologies used

* Implementation is in [Python 3.7](https://www.python.org/).
* Code was written using [Anaconda](https://www.anaconda.com/), [The Jupyter Notebook](https://jupyter.org/), [Google colab](https://colab.research.google.com/notebooks/intro.ipynb).
* [NetworkX](https://networkx.org/)'s PageRank algorithm implementation was used.
* Other packages and libraries used: [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/), [pandas](https://pandas.pydata.org/).

<!-- NOTES -->
## Notes

* There is a lot of room for experiment with implemented simulation system which synthesizes the evolution process of citation networks. Parameters of the system (e.g. the probability of new authors being spawned, average length of paper's reference list and author list, etc.) can be varied to monitor changes in results.
* Since the results in some scenarios on the synthesized data in this project are different from those in the paper, the cause should be investigated.
	* We can delve deeper into the nature of real-world citation networks, to understand how relevant the results on our current artificial network are.
	* We can develop a system for recognizing groups of authors who 'massage' their h-index (those who cite themselves, who work in large groups, who focus on quantity rather than quality) and apply it to real-world data to compare indices that way.
* We can test efficiency of the system on very large real-world database.

<!-- REFERENCES -->
## References

* The paper: <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4545754/#" > "The Pagerank-Index: Going beyond Citation Counts in Quantifying Scientific Impact of Researchers",  Upul Senanayake, Mahendra Piraveenan, Albert Zomaya </a>
* The real-world datasets authors used in the analysis: <a href=https://github.com/upulcranga/pindex> https://github.com/upulcranga/pindex </a> (in case the previous link doesn't work: <a href=https://github.com/marijakatic/pindex.git> https://github.com/marijakatic/pindex.git </a>)


<!-- CONTACT -->
## Contact

* Marija Katić | katic.marija.97@gmail.com, mr16032@alas.matf.bg.ac.rs | https://github.com/marijakatic


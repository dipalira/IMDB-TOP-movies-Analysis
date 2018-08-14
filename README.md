# IMDB-TOP-movies-Analysis
**Abstract** Our project is intended for users that want to discover new movies they may not have seen yet. More specifically, it will help users find movies that are related to movies they have watched while also maintaining a similar rating. Our project does topic analysis on the top and bottom 250 user rated movies on IMDb (a reliable source to find movie ratings) and generates multiple dynamic graphs. It is useful because it facilitates searching for a new movie by focusing on the visualization of the data, making it easier to analyze. We have published some of these visualizations on a web page for people to explore, which can be seen by opening index.html from the GitLab repository.  <https://gitlab-beta.engr.illinois.edu/jmoral39/cs410project>

**Implementation/Methodology**
Our probabilistic approach employs LDA to model user top and bottom IMDb rated movie summaries. We assume that movie summaries can be modeled as mixtures of topics, and that each topic represents a probability distribution over movies. In this process,we hope to find the similarities in movies which are highly/lowly ranked.


**Data Collection:**
To collect our data, we scraped the IMDb web sites which contained the top and bottom 250 IMDb rated movie Ids. Next, we wrote a python script that found tags for each of the movies in the lists, allowing us to write the movie IDs in a text file. We then used IMDbPY (Python package) to gather the movie titles, year of release and summaries which were later stored into separate text files.Besides the list of movies collected, we also used the CMU Movie Summary Corpus for topic modeling and visualization. This dataset contains 42,306 movie plot summaries and associated metadata.
**Results**
For our full results, please read the final report.

Author - Jose Morales, Bobby Zahn, Dipali Ranjan 

Department of Computer Science, University of Illinois at Urbana-Champaign

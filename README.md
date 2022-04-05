# Decision-Theory (Movie Recommendation System)

Developed a system that suggests movies to users based on the movies they have watched and the ratings they have made. In addition, data is analyzed from which information was extracted and visualized. 

Initial Datasets: users.csv, movies.csv, ratings.csv

New dataset fixed_ratings, fixed_users, fixed_movies were built to serve the data analysis done in showtime.py

Project files description:

user_based_collaborative_filtering -> movie suggestion system (2 scripts)

demographics ->  data processing of datasets for information retrieval.

showtime -> data analysis for data visualization and production of statistics.

Suggested execution order:

1. user_based_colabborative_filtering
2. demographics
3. showtime

There is extensive commentary on all code files.

Libraries used in the Project:

sys
csv
random
warnings
pandas 
numpy 
pandas.io.parsers, FixedWidthReader
scipy, csr_matrix
matplotlib.pyplot
seaborn
numpy.lib.arraysetops, unique
numpy.lib.shape_base, split
collections, Counter
operator, itemgetter
itertools, combinations
sklearn.neighbors, NearestNeighbors
sklearn.model_selection, train_test_split

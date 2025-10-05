Key Insights and Concepts:
-----------

* Content-Based Filtering : Recommends items based on similarity of item attributes (genres, keywords, overviews) rather than user preferences.
* TF-IDF Vectorization : Converts text data into numerical vectors, emphasizing important words specific to each movie.
* Cosine Similarity : Measures similarity between vectorized movies; values closer to 1 indicate higher similarity.
* Stop Words Removal : Common words that don’t add meaning are filtered out to improve recommendation quality.
* OMDb API Integration : Provides external movie data (plots, posters) to enrich recommendations with details beyond the dataset.
* Streamlit UI : Provides an interactive frontend for users to select movies and view recommendations with enhanced visuals.
* Data Cleaning & Preprocessing : Includes handling missing values, concatenating relevant columns, and cleaning text data to prepare for vectorization.

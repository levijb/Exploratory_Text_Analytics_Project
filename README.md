# Exploratory_Text_Analytics_Project
## University of Virginia, DS 5001: Exploratory Tex Anlaytics, Spring 2023

This project explores the lyrics of over 100 hip-hop artists from the 1980's to present day. Techniques used include TF-IDF, Principle Component Analysis(PCA) with hierarhcical clustering, Latent Dirichlet Allocation (LDA) topic modeling, word2vec word embedding, and sentiment analysis. 

Files:
- Data: JSON files with lyrics downlaoded from Genius.
- Data files: CSV files(some compresesed) of dataframes created throughout the analysis.





Hip-Hop, a genre of music and cultural movement that emerged in the late 1970s and early 1980s, has had a significant impact on popular culture since its inception. Born as a counterculture movement in basements and on the streets, Hip-Hop has grown into a global phenomenon that dominates the music industry. Despite its widespread popularity, Hip-Hop has often faced criticism from certain conservative and older communities due to its often-explicit language, crude insinuations, and depictions of immoral or illegal behavior. Despite these criticisms, Hip-Hop's popularity continues to soar, and it has become one of the most influential genres of music in the world. In this project, I will delve into the lyrics of Hip-Hop music to better understand the cultural significance of this ever-evolving art form. Some questions to guide my exploration: which artists have the longest and most unique lyrics, which artists are the most similar, how has lyrical sentiment changed over time, and what are the most popular topics in hip-hop songs?

To gather data for this project, I used the [lyricgenius](https://pypi.org/project/lyricsgenius/) package to download song information for various hip-hop artists from the [Genius.com API](https://docs.genius.com/). There is a separate JSON file for each artist, and these are combined to make a complete corpus. 116 artists were selected from the 80s to present day, and each artist has more than 50 songs and no more than 250. The artists were selected based on popularity rankings from various websites while making sure to include at least 20 artists from each decade, except the 1980's as hip-hop was just begining to emerge as a genre. I manually created a dictionary to include each artist's hometown and state, and an artist year column was created by taking the median song year for each artist. 



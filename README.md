# MusicRecommendationSystem
Final Year R project for Music Recommendation
Run the code in R studio.
it takes 1 input that is Genre. Insert whatever Genre you want. Note: Genre should be present in the database.
The ouputs:
dfsr: Top songs based on song rating. (content based)
dfaf: Top songs based on Artist Familiarity (Content based)
playlist 1: playlist for User A based on top rated of User B(Collaboration based)
playlist 2: playlist for User B based on Top Rated of User A(Collaboration based)
Note: User A and User B are determined by using cosine similarity. Users with highest similarity are taken as A and B.

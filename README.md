# IS362_Week7

# User Average Ratings  
The average rating each user gave across all movies.

# Movie Average Ratings  
The average rating each movie received across all users.

# Normalized Ratings  
Min-Max normalization applied per user, where ratings are scaled between 0 and 1.

# Standardized Ratings  
Z-score standardization applied per user, where ratings are adjusted based on their mean and standard deviation.

## Conclusion on Normalized Ratings

### Advantages:
- Allows fair comparison of user ratings since different users may have different rating tendencies (some may rate generously, others more critically).
- Useful when implementing recommendation algorithms that require standardized inputs.

### Disadvantages:
- Normalization can distort the original rating scale, making it harder to interpret the real sentiment behind the ratings.
- If a user has rated only a small number of movies, normalization can amplify small differences disproportionately.

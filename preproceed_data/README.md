1. O_mask: Mask to determine whether the user-item pair is observed
2. item_features, user_features: encoded features for each movie and user

      example code to combine them for all possible user-item pairs can be seen in IPS_generate - "Concatenate user and item features into a matrix for all possible user item pairs"
3. rating_pairs: rating in matrix form for all user_item pairs, containing a lot of NaN values
4. propensities: propensities for all user_item pairs

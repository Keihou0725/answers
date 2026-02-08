# answers
Figures and outputs are in separate files. For any text, answers will be answered here.
Conceptual answers: Bag-of-words showed more interpretable results compared to the embedding-based method. In Bag-of-words, each dimension corresponds to a specific word, whereas embedding-based methods group similar words into a single type. The trade-off of using Bag-of-words is that it loses downstream modelling, since it is not as expressive as the embedding-based method in converting characteristics into spatial-level representations, with better performance in regression.


Question4 LDA question: Topic 1 dominant topic should relate “romantic”, the top 8 words including love, father, film, life, man, tells, family, and girl. Topic 2 is related to “neutral” drama, including police, paul, new, goes, gets, time, home, and father. Topic 3 is related to “interpersonal”, including words such as film, Michael, John, father, house, time, life, and mother. Topic 4 should be named as “conflicts drama”, including words town, war, army, men, killed, later, begins, and escape. Topic 5 is related to character-driven with crime, including anne, tells, car, goes, man, mike, mother, police, and johnny. Topic 6 is related to characters, including words as jerry, Norman, max, tom, mary, and carl as well as mother
The two topics should contain the neutral drama, which is topic 2, and the conflicts drama, which is topic 4. Topic 2 contained lots of neutral words for me, as well as demonstrative pronouns, but I needed to differentiate from topic 1, therefore named it neutral. Topic 4 contained lots of negative words and included some words containing “conflicts”, such as war, killed, etc. The preprocessing of skipping the stopwords and deleting low-frequency words can improve the topic quality, since stopwords are meaningless, as well as low frequency words can not represent the overall sample size. 

Question 5
MAE:  0.2717
RMSE: 0.366
R^2:  0.0722
This can help transfer the plots of the movies into a quantitive way to predict the type of movie, however it contains some limitations. First, if the sample size is small, it will directly impact the embedding quality, and the impact maybe larger than the bag-of-words when using the small sample size. In addition, the interpretation of this approach may less interpretable compared to bag of words, since each word has been converted into a dimension, and it is hard to determine which dimension represents what kinds of meaning. 


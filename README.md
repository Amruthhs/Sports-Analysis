# IPL-Analysis

* Our project for CA683 Data analytcis and Data minig is titled "IPL match analysis and prediction".
* Sports is one of the prime topics of discussions in today's world, attracting millions of followers. 
* Cricket is considered to be most exciting and unpredictable game and IPL is the biggest sport event that happens in India every year. 
* It's becoming a billion dollar market for many as they gamble financially, expecting to be able to earn income. 
* So, would'nt it be great if we could predict or understand the game's outcome. 
* So, this work focuses on predicting Indian Premier League (IPL) match-winning result, considering different influencing factors using machine learning algorithms such as Logistic Regression, Random Forest and K-Nearest Neighbors. 
* Paper also provides the analysis of why IPL has achieved such huge success in short period and for team owners to look for best players in auction.

# Data Source 
The data set is taken from kaggle.com, it has about 150k rows and 30+ columns, we are primarly intrested in features like venue, toss winner, toss decision, etc which help us to answer our main reserach questions 

# Research Questions
[1] Toss win match win 
here we are trying to answer the question "what is the match winning percentage of a team who wins the toss?"
[2] bat first match win - "what are the chances of team winning that match who batted first?"
[3] Home advantage- "how does team playing in its home ground has advanatge over away matches"
[4] home advantage+ toss winner - "what is the percentage of team winning a match if it plays in home ground and wins has won the toss"

# labelling the factors  
"over the period of time, teams name changed but represented the same city, so we had to make sure that there was no ambuguity in team names and the city they represented  "


# why choosing these algorithms?
Due to its flexibility, non-parametric design and ease of execution, the KNN algorithm is commonly used in text categorization tasks

Random forest?
Random forest is an ensemble model whos fundamental working is based on decison trees. since most of the predictor varivbl we are using are catogerical in nature a decision tree baswed random forest tree model would give us good results. Random forest also help in the cause of the bias and variance trade off and avoids overfitting of the data. 

# Future Work
DL method not implemented, rain interrupted matches not considered 
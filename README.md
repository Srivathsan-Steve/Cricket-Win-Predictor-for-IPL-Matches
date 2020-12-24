# Cricket-Win-Predictor-for-IPL-Matches
<p>Cricket is a well-known game that is played and watched around the globe. The Indian Premier League (IPL) is a T20 League which was started in 2008 and is now one of the most irresistible T20 cricket carnival. Investments on this are increasing each season, its viewership has increased markedly and the fantasy league market for IPL is growing significantly every year.</p>
<p> This work focuses on predicting the winner of an IPL match based on the historical team performance data. Various features have been analysed to predict the match winner before the game started. Different features such as home ground, toss winner, toss decision etc have been looked at to predict the winner. For this purpose, different types of classification techniques are evaluated to seek accurate models that can predict the outcome of a match. The dataset chosen is obtained from a well-known repository Kaggle and it contains past match records of 11 IPL seasons (2008-2017) capturing 17 features for every match played within the timespan.</p>
<p>Influential features from the dataset have been obtained using filter-based and wrapper-based methods such as Correlation-based Feature Selection (CBF), Information Gain (IG), Relief-F etc. Two feature subsets were formulated from these extracted features, one based on home team advantage and other based on Toss decision. Various Machine Learning classifiers including Naïve Bayes, Random Forest, K-Nearest Neighbour (KNN) and Model Trees (Decision Tree C4.5) have been trained on both the feature subsets and evaluated for performance.</p>
<p>Experimental tests show that tree-based models particularly Random Forest performed better on both the feature sets when compared to probabilistic and statistical models. KNN outperformed the other algorithms when processing the Toss Winner feature set despite the fact that overall accuracy of all the models were low.</p>
<p> Considering the dynamic nature of the game, ball by ball statistics, team players’ data etc. it is required to improve the overall accuracy of prediction.The prediction model will have benefits for cricketing boards like evaluating the team’s strength and cricket analysis. For fantasy applications and match reporting media this model will be a blessing in disguise.</p>

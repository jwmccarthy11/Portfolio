# Predicting NBA Draft Prospect Value Using LTR
### Jack McCarthy
<br>

Drafting the right players is a critical component to the success of any professional sports franchise. NBA teams in particular place a significant importance on drafting quality players in order to construct a successful roster, going so far as to intentionally achieve a poor record in order to obtain a better draft position. It is crucial, then, that teams draft the best players. This is a difficult and messy process, however, especially outside of the top few picks. I propose the construction of a draft prospect ranking model, which I have tentatively decided will be a pairwise LTR model (such as LambdaMART) trained on draft prospect’s college stats. Players drafted from Europe or elsewhere that did not play in the NCAA are not planned to be considered for this project due to data scarcity and the inherent differences between American and foreign basketball leagues. Data will be obtained from basketball reference, which contains both college and professional statistics for the plays under consideration. There is no single metric that entirely summarizes a player’s impact which we may use to compare players, but a few advanced stats exist that may be helpful in training a model that prioritizes certain abilities or characteristics.

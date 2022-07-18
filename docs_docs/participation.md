## **How to Participate**


- The organisers have defined [three-subtasks](https://afrisenti-semeval.github.io/#:~:text=Task%20A%3A%20Monolingual%20Sentiment%20Classification%3A%20Given,target%20languages%20is%20positive%2C%20negative%2C%20or%20neutral.) 
and will release the training data. Participants can work on any or all of the subtasks.

- The participants can form a team with multiple people, or a single person team is okay.

- The participants can experiment with the training data to develop models. Usage of any external data or resources is allowed and highly encouraged. This process can run util the evaluation period.

- Evaluation period: Organisers will release the test set containing instances without the labels. The participants will use their developed models to predict the labels for the instances, and they have to create a submission file that follows exactly the same format as the training data. These prediction files should be submitted to Codalab submission portal (will be announced later). These predictions will be compared against the ground truth labels of the test data and the teams will be ranked on a leaderboard according to the performance score.

- Each team is encouraged to write a system description paper describing their submission system, including interesting insights, and submit it before the due date. After a review period, each team has to update their submitted paper based on the review feedback and submit the camera-ready version. Accepted papers will be published as part of the proceedings of the SemEval 2023 Workshop (link).
.


## **Training Data Format**

AfriSentiEval 2022 featured datasets in thirteen African languages, namely: Hausa, Yoruba, Igbo, Nigerian-Pidgin, Swahili, Amharic, Tunisian Arabizi, Kinyarwanda, Algerian Arabic dialect, Tigrinya, Twi, isiZulu, Setswana. 

Twitter has a [strong policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy) for public distribuition of user data and allows only the sharing of TweetsIDs
 allow only sharing of TweetsIDs. Therefore, we will not be able to provide the full text of the tweets. Instead, we will realease the dataset with the following metadata for each language: tweet ids and the annotation labels. Below is an example of the dataset.

 tweetIDs | labels | 
--- | --- |
 1329755580903415808 | negative |
 1387857032523489280 | negative | 
 1177449493844787200 | positive | 
 1082503529007403008 | neutral | 

We will provide a script to allow hydrating all the tweets in our dataset. Check the [Github repository](https://github.com/afrisenti-semeval/afrisent-semeval-dataset) for more details.

## **Trial Data**

We provide a sample dataset for the shared task. Check the [Github repository](https://github.com/afrisenti-semeval/afrisent-semeval-dataset).
## **Baseline**

We provide baseline based on the following two papers: 

 1. Shamsuddeen Hassan Muhammad, David Ifeoluwa Adelani, Sebastian Ruder, Ibrahim Said Ahmad, Idris Abdulmumin, Bello Shehu Bello, Monojit Choudhury, Chris Chinenye Emezue, Saheed Salahudeen Abdullahi, Anuoluwapo Aremu, Alipio Jeorge, Pavel Brazdil. 2022, NaijaSenti: A Nigerian Twitter Sentiment Corpus for Multilingual Sentiment Analysis, Marseille, France
 2. Seid Muhie Yimam, Hizkiel Mitiku Alemayehu, Abinew Ayele, Chris Biemann. 2020: Exploring Amharic Sentiment Analysis from Social Media Texts: Building Annotation Tools and Classification Models, Barcelona, Spain (Online)

## **Submission Website**

We will be accepting and evaluating your submissions on [CodaLab](https://codalab.lisn.upsaclay.fr). The submission page will be available soon!


## **Evaluation**

We will use the AvgRec, Accuracy, and macro-average F1 measures for model evaluation. AvgRec, which provides results in a range of [0,1] favoured over standard accuracy because it is more robust to class imbalance (usually more natural classes than positive or negative as it can be seen in our Amharic dataset class distribution). Although accuracy reports the overall performance of the system, the F1 metric is calculated over the POSITIVE and the NEGATIVE classes exclusively.


## **Results**

The Evaluation phase of Afri-Senti-SemEval 2023 will start on January 10, 2023 and end on 31 January 2023. The Evaluation results and rankings will be notified in this page. We will list the usernames as they appear on CodaLab and the F1 score of your LAST submission. 


## **System Description Papers**

Participants who made a submission on the CodaLab website during the official evaluation period are given the opportunity to submit a system-description paper. The paper will be part of the SemEval-2023 proceedings. 

<style>
body {
text-align: justify}
</style>


<center>

#   **AfriSenti-SemEval Shared Task 12** 
AfriSenti-SemEval: Sentiment Analysis for Low-resource African Languages using Twitter Dataset

> Contact organizers at: [afrisenti-semeval-organizers@googlegroups.com](mailto:afrisenti-semeval-organizers@googlegroups.com)

> Join [Task Slack Channel](https://join.slack.com/t/afrisenti-semeval/shared_invite/zt-1fds98x1u-L3c~bpBI91IWRD80_Fy23Q) to communicate with the organizers.
</center>

---

## **Motivation**

Due to the widespread use of the Internet and social media platforms, most languages are becoming digitally available. This allows for various artificial
intelligence (AI) applications that enable tasks such as sentiment analysis, machine translation and hateful content detection. According to UNESCO (2003), 30% of all living languages, around 2,058, are African languages. However, most of these languages do not have curated datasets for developing such AI applications. Recently, various individual and funded initiatives, such as the Lacuna Fund, have set out to reverse
this trend and create such datasets for African languages. However, research is required to determine both the suitability of current natural language processing (NLP) techniques and the development of novel techniques to maximize the applications of such datasets.

There has been a growing interest in sentiment analysis which applies to many domains, including public health, commerce/business, art and literature, social sciences, neuroscience,
and psychology (<cite>Mohammad, Saif M, 2022</cite>). Previous shared tasks on sentiment analysis include <cite>Mohammad, Saif M et al., (2018), Nakov et al., (2016), Pontiki et al., Ghosh et al., (2015), (2014), and so on </cite> . However, none of these tasks included African languages. Though <cite> Mohammad, Saif, et al. (2018)</cite> included standard Arabic, we focus on Arabic dialects from African countries: <cite>Algerian Arabic</cite> and <cite>Tunisian Arabizi</cite>. We believe SemEval is the right venue, due to its popularity and widespread acceptance, to carry out shared tasks for African languages to strengthen their further development. 



In this shared task, we have covered 13 African languages, 4 languages from Nigeria ([Hausa](https://en.wikipedia.org/wiki/Hausa_language), [Yoruba](https://en.wikipedia.org/wiki/Yoruba_language), [Igbo](https://en.wikipedia.org/wiki/Igbo_language), [Nigerian Pigdin](https://en.wikipedia.org/wiki/Nigerian_Pidgin)), 2 from Ethiopia ([Amharic](https://en.wikipedia.org/wiki/Amharic) and [Tigrinya](https://en.wikipedia.org/wiki/Tigrinya_language)), [Swahili](https://en.wikipedia.org/wiki/Swahili_language) from Kenya and Tanzania,  [Algerian Arabic](https://en.wikipedia.org/wiki/Algerian_Arabic) dialect from Algeria, [Tunisian Arabizi](https://en.wikipedia.org/wiki/Tunisian_Arabic) from Tunisia, [Kinyarwanda](https://en.wikipedia.org/wiki/Kinyarwanda), [Twi](https://en.wikipedia.org/wiki/Twi) from Ghana, and 2 languages from South Africa ([isiZulu](https://en.wikipedia.org/wiki/Zulu_language), [Setswana](https://en.wikipedia.org/wiki/Tswana_language)). We are also working on adding more languages to the shared task.

## **Task Overview**


The **AfriSenti-SemEval Shared Task 12** is based on a collection of Twitter datasets in 13 African languages for sentiment classification. It consists of three sub-tasks. Participants can select one or more tasks depending on their preference. 

> **Task A: Monolingual Sentiment Classification**

> Given training data in a target language, determine the polarity of a tweet in the target language (positive, negative, or neutral). If a tweet 
For messages conveying both a positive and negative sentiment, whichever is the stronger sentiment should be chosen.

> **Task B: Multilingual Sentiment Classification**

Given a combined training data from 10 African languages, determine the polarity of a tweet in the target language (positive, negative, or neutral)

> **Task C: Zero-Shot Sentiment Classification**

Given unlabeled tweets in two African languages (Tigrinya and Kinyarwanda), leverage any or all of the available training datasets in Subtasks 1 and 2 to determine the sentiment of a tweet in the two target languages is positive, negative, or neutral.

## **Dataset Examples**

The dataset involves tweets labeled with three sentiment classes (positive, negative, neutral) in 12 African languages. Each tweet is annotated by three annotators following the annotation guidelines in (<cite>Mohammad, Saif M, 2016</cite>). We use a form of majority vote to determine the sentiment of the tweet. See more in our paper (<cite>Muhammad et al., 2022</cite>, <cite>Yimam et al., 2020</cite>). Below is a sample dataset for the 4 Nigerian languges (Muhammad et al., 2022):

![Dataset Example](dataset.png)

The datasets are available on [Github](https://github.com/afrisenti-semeval/afrisent-semeval-dataset)


## **Important Dates**


| Descriptions |  Deadlines |
| --- | --- |
| Sample Data Ready  | 15 July 2022 |
| Training Data Ready | 1 September 2022 |
| Evaluation Start  | 10 January 2023|
| Evaluation End  | 31 January 2023|
| System Description Paper Due |  February 2023  |
| Notification to authors   | March 2023   |
| Camera ready due   | April 2023  |
| SemEval workshop Summer 2023  |(co-located with a major NLP conference) | 

All deadlines are 23:59 UTC-12 ("anywhere on Earth").


## **Communication**

- Join [Task Mailing List](https://groups.google.com/g/afrisenti-semeval)
- Join [Task Slack Channel](https://join.slack.com/t/afrisenti-semeval/shared_invite/zt-1fds98x1u-L3c~bpBI91IWRD80_Fy23Q) to communicate with the organizers.
- Contact Organizers: [afrisenti-semeval-organizers@googlegroups.com](mailto:afrisenti-semeval-organizers@googlegroups.com)
## **Previous Shared Tasks**

1. Shared tasks in English:[SemEval-2017](https://alt.qcri.org/semeval2017/task4/),[SemEval-2016](https://alt.qcri.org/semeval2016/task4/),[SemEval-2015](https://alt.qcri.org/semeval2015/task10/),[SemEval-2014](https://alt.qcri.org/semeval2014/task9/),[SemEval-2013](https://aclanthology.org/S13-2052/)

2. Shared tasks in Spanish [TASS-2017](http://www.sepln.org/workshops/tass/2017/),[TASS-2016](http://www.sepln.org/workshops/tass/2016/tass2016.php),[TASS-2015](http://www.sepln.org/workshops/tass/2015/tass2015.php),[TASS-2014](http://www.sepln.org/workshops/tass/2014/tass2014.php),[TASS-2013](https://competitions.codalab.org/competitions/17751#learn_the_details-overview),[TASS-2012](http://www.sepln.org/workshops/tass/2012/tasks.php).


## References

   1. UNESCO. 2003. Sharing the world of difference. UNESCO.
   2. Mohammad, Saif M. "Ethics sheet for automatic emotion recognition and sentiment analysis." Computational Linguistics 48.2 (2022): 239-278.
   3. Preslav Nakov, Sara Rosenthal, Svetlana Kiritchenko, Saif M Mohammad, Zornitsa Kozareva, Alan Ritter, Veselin Stoyanov, and Xiaodan Zhu. 2016. Developing a successful SemEval task in sentiment analysis of twitter and other social media texts. Language Resources and Evaluation, 50(1):35–65.
   4. Mohammad, Saif, et al. "Semeval-2018 task 1: Affect in tweets." Proceedings of the 12th international workshop on semantic evaluation. 2018.
   5. Maria Pontiki, Dimitris Galanis, John Pavlopoulos, Harris Papageorgiou, Ion Androutsopoulos, Suresh Manandhar. 2014: SemEval-2014 Task 4: Aspect Based Sentiment Analysis, Dublin, Ireland
   6. Saif Mohammad. 2016. A Practical Guide to Sentiment Annotation: Challenges and Solutions. In Proceedings of the 7th Workshop on Computational Approaches to Subjectivity, Sentiment and Social Media Analysis, pages 174–179, San Diego, California. Association for Computational Linguistics.
   7. Aniruddha Ghosh, Guofu Li, Tony Veale, Paolo Rosso, Ekaterina Shutova, John Barnden, Antonio Reyes. 2015: SemEval-2015 Task 11: Sentiment Analysis of Figurative Language in Twitter, Denver, Colorado
   8. Shamsuddeen Hassan Muhammad, David Ifeoluwa Adelani, Sebastian Ruder, Ibrahim Said Ahmad, Idris Abdulmumin, Bello Shehu Bello, Monojit Choudhury, Chris Chinenye Emezue, Saheed Salahudeen Abdullahi, Anuoluwapo Aremu, Alipio Jeorge, Pavel Brazdil. 2022, NaijaSenti: A Nigerian Twitter Sentiment Corpus for Multilingual Sentiment Analysis, Marseille, France
   9. Seid Muhie Yimam, Hizkiel Mitiku Alemayehu, Abinew Ayele, Chris Biemann. 2020: Exploring Amharic Sentiment Analysis from Social Media Texts: Building Annotation Tools and Classification Models, Barcelona, Spain (Online)


<style>
body {
text-align: justify}
</style>


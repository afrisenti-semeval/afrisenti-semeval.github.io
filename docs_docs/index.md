<center>

#   **AfriSenti-SemEval Shared Task 12** 
AfriSenti-SemEval: Sentiment Analysis for Low-resource African Languages using Twitter Dataset

> [afrisenti-semeval@googlegroups.com](afrisenti-semeval@googlegroups.com)
</center>
---

## **Motivation**

Due to the widespread use of the Internet and social media platforms, most languages are becoming digitally available. This allows for various artificial
intelligence (AI) applications that enable tasks such as sentiment analysis, machine translation, hateful content detection, among others. According to UNESCO (2003), 30% of all living languages, around 2,058, are African languages. However, most of these languages do not have curated datasets for developing such AI applications. Recently, various individual and funded initiatives, such as the Lacuna Fund, have set out to reverse
this trend and create such datasets for African languages. However, research is required to determine both the suitability of current natural language processing (NLP) techniques and the development of novel techniques to maximize the applications of such datasets. We believe that SemEval is the right venue, due to its popularity and widespread acceptance, to carry out shared tasks in these African languages to strengthen their further development.

In this shared task, we have covered 13 African languages, namely 4 languages from Nigeria ([Hausa](https://en.wikipedia.org/wiki/Hausa_language), [Yoruba](https://en.wikipedia.org/wiki/Yoruba_language), [Igbo](https://en.wikipedia.org/wiki/Igbo_language), [Nigerian Pigdin](https://en.wikipedia.org/wiki/Nigerian_Pidgin)), 2 from Ethiopia ([Amharic](https://en.wikipedia.org/wiki/Amharic) and [Tigrinya](https://en.wikipedia.org/wiki/Tigrinya_language)), [Swahili](https://en.wikipedia.org/wiki/Swahili_language) from Kenya and Tanzania,  [Algerian Arabic](https://en.wikipedia.org/wiki/Algerian_Arabic) dialect from Algeria, [Tunisian Arabizi](https://en.wikipedia.org/wiki/Tunisian_Arabic) from Tunisia, [Kinyarwanda](https://en.wikipedia.org/wiki/Kinyarwanda), [Twi](https://en.wikipedia.org/wiki/Twi) from Ghana, and 2 languages from South Africa ([isiZulu](https://en.wikipedia.org/wiki/Zulu_language), [Setswana](https://en.wikipedia.org/wiki/Tswana_language)). We are also working on adding more languages to the shared task.



## **Task Overview**

Previous shared tasks on different aspects of sentiment analysis includes <cite>Nakov et al., (2016), Pontiki et al., (2014), Ghosh et al., (2015)</cite> and so on. However, none of these tasks have covered African languages. The AfriSenti-SemEval shared task is based on a collection of Twitter datasets in 12 African languages for sentiment classification.

The **AfriSenti-SemEval Shared Task 12** consists of three sub-tasks. Participants can select one or more tasks depending on their preference. 

> **Task A: Monolingual Sentiment Classification**

> Given training data in a target language, determine whether an instance of tweet in that language is positive, negative, or neutral

> **Task B: Sentiment  Multilingual Sentiment Classification**

Given a combined training data from 10 African languages, determine whether a tweet instance in any of the given languages is positive, negative, or neutral.

> **Task C: Zero-Shot Sentiment Classification**

Given unlabeled tweets in two African languages (Tigrinya and Kinyarwanda), leverage any or all of the available training datasets in Subtasks 1 and 2 to determine whether an instance of a tweet in the two target languages is positive, negative, or neutral.

## **Dataset Examples**

The dataset involves tweets labeled with three sentiment classes (positive, negative, neutral) in 12 African languages. Each tweet is annotated by three annotators. We use a form of majority vote to determine the sentiment of the tweet. See more in our paper (<cite>Muhammad et al., 2022</cite>, <cite>Yimam et al., 2020</cite>).
 Below is a sample dataset for the 4 Nigerian languges (Muhammad et al., 2022):

![Dataset Example](dataset.png)

The datasets are available on [Github](https://github.com/afrisenti-semeval/afrisent-semeval-dataset)


## **Important Dates**


| Descriptions |  Deadlines |
| --- | --- |
| Sample Data Ready  | 15 July 2022 |
| Training Data Ready | 1 September 2022 |
| Evaluation Start  | 10 January 2023|
| Training Data Ready | 1 September 2022 |
| System Description Paper Due |  February 2023  |
| Notification to authors   | March 2023   |
| Camera ready due   | April 2023  |
| SemEval workshop Summer 2023  |(co-located with a major NLP conference) | 



## **Communication**

- [Task Mailing List](afrisenti-semeval@googlegroups.com) 
- Join [Masakhane's](https://www.masakhane.io) [Slack](https://join.slack.com/t/masakhane-nlp/shared_invite/zt-1cg72ed5u-01xYqGd1MdXcbSEvZ435YA) and join #Afrisenti channel to communicate with other participants.
- If you are attending Deep Indaba2022, we will present a poster. Come and chat with us more about the task.


## References

   1. UNESCO. 2003. Sharing the world of difference. UNESCO.
   2. Preslav Nakov, Sara Rosenthal, Svetlana Kiritchenko, Saif M Mohammad, Zornitsa Kozareva, Alan Ritter, Veselin Stoyanov, and Xiaodan Zhu. 2016. Developing a successful SemEval task in sentiment analysis of twitter and other social media texts. Language Resources and Evaluation, 50(1):35–65.
   3. Maria Pontiki, Dimitris Galanis, John Pavlopoulos, Harris Papageorgiou, Ion Androutsopoulos, Suresh Manandhar. 2014: SemEval-2014 Task 4: Aspect Based Sentiment Analysis, Dublin, Ireland
   4. Aniruddha Ghosh, Guofu Li, Tony Veale, Paolo Rosso, Ekaterina Shutova, John Barnden, Antonio Reyes. 2015: SemEval-2015 Task 11: Sentiment Analysis of Figurative Language in Twitter, Denver, Colorado
   5. Shamsuddeen Hassan Muhammad, David Ifeoluwa Adelani, Sebastian Ruder, Ibrahim Said Ahmad, Idris Abdulmumin, Bello Shehu Bello, Monojit Choudhury, Chris Chinenye Emezue, Saheed Salahudeen Abdullahi, Anuoluwapo Aremu, Alipio Jeorge, Pavel Brazdil. 2022, NaijaSenti: A Nigerian Twitter Sentiment Corpus for Multilingual Sentiment Analysis, Marseille, France
   6. Seid Muhie Yimam, Hizkiel Mitiku Alemayehu, Abinew Ayele, Chris Biemann. 2020: Exploring Amharic Sentiment Analysis from Social Media Texts: Building Annotation Tools and Classification Models, Barcelona, Spain (Online)


<style>
body {
text-align: justify}
</style>


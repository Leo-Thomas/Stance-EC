# Stance-EC: A Spanish-language Data Set on Polarized Twitter Conversations About the 2022 Protests in Ecuador

<!-- ABOUT THE PROJECT -->
## About the project

Social networks have become one of the most important channels allowing people to share their thoughts and opinions on various topics. Among these, Twitter is the primary medium for debates on different topics, including socio-political aspects. There is a growing research interest in detecting stances in these contexts. However, a large amount of information and the lack of reliable data sets make it challenging to recognize social network users' feelings and emotions accurately. Furthermore, the number of data sets in English for stance detection is large, but to our knowledge, they are limited in Spanish. This paper presents a new data set in Spanish for stance detection on the 2022 protests in Ecuador. This event was significant national and international relevance since the country experienced several days of chaos. It was also the subject of extensive discussion on Twitter between the different sides supporting and opposing the protests. The tweets were downloaded through the Twitter API, obtaining 232,609 tweets after deduplication. A random sample of 25,454 tweets was selected and manually annotated by five people. Both the annotated and non-annotated data sets are publicly available. The results showed that our data set is rich in important information from Twitter discussions about the event. Also, machine learning classifiers were trained and evaluated on the annotated data set. The classifiers showed good overall performance in training and validation, and no excessive overfitting was observed, demonstrating that the data set is reliable and valuable for future research.

This project was developed by Leo Ramos, Mike Bermeo, students, Silvana Escobar, Diego Morales, and Erick Cuenca, professors, at [Yachay Tech University](https://www.yachaytech.edu.ec/en/).

<!-- GETTING STARTED -->
## Installation

pip install git+https://github.com/Leo-Thomas/Stance-EC

## Description of the main files

- [Paro_tweets_Annotated.rar](Paro_tweets_Annotated.rar): Compressed file of labeled tweets
- [Paro_tweets_NoAnnotated.rar](Paro_tweets_NoAnnotated.rar): Compressed file of unlabeled tweets

## Data set description

Two data sets are provided, one annotated and one non-annotated. The distribution of these is as follows:

| Data set        | Amount   |
|----------------|----------|
| Annotated       | 25,454   |
| Non-annotated   | 207,155  |
| Total           | 232,609  |

Regarding the annotated data set, it was categorized manually. Each tweet was assigned to one of three categories, which are:

* **Favor (F)** This label alludes to tweets that express a position of support, directly or indirectly, for the execution and continuation of the protests.
* **Against (A)** This label refers to tweets that express a position of support, directly or indirectly, to the non-execution of the strike and its immediate termination.
* **Neutral (N)** The tweets in this category do not support or oppose the strike. These tweets contain general information about the strike.

The percentage distribution of tweets from the annotated data set according to each stance category is as follows:

| Label    | Amount  | Percent (\%) |
|----------|---------|--------------|
| Favor    | 6,756   | 26.54        |
| Against  | 7,066   | 27.76        |
| Neutral  | 11,632  | 45.70        |
| Total    | 25,454  | 100          |

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Mike bermeo - [LinkedIn](https://www.linkedin.com/in/mike-bermeo/) - mike.bermeos@yachaytech.edu.ec

Silvana Escobar - [LinkedIn](https://www.linkedin.com/in/silvanakescobar/) - sescobar@yachaytech.edu.ec

Diego Morales - [LinkedIn](https://www.linkedin.com/in/diego-fabi%C3%A1n-morales-navarrete-2764802a/) - dmorales@yachaytech.edu.ec

Erick Cuenca - [LinkedIn](https://www.linkedin.com/in/erickcuenca/) - ecuenca@yachaytech.edu.ec

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - leo.ramos@yachaytech.edu.ec

<br>
<br>


<p align="right">(<a href="#top">back to top</a>)</p>

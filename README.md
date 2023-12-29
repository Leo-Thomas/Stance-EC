# Stance-EC: A Spanish-language Dataset of Political Discourse on Twitter for Stance Detection

<!-- ABOUT THE PROJECT -->
## About the project

Stance detection is a task in natural language processing that involves identifying and categorizing opinions in text. It has various applications, such as improving our understanding of socio-political discussions and informing market analysis. Social media, especially Twitter, is crucial for social discourse. However, using Twitter for stance detection faces a significant challenge: the lack of reliable language-specific datasets. While English datasets for stance detection are prevalent, Spanish-language resources remain limited. In this paper, we present Stance-EC, a new Spanish-language dataset for stance detection. We aim to provide a valuable resource with polarized content, focusing on the 2022 Ecuador protests as our primary data source. This event, which sparked extensive debate on Twitter, was marked by a high degree of polarization, showcasing diverse viewpoints from supporters and opponents. Utilizing Twitter's API, we downloaded tweets relevant to the event using specific hashtags. After deduplication, we obtained a corpus of 232,609 tweets, from which a random sample of 25,454 was selected for manual annotation. Tweets were categorized as `favor', `against', or `neutral' towards the protest, totaling 6,756, 7,066, and 11,632 in each category. We used machine learning classifiers including Random Forest, SVM, Logistic Regression, Decision Tree, CatBoost, XGBoost, and LightGBM for unigram and bigram analysis, to test the dataset's capability, evaluating performance with Accuracy, Precision, Recall, and F1-score. Results showed strong performance across all metrics, typically around 70% for both unigrams and bigrams, and even exceeding 80% in LightGBM with unigrams, without excessive overfitting, highlighting the dataset's reliability for future research.

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

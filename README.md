<h1>Eesti alamredditi korpuse loomine ning analüüs</h1>
<p>Autor: <b>Tauno Tamm</b></p>
<p>Juhendaja: <b>Siim Orasmaa, PhD</b></p>
<h3>Lühikokkuvõte:</h3>
<p align="justify">Reddit on maailma suurim foorum, mida jälgib igakuiselt umbes 1.2 miljardit kasutajat. Eesti suurimaks subreddit-iks ehk alamredditiks on r/Eesti. Selle magistritöö käigus loodi r/Eesti andmete põhjal keelekorpus ning analüüsiti seal olevaid andmeid. Analüüsi käigus vastati järgnevatele uurimisküsmustele: kuidas ja millal postitatakse ning millest postitatakse. Uurimisküsimustele vastamiseks peenhäälestati ning kasutati erinevaid transformer-tüüpi mudeleid tundmusanalüüsi läbiviimiseks, Pythoni keeletuvastuse teeki Lingua keeletuvastuseks, teemade analüüsiks BERTopic-ut jpm. Tulemustest selgus, et r/Eesti alamredditit võib pidada kakskeelseks, sest lisaks eesti keelele on suur osa postitusi ning kommentaare tehtud ka inglise keeles.</p>

<img src="https://raw.githubusercontent.com/taunotamm/DS_MSc_Thesis/main/media/abstract/Tauno_Tamm_abstrakt_v2_ET.jpg" width="100%">

<h3>Failid kaustas "code":</h3>
<ul>
  <li><b>corpus.ipynb</b> - korpuse loomine;</li>
  <li><b>comparison_EKÜ.ipynb</b> - andmestiku kattuvuse võrdlus eesti keele ühendkorpusega;</li>
  <li><b>overall_data_analysis.ipynb</b> - üldine andmetel põhinev analüüs;</li>
  <li><b>lang_detect.ipynb</b> - keeletuvastuse proovimine ja rakendamine; sisaldab ka üldist andmetel põhineva analüüsi osi;</li>
  <li><b>Est_RoBERTa_train.ipynb</b> - eestikeelse RoBERTa mudeli peenhälestamine;</li>
  <li><b>ENG_model_test.ipynb</b> - ingliskeelsete mudelite soorituste hindamine tundmusanalüüsi jaoks;</li>
  <li><b>sentiment.ipynb</b> - tundmusanalüüsi mudelite rakendamine. Inglise keele puhul võrreldakse kahe mudeli sooritust;</li>
  <li><b>sentiment_BERTopic.ipynb</b> - tundmusanalüüsi rakendamine koos teemade analüüsiga (BERTopic).</li>
</ul>
<hr>

<h1>Creation and Analysis of the Estonian Subreddit Corpus</h1>
<p>Author: <b>Tauno Tamm</b></p>
<p>Supervisor: <b>Siim Orasmaa, PhD</b></p>
<h3>Abstract:</h3>
<p align="justify">Reddit is the world's largest forum, visited by about 1.2 billion users monthly. The largest Estonian subreddit is r/Eesti. This master's thesis involved creating a language corpus based on the data from r/Eesti and analyzing the data therein. The analysis addressed questions on how and when posts are made and what they discuss. For answering these research questions, various transformer-type models were fine-tuned for sentiment analysis, the Python language detection library Lingua was used for language detection, and BERTopic was employed for topic analysis. The results revealed that the r/Eesti subreddit can be considered bilingual, as a significant portion of posts and comments are also in English.</p>

<img src="https://raw.githubusercontent.com/taunotamm/DS_MSc_Thesis/main/media/abstract/Tauno_Tamm_abstrakt_v2_EN.jpg" width="100%">

<h3>Files in the "code" folder:</h3>
<ul>
  <li><b>corpus.ipynb</b> - creating the corpus;</li>
  <li><b>comparison_EKÜ.ipynb</b> - comparing dataset overlap with the Estonian Joint Corpus;</li>
  <li><b>overall_data_analysis.ipynb</b> - general data-based analysis;</li>
  <li><b>lang_detect.ipynb</b> - trying and applying language detection; also includes parts of general data-based analysis;</li>
  <li><b>Est_RoBERTa_train.ipynb</b> - fine-tuning the Estonian RoBERTa model;</li>
  <li><b>ENG_model_test.ipynb</b> - evaluating the performance of English models for sentiment analysis;</li>
  <li><b>sentiment.ipynb</b> - applying sentiment analysis models. In English, performance of two models is compared;</li>
  <li><b>sentiment_BERTopic.ipynb</b> - applying sentiment analysis combined with topic analysis (BERTopic).</li>
</ul>

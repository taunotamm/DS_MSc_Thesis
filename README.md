<h1>Eesti alamredditi korpuse loomine ning analüüs</h1>
<p>Autor: <b>Tauno Tamm</b></p>
<p>Juhendaja: <b>Siim Orasmaa, PhD</b></p>
<h3>Lühikokkuvõte:</h3>
<p align="justify">Reddit on maailma suurim foorum, mida jälgib igakuiselt umbes 1.2 miljardit kasutajat. Eesti suurimaks subreddit-iks ehk alamredditiks on r/Eesti. Selle magistritöö käigus loodi r/Eesti andmete põhjal keelekorpus ning analüüsiti seal olevaid andmeid. Analüüsi käigus vastati järgnevatele uurimisküsmustele: kuidas ja millal postitatakse ning millest postitatakse. Uurimisküsimustele vastamiseks peenhäälestati ning kasutati erinevaid siirdeõppe mudeleid tundmusanalüüsi läbiviimiseks, Pythoni keeletuvastuse teeki Lingua keeletuvastuseks, teemade analüüsiks BERTopic-ut jpm. Tulemustest selgus, et r/Eesti alamredditit võib pidada kakskeelseks, sest lisaks eesti keelele on suur osa postitusi ning kommentaare tehtud ka inglise keeles. Tundmusanalüüs näitas, et eesti keeles postitavad ja kommenteerivad kasutajad on tugevalt negatiivselt meelestatud, kuid inglise keeles kirjutavad kasutajad on tugevalt neutraalselt meelestatud, olles pigem positiivse tundmuse poole kaldu. Mõlema keele puhul on kõige populaarsemaks ühtivaks teemaks „Haridus“.</p>

<img src="https://raw.githubusercontent.com/taunotamm/DS_MSc_Thesis/main/media/graphical_abstract/Tauno_Tamm_abstrakt_v2_ET.jpg" width="100%">

<h3>Failid kaustas "code":</h3>
<ul>
  <li><b>corpus.ipynb</b> - korpuse loomine;</li>
  <li><b>comparison_EKÜ.ipynb</b> - andmestiku kattuvuse võrdlus eesti keele ühendkorpusega;</li>
  <li><b>overall_analysis.ipynb</b> - üldine andmetel põhinev analüüs;</li>
  <li><b>lang_detect.ipynb</b> - keeletuvastuse proovimine ja rakendamine; sisaldab ka üldist andmetel põhineva analüüsi osi;</li>
  <li><b>estRoBERTa_train.ipynb</b> - eestikeelse RoBERTa mudeli peenhälestamine; osaliselt tugineti sellele tööle: https://github.com/LisannaL/Thesis_MSc/tree/main</li>
  <li><b>ENG_model_test.ipynb</b> - ingliskeelsete mudelite soorituste hindamine tundmusanalüüsi jaoks;</li>
  <li><b>EN_sentiment_model_comparison.ipynb</b> - Inglise keele tundmusanalüüsi mudelite soorituste võrdlus;</li>
  <li><b>sentiment_BERTopic.ipynb</b> - tundmusanalüüsi rakendamine koos teemade analüüsiga (BERTopic).</li>
</ul>

<h3>Failid kaustas "media":</h3>
<ul>
  <li><b>comments_en.PNG</b> - ingliskeelsete postituste kommentaaride tundmuse jaotus üle teemade;</li>
  <li><b>comments_et.PNG</b> - eestikeelsete postituste kommentaaride tundmuse jaotus üle teemade;</li>
  <li><b>post_en.PNG</b> -  ingliskeelsete postituste tundmuse jaotus üle teemade;</li>
  <li><b>posts_et.PNG</b> - eestikeelsete postituste tundmuse jaotus üle teemade;</li>
</ul>

<hr>

<h1>Creation and Analysis of the Estonian Subreddit Corpus</h1>
<p>Author: <b>Tauno Tamm</b></p>
<p>Supervisor: <b>Siim Orasmaa, PhD</b></p>
<h3>Abstract:</h3>
<p align="justify">Reddit is the world's largest forum, visited by about 1.2 billion users monthly. The largest Estonian subreddit is r/Eesti. This master's thesis involved creating a language corpus based on the data from r/Eesti and analyzing the data therein. The analysis addressed questions on how and when posts are made and what they discuss. For answering these research questions, various transformer-type models were fine-tuned for sentiment analysis, the Python language detection library Lingua was used for language detection, and BERTopic was employed for topic analysis. The results revealed that the r/Eesti subreddit can be considered bilingual, as a significant portion of posts and comments are also in English. The sentiment analysis exhibited that users posting and commenting in Estonian are mostly negative, while those who write in English tend to be neutral, with a slight lean towards positivity. In both languages, “Education” is the most common topic.</p>

<img src="https://raw.githubusercontent.com/taunotamm/DS_MSc_Thesis/main/media/graphical_abstract/Tauno_Tamm_abstrakt_v2_EN.jpg" width="100%">

<h3>Files in the "code" folder:</h3>
<ul>
  <li><b>corpus.ipynb</b> - creating the corpus;</li>
  <li><b>comparison_EKÜ.ipynb</b> - comparing dataset overlap with the Estonian Joint Corpus;</li>
  <li><b>overall_analysis.ipynb</b> - general data-based analysis;</li>
  <li><b>lang_detect.ipynb</b> - trying and applying language detection; also includes parts of general data-based analysis;</li>
  <li><b>estRoBERTa_train.ipynb</b> - fine-tuning the Estonian RoBERTa model; This code was partially based on: https://github.com/LisannaL/Thesis_MSc/tree/main</li>
  <li><b>ENG_model_test.ipynb</b> - evaluating the performance of English models for sentiment analysis;</li>
  <li><b>EN_sentiment_model_comparison.ipynb</b> - performance comparison of the English language sentiment analysis models;</li>
  <li><b>sentiment_BERTopic.ipynb</b> - applying sentiment analysis combined with topic analysis (BERTopic).</li>
</ul>

<h3>Files in the "media" folder:</h3>
<ul>
  <li><b>comments_en.PNG</b> - distribution of sentiment in comments on English posts across topics;</li>
  <li><b>comments_et.PNG</b> - distribution of sentiment in comments on Estonian posts across topics;</li>
  <li><b>post_en.PNG</b> - distribution of sentiment in English posts across topics;</li>
  <li><b>posts_et.PNG</b> - distribution of sentiment in Estonian posts across topics;</li>
</ul>

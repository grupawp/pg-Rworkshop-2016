# pg-Rworkshop-2016
Warsztaty z R dla średniozaawansowanych na Politechnice Gdańskiej

- Organizatorzy: [@pcejrowski](https://github.com/pcejrowski), [proszę dopisać swój nick]
- Prowadzący: [@MarcinKosinski](https://github.com/MarcinKosinski)

Strona warsztatu http://grupawp.github.io/pg-Rworkshop-2016/


Ramowy plan warsztatu

- 9:00-9:15/9:20 - [Prezentacja] Paweł Cejrowski - Istota Data Science
- 9:20-9:40 - [Prezentacja] Marcin Kosiński - Po co przyszliśmy na warsztat: co wiemy o R i analizie danych?
- 9:40-10:00 - [Prezentacja/Life-coding] Marcin Kosiński - Omówienie danych wraz z ich przygotowaniem w `dplyr`
- 10:00-10:30 - [Prezentacja/Life-coding] Marcin Kosiński - Omówienie podstaw uczenia statystycznego na przykładzie klasyfikacji wykorzystującej podstawowy algorytm na danych wybranych do warsztatu.
- 10:30-10:35 - Omówienie przygotowanych materiałów
- 10:35-12:00 - Praca w zespołach nad analiza danych i klasyfikacją z wykorzystanie algorytmów omówionych w przygotowanych materiałach. Prośba o prowadzenie analizy w plikach `.Rmd`. 6 pięcioosobowych zespołów.
- 12:00-12:30 - [Prezentacja zespołów] - PIZZA, w trakcie której zespoły opowiedzą [każdy zespół 5 min]:
    - jaki algorytm wybrały
    - na czym polega algorytm
    - jakie są postępy
    - jakie zmienne wybrano do analizy
    - jakie są dalsze plany na anlizę
- 12:30-13:45 - Praca w zespołach nad analiza danych i klasyfikacją z wykorzystanie algorytmów omówionych w przygotowanych materiałach. Prośba o prowadzenie analizy w plikach `.Rmd`. 6 pięcioosobowych zespołów. 
- 13:45-14:00 - Ostateczne 2minutowe prezentacje + sklejenie plików `.Rmd` w jedną stronę HTML.
- 14:00-14:15 - Zakończenie warsztatu i konsultacje.


## [Proponowane zbiory danych - ostatecznie zostaniemy przy jednym](https://archive.ics.uci.edu/ml/datasets.html)

- [Internet Advertisements Data Set](https://archive.ics.uci.edu/ml/datasets/Internet+Advertisements) - This dataset represents a set of possible advertisements on Internet pages. The features encode the geometry of the image (if available) as well as phrases occuring in the URL, the image's URL and alt text, the anchor text, and words occuring near the anchor text. The task is to predict whether an image is an advertisement ("ad") or not ("nonad"). **Wymiary:** 3279 X 1558
- [Multiple Features Data Set](https://archive.ics.uci.edu/ml/datasets/Multiple+Features) - This dataset consists of features of handwritten numerals (`0'--`9') extracted from a collection of Dutch utility maps. 200 patterns per class (for a total of 2,000 patterns) have been digitized in binary images. **Wymiary:** 2000 X 649
- [p53 Mutants Data Set](https://archive.ics.uci.edu/ml/datasets/p53+Mutants) - Biophysical models of mutant p53 proteins yield features which can be used to predict p53 transcriptional activity. All class labels are determined via in vivo assays. **Wymiary:** 16772 X 5409
- [The Cancer Genome Atlas Project Data - Breast Cancer](http://gdac.broadinstitute.org/) - Clinical information, genes mutations and expressions for patients suffering from Breast Carcinoma. **Wymiary:** ~900 X ~22 tysiące
- [Free data set for very high dimensional classification](http://stats.stackexchange.com/questions/973/free-data-set-for-very-high-dimensional-classification) - stackoverflow propositions

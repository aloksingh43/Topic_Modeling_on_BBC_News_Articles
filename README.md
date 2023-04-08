# Topic_Modeling_on_BBC_News_Articles
⏺ The dataset contains a set of news articles for each major segment consisting of business, entertainment, politics, sports and technology. You need to create an aggregate dataset of all the news articles and perform topic modeling on this dataset. Verify whether these topics correspond to the different tags available.

BBC News is an operational business division of the British Broadcasting Corporation (BBC) responsible for the gathering and broadcasting of news and current affairs in the UK and around the world. The department is the world's largest broadcast news organisation and generates about 120 hours of radio and television output each day, as well as online news coverage. The service maintains 50 foreign news bureaus with more than 250 correspondents around the world.

The Data provided is divided into 5 categories, that are, Sports, Tech, Business, Entertainment and Politics. Across these folders the data is stored in form of text files such that each text file contains the complete transcript of the article. The dataset in this case isn't collective, it has been stored in form of numerous text files sub-categorized in 5 different domains. The first task is to segregate the data which can be achieved by traversing all these folders and storing the data in the files to a data-frame. For loading the data we'll visit all text files individually and copy all articles to a dataframe along with their category.

Steps Involved

1-Data Collection

2-EDA

3-Removing punctuations

4-Removeing stopwords

5-Feature Extraction

6-Model Development(LDA)

7- Topic visualization(pyLDAvis)


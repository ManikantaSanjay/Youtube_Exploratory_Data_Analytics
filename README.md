# Youtube_Exploratory_Data_Analytics
This is a Mini Project made using Python Libraries to perform Data Analytics on US Youtube Videos and Comments dataset. 
### Libraries Used :
i> Pandas

ii> NumPy

iii> Mathplotlib

iv> Seaborn

v> Warnings

vi> WordCloud

vii> TextBlob

viii> Emoji

ix> PlotLy

### Description :
This Project mainly contains performing three tasks namely :
##### -> Sentiment Analysis of Youtube Comments :
By making use of the sentiment polarity function of the TextBlob , we classsify the sentences into positive sentences (polarity is equal to 1) and negative sentences (polarity is equal to 0) and we make use of wordcloud module to generate a wordcloud denoting 
the most frequency words in the particular sentence.
##### -> Analysing Tags Column :
We try to find the most trending tags on youtube by making use of the wordcloud module and generating a wordcloud depicting the most occuring tags in the videos dataset.
We also try to find the correlation between likes v/s views and the dislikes v/s views and finally finding the correlation between all the three, i.e likes,dislikes and views by using a correlation matrix.
##### -> Analysing Emojis in Comments :
We create a dictionary having the emojis along with its frequency and create a dataframe for the 20 most used emojis in the comments dataset. Now we make use of the Plotly module and plot a graph for the same relation i.e Emoji v/s Frequency of the same.

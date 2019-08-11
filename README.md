Named Entity Recognition With Spacy Package

In my previous post https://opokualbert.com/post.html#ner, I showed how you can get the entities in an article or any text documents using Natural language processing NER Package by Stanford NLP.  In this post I will share how to do this in a few lines of code in Spacy and compare the results from the two packages.
Named entity recognition is using natural language recognition to pull out all entities like a person, organization, money, geo location, time and date from an article or documents . These packages use part of speech tagging to identify which entity a word in the article should be assigned to.
As I indicated in the previous post this is useful if you quickly need to gather the specific salient information about a very long document, example who contacted who at what time and at what place; and which organization do they work for or are they discussing? Was money involved in the dealings and how much?
It turns out spacy is fast and also require few line of code but the results is more accurate compared to  Stanford NLP NER. Spacy also gives additional methods to describe or explain what the labels represent. And if you so desire, you can also visualize the entities in the text document.

For comparison purposes, I will use the same text I used in the earlier post. The text is  from this article from techrunch. [African fintech dominates Catalyst Fund’s 2019 startup cohort](https://techcrunch.com/2019/06/21/african-fintech-dominates-catalyst-funds-2019-startup-cohort/)

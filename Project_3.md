# Document Classification with CNN
In this project, I used a convolutional neural network (CNN) to classify documents based on their content. The dataset used was the IMDB movie review dataset, and the goal was to predict whether a review was positive or negative.

Data ¶
1. we have total of 20 types of documents(Text files) and total 18828 documents(text files).
2. You can download data from this link (https://drive.google.com/open?id=1rxD15nyeIPIAZ-J2VYPrDRZI66-T
BWvM), in that you will get documents.rar folder.
If you unzip that, you will get total of 18828 documnets. document name is defined as'ClassLabel_Docume
ntNumberInThatLabel'.
so from document name, you can extract the label for that document.
4. Now our problem is to classify all the documents into any one of the class.
5. Below we provided count plot of all the labels in our data.


1. Find all emails in the document and then get the text after the "@". and then split those texts by
'.'
after that remove the words whose length is less than or equal to 2 and also remove'com' word and then
combine those words by space.
In one doc, if we have 2 or more mails, get all.
Eg:[test@dm1.d.com, test2@dm2.dm3.com]-->[dm1.d.com, dm3.dm4.com]-->[dm1,d,com,dm2,dm3,com]-->[dm1,dm2,
dm3]-->"dm1 dm2 dm3"
append all those into one list/array. ( This will give length of 18828 sentences i.e one list for each
of the document).
Some sample output was shown below.
> In the above sample document there are emails [jcopelan@nyx.cs.du.edu, 65882@mimsy.umd.edu, mangoe@c
s.umd.edu]
preprocessing:
[jcopelan@nyx.cs.du.edu, 65882@mimsy.umd.edu, mangoe@cs.umd.edu] ==> [nyx cs du edu mimsy umd edu cs um
d edu] ==>
[nyx edu mimsy umd edu umd edu]
2. Replace all the emails by space in the original text.

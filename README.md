## **Created By -** <br/>
   # <font color=red>**Dharmendra Choudhary**</font>  
    
   ## <font color=red>**VIT university,Vellore,Tamil Nadu,India**</font>
[1.1]: https://i.imgur.com/IbLg2tB.png?2 (twitter click here)
[1.2]: https://i.imgur.com/huhwaQ2.png?2 (facebook click here)
[1.3]: https://i.imgur.com/gXipWFn.png?2 (github click here)
[1.4]: https://i.imgur.com/4Y1X4Eo.png?2 (gitlab click here)
[1]: https://twitter.com/dammonoit
[2]: https://www.facebook.com/profile.php?id=100022695248450
[3]: https://github.com/Dammonoit
[4]: https://gitlab.com/Dammonoit

 ## **Follow me on:-** [![Twitter][1.1]][1] [![Facebook][1.2]][2]  [![Github][1.3]][3] [![Gitlab][1.4]][4]
 <br/>
## **What is Word Sense Disambiguation?**
* In the 1970s, WSD was a subtask of semantic interpretation systems developed within the field of artificial intelligence, starting with Wilks' preference semantics.
* WSD has been a trending area of research in Natural Language Processing and Machine Learning. WSD is basically solution to the ambiguity which arises due to different meaning of words in different context.
* For example, consider the two sentences.
“The bank will not be accepting cash on Saturdays. ”
“The river overflowed the bank.”

The word bank in the first sentence refers to the commercial (finance) banks, while in second sentence, it refers to the river bank. The ambiguity that arises due to this, is tough for a machine to detect and resolve. Detection of ambiguity is the first issue and resolving it and displaying the correct output is the second issue.
* The algorithm that we’ll be using for review analysis is the classic Lesk Algorithm.
* The Lesk algorithm is a classical algorithm for word sense disambiguation introduced by Michael E. Lesk in 1986.
* The Lesk algorithm is based on the assumption that words in a given "neighborhood" (section of text) will tend to share a common topic.
* A frequently used example illustrating this algorithm is for the context "pine cone". The following dictionary definitions are used:
PINE 
1. kinds of evergreen tree with needle-shaped leaves
2. waste away through sorrow or illness
CONE 
1. solid body which narrows to a point
2. something of this shape whether solid or hollow
3. fruit of certain evergreen trees
As can be seen, the best intersection is Pine #1 ⋂ Cone #3 = 2.
* In Simplified Lesk algorithm,the correct meaning of each word in a given context is determined individually by locating the sense that overlaps the most between its dictionary definition and the given context. 
* Rather than simultaneously determining the meanings of all words in a given context, this approach tackles each word individually, independent of the meaning of the other words occurring in the same context.

## **What is Text Summarization**?
* Text Summarization is one of those applications of Natural Language Processing (NLP) which is bound to have a huge impact on our lives. With growing digital media and ever growing publishing – who has the time to go through entire articles / documents / books to decide whether they are useful or not? Thankfully – this technology is already here.
* Text summarization can broadly be divided into two categories — **Extractive Summarization** and **Abstractive Summarization**.
  * **Extractive Summarization:** These methods rely on extracting several parts, such as phrases and sentences, from a piece of text and stack them together to create a summary. Therefore, identifying the right sentences for summarization is of utmost importance in an extractive method.
  * **Abstractive Summarization:** These methods use advanced NLP techniques to generate an entirely new summary. Some parts of this summary may not even appear in the original text.
* In this project i used a algorithm called **TextRank** Algorithm which is developed from motivation of **PageRank** Algorithm used by google for indexing webpages.
* The Architecture of this Algo. is:
* ![TextRank](https://i.imgur.com/hxo6JYs.png)
* [Click here](https://www.analyticsvidhya.com/blog/2018/11/introduction-text-summarization-textrank-python/) for more description on TextRank Algorithm.

## **For opinion mining i'll be using Logistic Regression,Naive Bayes Classifier including Gaussian,Multnomial and Bernoulli Distribution Methods.**

## **What's new?**
* Although all this components/modules did exists before in theory may not be in execution but what i did new is combining them in form of motivation to solve existing problem more efficiently .
* Since, we know this entire fuss of datascience wouldn't have existed if we didn't want to solve problem but when we talk about language aspects in datascience, we couldn't help but to think about NLP(Natural language processing) whom i used to for context resolution in this project. I trusted NLP over Artificial-NN in this project which already has been and had been implemented numerous time to solve this current problem to language in-accuracy and believe me it this problem is so severe that it haunts google(a country thriving to be trillion $ market cap.) till this day in their google assisstant.

## **DataSet?**
* This dataset contains product reviews and metadata from Amazon, including 143.7 million reviews spanning May 1996 - July 2014.

* This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs).

* The dataset consists of features in various formats. It has numerical data such as prices
and numbers of products/items, as well as categorical features such
as zone classifications for sale, which can be baby products’, ‘computer appliances,
, etc.
* i downloaded it from UCSD(University of California San Diego) official website.

## **How does all this work?**
* This project has two different components which although being mutually exclusive in relative sense are completely dependant. The components are Text Summarization and Opinion mining.
* first of all data is loaded in opinion mining file and after performing data-preprocessing, all the classifier algorithms are applied 1-by-1 which led to below conlusion :
* ![OPINION](https://i.imgur.com/CdwaT7r.png)
* then to enhance the opinion minig output, we passed remaining test data/user-input in WSD file in order to improve opinion and then after writing all the opinions(favourable & un-favourable) to respective text file, i performed Text summarization on them using TextRank algorithm on them individually.

## **System Specification and Algorithms.**
 
### **Software:**
* Programming Language: Python3.x.
* Software: Jupyter Notebook, VS Code editor, 
* Packages: Anaconda 3.5.6
* Libraries : NLTK,numpy,pandas,Matplotlib,tensorflow,NetworkX.

## **Algorithms:**
* Algorithm Used: Logistic regression,Naive Bayes Classifier(Bernoulli and Multinomial).
* Text Summarization: TextRank Algorithm.
* Word-Sense Disambiguation: Lesk Algorithm 

## **Hardware.**
* Operating System: Ubuntu 16.04.1(LTS)
* Hardware Requirements : 
* RAM: 4 GB
* Internal Storage : >10 GB


## **FYI : I named this repository on Linus Torvilds who is one of my great hero(if they even exist).**

# cs6474-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS6474 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs6474-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91058&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6474 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
The goal of this option of the assignment is to develop different supervised learning models to identify success or failure of altruistic requests on social media. The questions derive from social computing research that aims to understand linguistic markers of altruism as described on social media [1]. The questions in the assignment will test your understanding of theoretical notions of language and help seeking (narratives, moral foundations) and to what extent they can provide insights into the social construct of altruistic requests.

Part 1: Please refer to the enclosed zipped folder that contains dataset and associated information1. The dataset, named the file pizza_request_dataset.json, contains a collection of 5671 textual requests for pizza from the Reddit community “Random Acts of Pizza”2 (henceforth referred to as ROAP) together with their outcome (successful/unsuccessful) and meta-data. All requests ask for the same altruistic request: a free pizza, and span the timeframe December 8, 2010 to September 29, 2013. The outcome of each request – whether its author received a pizza (successful) or not (unsuccessful) – is known. In the questions below, the ground truth data for all of the classification models will be this outcome, specifically in the file pizza_request_dataset.json, the field requester_received_pizza. Please refer to Appendix I of this assignment document for an elaborate listing and description of all of the fields in the dataset file.

The features to be used in the classification models are described in the questions below. Please develop one classifier, specifically a Support Vector Machine model with a linear kernel and default parameters corresponding to each question below. For all of the classifiers, use a randomly sampled 10% of the dataset as test set (567 posts), and the remaining 90% as the training dataset (5104 posts) – the training and test sets need to be consistent across all classifiers below, i.e., the same 567 posts should be used for testing and the same 5104 for training for a), b), c) and d).

a) Model 1 – n-grams (20 points): This model will extract the top 500 unigrams and top 500 bigrams3 as features to classify posts that would be successful or those that will be unsuccessful in their pizza requests. Here “top” means most frequently occurring unigrams and bigrams in the posts belonging to the training set. Using these n-gram features, train and test an SVM classifier as described above. Report a table containing the accuracy of your classifier, precision, recall, F1, specificity, and AUC.

b) Model2–ActivityandReputation(20points):Thismodelwillutilizeavarietyoftheactivityandreputationdata included in the dataset file (pizza_request_dataset.json) as features to distinguish between successful and unsuccessful requests. The specific activity features will use the values included in the following fields corresponding to each post:

post_was_edited requester_account_age_in_days_at_request requester_account_age_in_days_at_retrieval

1 Downloaded from the SNAP Stanford website: http://snap.stanford.edu/data/web-RedditPizzaRequests.html

2 https://www.reddit.com/r/Random_Acts_Of_Pizza/ Excerpt from the subreddit description: “Feel like giving a random redditor a free pizza, but don’t know how or who? Well this is the right place for you! Random giving is why we are here!”

3 Post content is given in the field “request_text” in the dataset file pizza_request_dataset.json.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
requester_days_since_first_post_on_raop_at_request requester_days_since_first_post_on_raop_at_retrieval requester_number_of_comments_at_request requester_number_of_comments_at_retrieval requester_number_of_comments_in_raop_at_request requester_number_of_comments_in_raop_at_retrieval requester_number_of_posts_at_request requester_number_of_posts_at_retrieval requester_number_of_posts_on_raop_at_request requester_number_of_posts_on_raop_at_retrieval requester_number_of_subreddits_at_request requester_subreddits_at_request

And the specific reputation features will use the values included in the following fields for each post:

number_of_downvotes_of_request_at_retrieval number_of_upvotes_of_request_at_retrieval requester_upvotes_minus_downvotes_at_request requester_upvotes_minus_downvotes_at_retrieval requester_upvotes_plus_downvotes_at_request requester_upvotes_plus_downvotes_at_retrieval requester_user_flair

Using these values for activity and reputation as features, train and test an SVM classifier as described above.

Report a table containing the accuracy of your classifier, precision, recall, F1, specificity, and AUC.

c) Model3–Narratives(30points):Thisthirdmodelwillextractfeaturescorrespondingtothenarrativedimensions

identified in [1]. Refer to the enclosed files within “/resources/narratives”. There are five narratives – desire, family, job, money, and student. Each narrative file has a set of words associated with it. To extract post features corresponding to a narrative, perform regular expression match between all words corresponding to the narrative and those corresponding to a post (in the training and test sets)3. The narrative features for a post will be the ratio of the number of matches for each narrative to the total number of white spaced words in the post. Using these five narrative features, train and test an SVM classifier as described above. Report a table containing the accuracy of your classifier, precision, recall, F1, specificity, and AUC.

d) Model4–Moralfoundations(30points):Thisthirdmodelwillusethedimensionsof“moralfoundations”asfeatures for classifying successful and unsuccessful requests. These dimensions are based on the moral foundations theory4 that seeks to understand why morality varies so much across cultures yet still shows so many similarities and recurrent themes. In brief, the theory proposes that several innate and universally available psychological systems are the foundations of “intuitive ethics.” The dimensions of the moral foundations include: care/harm, loyalty/betrayal, authority/subversion, and sanctity/degradation. Their descriptions can be found in Appendix II. To extract features corresponding to the different dimensions, first refer to the enclosed file “MoralFoundations.dic” under “/resources” – the file opens with any simple plain text editor program. The dictionary contains terms indexed by integers, where the integers are mapped to the moral foundations dimensions. Then, for a given post in your training or test data3, obtain one feature corresponding to each dimension, by matching (with regular expressions) each word in the dictionary for that dimension to each word in the post. This way, you will obtain a count variable of the occurrence of the dimension in the post. By dividing this count by the total number of white spaced words in the post, you will obtain a normalized feature value for the same dimension. Using these dimensions as features, train and test an SVM classifier as described above. Report a table containing the accuracy of your classifier, precision, recall, F1, specificity, and AUC.

Part 2: Present a discussion of the performance of the above four models:

a) (4 points) Which of the four classifiers performed the best; which one performed the worst?

b) (6points)Describeyouranticipatedreasoningdrivingthesedifferencesinperformanceoftheclassifiers.

4 http://moralfoundations.org/

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
c) (10points)Formodels3and4inparticular,describetheirperformancecomparedtomodels1and2.Whydo you think they perform better or worse than models 1 and 2? Between models 3 and 4, which one is better? What could be the reason behind this observation?

d) (10points)Presentyourreasoningifyourmodelsindicatethatlanguageisabletopredictsuccessofaltruistic requests – other than model 2, all of the other models rely on language.

Part 3: Presentation a comparative discussion of the performance of all of your classification models and the performance metrics (AUC) reported in Table 4 of [1]:

a) (10 points) In what ways are your models similar or different from those in Table 4 of [1]? b) (10points)Whereandwhydotheyperformbetterorworsecomparedto[1]?

Reference:

[1] Althoff,T.,Danescu-Niculescu-Mizil,C.,&amp;Jurafsky,D.(2014).Howtoaskforafavor:Acasestudyonthe success of altruistic requests. In Proc. ICWSM 2014. Link: https://cs.stanford.edu/~althoff/raop- dataset/altruistic_requests_icwsm.pdf

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Appendix I

Format of the file pizza_request_dataset.json:

giver_username_if_known

in_test_set number_of_downvotes_of_request_at_retrieval number_of_upvotes_of_request_at_retrieval post_was_edited

request_id request_number_of_comments_at_retrieval

request_text request_text_edit_aware

request_title requester_account_age_in_days_at_request

requester_account_age_in_days_at_retrieval

requester_days_since_first_post_on_raop_at_r equest

requester_days_since_first_post_on_raop_at_r etrieval

requester_number_of_comments_at_request requester_number_of_comments_at_retrieval

requester_number_of_comments_in_raop_at_requ est

requester_number_of_comments_in_raop_at_retr ieval

requester_number_of_posts_at_request

requester_number_of_posts_at_retrieval

requester_number_of_posts_on_raop_at_request

requester_number_of_posts_on_raop_at_retriev al

requester_number_of_subreddits_at_request

</div>
<div class="column">
Reddit username of giver if known, i.e. the person satisfying the request (“N/A” otherwise). Boolean indicating whether this request was part of our test set.

Number of downvotes at the time the request was collected.

Number of upvotes at the time the request was collected.

Boolean indicating whether this post was edited (from Reddit).

Identifier of the post on Reddit, e.g. “t3_w5491”.

Number of comments for the request at time of retrieval.

Full text of the request.

Edit aware version of “request_text”. We use a set of rules to strip edited comments indicating the success of the request such as “EDIT: Thanks /u/foo, the pizza was delicous”.

Title of the request.

Account age of requester in days at time of request.

Account age of requester in days at time of retrieval.

Number of days between requesters first post on RAOP and this request (zero if requester has never posted before on RAOP).

Number of days between requesters first post on RAOP and time of retrieval.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Field

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Description

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Total number of

requester at time

Total number of

requester at time

Total number of

requester at time

Total number of

requester at time

Total number of

time of request.

Total number of

time of retrieval.

Total number of

time of request.

Total number of

time of retrieval.

The number of subreddits in which the author

</div>
</div>
<div class="layoutArea">
<div class="column">
comments on Reddit by of request.

comments on Reddit by of retrieval.

</div>
</div>
<div class="layoutArea">
<div class="column">
comments in RAOP by of request.

comments in RAOP by of retrieval.

</div>
</div>
<div class="layoutArea">
<div class="column">
posts on Reddit by requester at posts on Reddit by requester at posts in RAOP by requester at posts in RAOP by requester at

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
requester_received_pizza

requester_subreddits_at_request

requester_upvotes_minus_downvotes_at_request

requester_upvotes_minus_downvotes_at_retriev al

requester_upvotes_plus_downvotes_at_request

requester_upvotes_plus_downvotes_at_retrieva l

requester_user_flair

requester_username unix_timestamp_of_request

unix_timestamp_of_request_utc

Appendix II

Descriptions of the different moral foundations dimensions:

</div>
<div class="column">
had already posted in at the time of request.

Boolean indicating the success of the request, i.e., whether the requester received pizza.

The list of subreddits in which the author had already posted in at the time of request. Difference of total upvotes and total downvotes of requester at time of request.

Difference of total upvotes and total downvotes of requester at time of retrieval.

Sum of total upvotes and total downvotes of requester at time of request.

Sum of total upvotes and total downvotes of requester at time of retrieval.

Users on RAOP receive badges (Reddit calls them flairs) which is a small picture next to their username. In our data set the user flair is either None (neither given nor received pizza, N=4282), “shroom” (received pizza, but not given, N=1306), or “PIF” (given after received, N=83).

Reddit username of requester.

Unix timestamp of request (supposedly in timezone of user but in most cases equal to the UTC timestamp which is incorrect since most RAOP users are from the USA).

Unit timestamp of request in UTC.

</div>
</div>
<div class="layoutArea">
<div class="column">
Care/harm: This foundation is related to our long evolution as mammals with attachment systems and an ability to feel (and dislike) the pain of others. It underlies virtues of kindness, gentleness, and nurturance. Fairness/cheating: This foundation is related to the evolutionary process of reciprocal altruism. It generates ideas of justice, rights, and autonomy.

Loyalty/betrayal: This foundation is related to our long history as tribal creatures able to form shifting coalitions. It underlies virtues of patriotism and self-sacrifice for the group. It is active anytime people feel that it’s “one for all, and all for one.”

Authority/subversion: This foundation was shaped by our long primate history of hierarchical social interactions. It underlies virtues of leadership and followership, including deference to legitimate authority and respect for traditions.

Sanctity/degradation: This foundation was shaped by the psychology of disgust and contamination. It underlies religious notions of striving to live in an elevated, less carnal, more noble way.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>

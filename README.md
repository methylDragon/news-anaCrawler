# news-anaCrawler
Article Dataset Generator for Internet News Sites. Crawls news sites, analyses them with NLP (sentiment analysis), and pushes to a database.


# Our solution
A social gamified platform to enable and encourage collaborative fact-checking, with the use of Natural Language Processing to provide an initial estimate of the legitimacy of articles. We will also use the platform to generate a labelled dataset to improve future fact-checking algorithms.

## The issue
Almost all news outlets have digital editors that push the content through social media, which feature a comment thread. News websites sometimes have a comment section at the end of the article. These comments allow users to interact with each other, giving reading a social element and allow the content to compete in the news market. However, as entertaining as the comment thread may be, there is limited use in determining the truth value of the news. In news sites with an agenda, comments that support the agenda are highly rated by similar users. There is no place to point out the factual inaccuracies of the article, which will be filtered out. This reinforces the filter bubbles, polarising the society.

Worldwide, there are also websites dedicated to fact-checking like Snopes. Occasionally, local news outlets run articles to address the fake news. However, fact checking is not able to address every dubious article, which are cheap to generate. Moreover, it requires the user to be actively skeptical of everything he reads.

## The opportunity
This video elaboration on the issues with YouTube comment section is pivotal in the development of our solution: 
https://youtu.be/Lvf8koqX_yE

There are online communities who are dedicated to provide and check information. On Quora, users may write quality answers to address the most conceptual of questions. On reddit, there are rules which govern behaviour. The best users are upvoted, and their actions will have a greater influence in the community. 

## Other proposed solutions
These are solutions proposed by other finalists in the Google Hackathon.

One solution suggests inoculating targeted readers with the debunking of news before they receive the fake news shared by the users. Another solution proposes a modification to chatting applications like Whatsapp and listens to the articles you share and receive. It alerts you if it detects fake news, and discourages you from sharing it. Alternatively, another group suggested running the fact check Google search after a long press on the screen.

There are also interesting solutions proposed. One of which proposes to generate clickbait articles based on true facts to compete with sites that are notorious for fake news. Another proposes a game where the user guess whether a news is fake on Telegram, to educate people on the difficulty and necessity for fact-checking.

# Our platforms
We have two linked platforms – one to fact check and another to evaluate. We have Google Chrome extension to fact check, and a website or mobile application to evaluate.

## Platform to fact check
Users will install the chrome extension. It will appear as a circle on the top right of the browser. When it reads a fake article, it turns red. If the user is interested in the alert, he shall click on the extension and read the evaluation of the article. Alternatively, users can paste a snippet of the text, or picture, on our site without logging in.

<include our chrome extension screenshot>

## Platform to evaluate
In the evaluation platform, the article – which may be in the form of text, photo, video or a combination of several – is presented. Registered users judge whether the news is legitimate or not.

<include our very ugly UI>

Firstly algorithms will give an initial score of the legitimacy of the article, based on source reliability, sentiment analysis on language. For demonstration, we have adopted sentiment analysis to analyse the “polarity” and “subjectivity” of each sentence in the article. We also have a planned adoption of another algorithm to measure the provocativeness of the text.

Moreover, related sources are presented for cross reference. The recommended sites can be other articles or forums considering the legitimacy of the article and its claims. If a picture is posted, it will undergo a reverse image search to seek out the first image. If text is quoted, it also suggests references to ensure that they are drawn from the correct context.

With these, users now comment and vote on whether the news is fake or not. The influence the actions of the users have depends on his reputation, which can be increased with consistent and helpful participation.

# The user hierarchy
The influence users have is based on their reputation. If the user has been consistently been making active contributions through useful comments and correct upvotes, he will gain reputation. It is difficult for a troll or a bot to gain reputation.

We will also have moderators who are learned and trusted. We would also have moderators with diverse political views, but committed to obtaining the truth. They can be promoted from the user base if they have been providing exemplary fact-checking service. 

There are also the stakeholders who resolve conflicts of interest, set and balance the rules over time.

# Proposed lifecycle of dubious news
Firstly, the dubious news article is posted. The user gets a rough estimate of the legitimacy of the article. If the news is viral enough with many requests for fact checking, it will appear as top priority in our evaluation platform. Users will identify whether the news is fake or not. After a while, when a consensus on the legitimacy of the article is reached, the news entry is archived.

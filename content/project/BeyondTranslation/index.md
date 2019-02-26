+++
title = "Beyond Translation"
date = 2019-02-24T21:01:40-05:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Social-Media", "Machine-translation", "SenseTrans", "eye-tracking", "Lab Experiment", "Design", "Interview", "System", "Prototyping", "NLP", "Sentiment Analysis", "Named Entity Extraction", "System Evaluation", "Data Analysis", "sensemaking"]

# Project summary to display on homepage.
summary = "How can we improve cross-lingual communication on social media?"

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = "https://github.com/hajingit/SenseTrans"
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++



Machine translation is often not enough for people to engage across languages due to translation errors and lack of cultural background. My research aims to explore design possibilities to improve multilingual communication based on grounded understandings of how people consume and make sense of foreign language messages and contents.



#### Study 1: Understanding how people consume and make sense of foreign language messages

To investigate how language affects people’s attention to and engagement with social media posts, I conducted an eye-tracking lab study in which monolingual English speaking participants (N=22) viewed a mock newsfeed containing English and foreign language posts. The result showed that participants paid less attention to, and showed less willingness to engage with, foreign language posts compared to English posts.

I also conducted a qualitative interview study  examining participants’ actual Facebook timelines (N=23) and probing the reasons that people were reluctant to pay attention to and engage with foreign language posts. Interviewees reported that they felt a lack of relevance and cultural knowledge when they tried to understand foreign language posts. Even with MT results, literal translation often could not provide sufficient understanding of posts due to the imperfect quality of MT and people’s lack of contextual knowledge associated with each post. As a strategy to make sense of foreign language posts, some focused on simply extracting the emotional components of a post (e.g., emoji) while others tried to gain a fuller understanding of a post by searching the information about keywords.
{{< figure src="sensemaking_goals.png" title="Sensemaking Goals" >}}



##### Related Publications
1. **Hajin Lim** and Susan R. Fussell. 2017. Understanding How People Attend to and Engage with Foreign Language Posts in Multilingual Newsfeeds, In Proceedings of the International AAAI Conference on Web and Social Media (ICWSM’17) {{% staticref "/publication/lim-2017-making/lim-2017-making.pdf" "newtab" %}}[pdf]{{% /staticref %}}

2. **Hajin Lim** and Susan R. Fussell. 2017. Making Sense of Foreign Language Posts in Social Media, Proceedings of the ACM on Human-Computer Interaction Volume 1 Issue CSCW'18 {{% staticref "/publication/lim-2017-understanding/lim-2017-understanding.pdf" "newtab" %}}[pdf]{{% /staticref %}}


#### Study 2: Design and Evaluation of AI-Augmented Interface to support better sensemaking of foreign language posts
{{< figure src="SenseTrans.png" title="SenseTrans" >}}


Based on the previous findings, I designed and developed a browser extension, SenseTrans that provides emotional and contextual knowledge in addition to MT to support better sensemaking processes surrounding social media posts. Aligned with the sensemaking strategies that interview participants reported (i.e., emotion vs. context focus), SenseTrans
provided emotional knowledge about a poster’s emotional states and contextual knowledge about the social and physical context of a post. By making use of available NLP techniques such as sentiment mining and named entity extraction, SenseTrans provides auto generated emotional and contextual annotations based on the text content of a status update.

##### Related Publications
1. **Hajin Lim**, Dan Cosley, and Susan R. Fussell. 2018. Beyond Translation: Design and Evaluation of an Emotional and Contextual Knowledge Interface for Foreign Language Social Media Posts, In Proceedings of CHI'2018 {{% staticref "/publication/lim-2018-beyond/lim-2018-beyond.pdf" "newtab" %}}[pdf]{{% /staticref %}}
2. **Hajin Lim**, Design for Computer-Mediated Multilingual Communication with AI Support, In Proceedings of the companion publication of CSCW’18, ACM (Doctoral Colloquium)



### Research Method
* Eye-tracking
* Lab Experiment
* Semi-Structured Interview
* Interview Coding
* Design, Prototyping
* Development

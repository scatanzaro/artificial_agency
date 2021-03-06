# A Primer on Artificial Intelligence for Executives and Managers

_NB: I will use machine intelligence and artificial intelligence interchangeably, although this practice irritates me._

The benefits and risk of artificial intelligence comprise most headlines of tech publications today. However, enterprise adoption of artificial intelligence (AI) remains slower than anticipated and few organizations are effectively applying AI to drive revenue growth or realize operational efficiencies. As such, this primer will explain what artificial intelligence is and how it can be used and will provide guidance on building and managing an AI roadmap and team. 

##  What is artificial intelligence?

AI enables computers to perform tasks commonly associated with human intelligence, like reasoning and problem solving. 

AI is different from process automation, wherein human tasks are replaced with a set of rules that the developer defines (e.g. if-then logic). With process automation, the computer does what it is explicitly programmed to do, the same way over and over again. In contrast, AI algorithms learn from data and can sometimes adapt in response to new information. 

_Three types of artificial intelligence:_
- **Narrow AI**: Solves specific problems in specific contexts, but if the context or task changes, humans must reprogram or reconfigure the system. AlI solutions that exist today are narrow AI. Even platforms like IBM Watson must be tweaked to perform different services (like diagnosing medical problems or forecasting sales).
- **General AI**: Emulates human reasoning in any context by accumulating knowledge and applying common sense to solve different types of problems. 
- **Superintelligence**: Exceeds human cognition in every field including creativity, general wisdom, and social skills.

_AI buzzwords:_
- **Machine learning**: A subfield of artificial intelligence where algorithms learn from data to make a decision or prediction; machine learning algorithms do not have a specific set of instructions that they execute.
- **Training data**: The set of data (examples) from which the algorithm learns; this data set should be separated from your test data, which the developer uses to validate that the machine learning algorithm works 
- **Neural nets**: A computer model, which mimics the human brain and is made up of simple, highly interconnected processing units, arranged in layers. Neural networks learn by parsing input data, looking for relationships to build mathematical models, and automatically correcting these models. 
- **Deep learning**: In traditional machine learning, the developer must identify the variables (“features”) that should be used to make a decision or a prediction. Deep learning uses neural networks to discover the most relevant features and how they are related, so that the developer need not specify them. 
- **Supervised learning**: Machine learning approach used where the input and desired output are specified. The system uses labelled training data to predict the values of the label on unlabelled data. For example, an anti-fraud product might learn how to classify your bank activity after seeing thousands of examples of fraudulent and legitimate transactions.  
- **Unsupervised learning**: Machine learning approach used to find hidden patterns or groupings with unlabeled data (when a classification or categorization is not included in the training data). 
- **Reinforcement learnin**g: Machine learning approach where an agent learns the best sequence of actions to achieve some outcome based on reward or punishment. Reinforcement learning has been used, for example, to teach machines to play chess. 
- **Computer vision**: Teaching machines to see; computer vision applies machine learning and other technologies to enable machines to perceive, recognize, and classify images.
- **Natural language processing**: Branch of artificial intelligence concerned with analyzing, understanding, and generating written and spoken human language.
- **Tensorflow**: Tensorflow, released by Google in 2015, is just one of many open source libraries for machine learning learning. TensorFlow and alternatives like Torch, Theano, and Caffe; make it easier for developers to design, train, and deploy neural networks.

##  How can AI help your business?

**Predicting outcomes (predictive analytics)**: By finding useful patterns among thousands of variables in high volume, high velocity datasets (including both historical and real-time data), artificial intelligence enables organizations to more accurately predict unknown outcomes. For example, recommendation engines predict what a customer might buy. AI can also be used for anomaly detection by predicting what’s normal, and contrasting that with what’s observed. 

_Examples:_
- [Researchers at the University of Nottingham are using AI to predict heart attacks.](http://www.digitaltrends.com/health-fitness/ai-algorithm-heart-attack/) 
- [National Consortium for the Study of Terrorism and Responses to Terrorism (START) uses machine learning to predict terrorist threats.](http://www.start.umd.edu/news/advancing-machine-learning-algorithms-could-predict-terrorist-threats)


**Optimizing decisions (prescriptive analytics)**: Often we want to know the right series of actions or decisions to make to achieve some goal. When these decisions involve many, possibly conflicting objectives, artificial intelligence can provide a critical decision support tool. 

_Examples:_
- [Google uses artificial intelligence to optimize its data center costs.](https://deepmind.com/blog/deepmind-ai-reduces-google-data-centre-cooling-bill-40/)  
- [Microsoft MSN uses machine learning to optimize content delivery](http://www.marketingdive.com/news/microsoft-research-taps-machine-learning-to-automate-website-optimization/430333/).


**Organizing data**: Artificial intelligence can be applied to automatically find structure in data, for example by grouping data (e.g. on customers) into subsets (e.g. segments). Artificial intelligence can also be applied to transform free-form data like news articles or social media posts into structured data that can be entered into a spreadsheet. 

_Examples:_
- [Google uses machine learning to classify Gmail inbox spam.](http://www.zdnet.com/article/googles-machine-learning-helping-it-catch-spam-to-gmail/) 
- [QuickBooks uses machine learning to classify expenses as personal or professional.](http://www.pymnts.com/news/b2b-payments/2017/quickbooks-intuit-machine-learning-expense-management-self-employed/)


**Automating tasks**: Routine tasks, which can be described with a precise set of instructions, can be automated with traditional software programming. However, with artificial intelligence, some intellectual tasks, like interpreting sentiment or providing customer support, can also be automated. Artificial intelligence will also enable the next generation of autonomous systems, including robotics and self-driving cars. 

_Examples:_
- [The Associated Press uses artificial intelligence to automate broadcast content creation.](http://www.niemanlab.org/2016/10/the-ap-wants-to-use-machine-learning-to-automate-turning-print-stories-into-broadcast-ones/)
- [JP Morgan uses machine learning to review commercial loan agreements](https://www.bloomberg.com/news/articles/2017-02-28/jpmorgan-marshals-an-army-of-developers-to-automate-high-finance).
 

##  How can your company build and manage an AI roadmap?

_To successfully leverage artificial intelligence, you must meet at least three requirements:_
- You have reliable access to high quality data (for both training and production).

- You defined and can evaluate success metrics for artificial intelligence initiatives.

- You have determined that you cannot achieve these success metrics without artificial intelligence. Artificial intelligence is challenging and expensive, therefore, other methodologies like crowdsourcing should be considered first.
 

_To meet these requirements, you should first:_
- Assign a data product manager: Your data product manager should understand your desired business outcomes. She will determine if artificial intelligence can and should be applied to bring about these outcomes. She will determine what talent and resources are required to bring about these outcomes. She will define and measure objectives and key results to evaluate success (e.g. did artificial intelligence help achieve your desired business outcomes). 

- Assign a data engineer: Artificial intelligence rarely fails due to the model. More often, it fails when high quality data is not available or accessible. The data engineer will ensure the integrity and reliability of your data pipelines. 

- Evaluate your existing competencies: The product manager and data engineer should work with existing developers to determine if they can implement an AI solution by using open-source frameworks, like TensorFlow, or “machine learning-as-a-service” platforms. If not, you may consider hiring machine learning developers.


_If you determine that these actions are too costly or burdensome, there are some alternatives:_
- Consider other data acquisition and analysis strategies:
	1. **Crowdsourcing:** Crowdsourcing is an effective data acquisition strategy when you can provide a simple set of rules or steps to follow to collect the data you need, and when the scale of your data collection task is limited (e.g. less than 100,000 data points). For example, crowdsourcing could be used to collect addresses for a set of companies or to classify clothing items. Some crowdsourcing platforms, like [Crowdflower](https://www.crowdflower.com/), allow you to use data tagged by workers, as the input for machine learning models.
	2. **Outsourcing:** Outsourcing is more effective when you have a more complex set of rules or procedures, which may require more subjective judgements. When outsourcing tasks, you can more directly supervise workers.
	3. **Web scraping:** Lots of data is available online. You can use simple open source web crawling frameworks, like [Scrapy](https://scrapy.org/), to collect data like Craigslist postings or conference speakers.
	4. **Heuristic approaches:** Before deciding to implement a machine learning model, you should determine your precision and recall requirements. You should then try to execute the data collection task manually (e.g. with humans). In this process, you may identify a simple set of rules or criteria that can be applied to achieve your requirements. You can use traditional software programming to automate the execution of the rules or criteria.
	5. **Statistical modeling:** Statistical modeling may be more useful than machine learning when trying to make inferences from data, for example, about the relationship between two variables. Statistical modeling is often appropriate when large datasets are not available. It may be faster and less costly to use linear or logistic regression models for predictive analysis. 
- Buy an out-of-the-box, verticalized solution: If you want to solve one, specific problem, you may look for a vertical solution. For example, companies like Liftigniter offer recommendation engines while companies like Brightfunnel do marketing attribution. 

- Hire consultants or freelancers: Consultants can help you understand your current competencies and identify opportunities to leverage data. They can them work with external teams to implement solutions.

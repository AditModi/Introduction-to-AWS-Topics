
AWS offers the broadest and deepest set of machine learning services and supporting cloud infrastructure, putting machine learning in the hands of every developer, data scientist and expert practitioner.

In this blog post, we will discuss some of the most important AWS machine learning services that help you make accurate predictions, get deeper insights from your data, reduce operational overhead, and improve customer experience. AWS helps you at every stage of your ML adoption journey with the most comprehensive set of artificial intelligence (AI) and ML services, infrastructure, and implementation resources.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dovlzi24raggblu8n3ld.png)

> **The Introduction to AWS** is a Series containing different articles that provide a basic introduction to different aws topics/categories. Each article covers the detailed guide on how to work with particular topic/category . This series aims at providing "A Getting Started Guide on Different aws topics / categories ."

# AWS Machine Learning Services

* AWS helps streamline self-service processes and reduce operational costs through chatbots and virtual assistants.
* AWS compiles data from siloed and unstructured sources across your organization to drive business productivity and customer satisfaction.
* AWS helps drive customer engagement and conversion with websites tailored to individual visitors—and see your conversion rates soar.
* Using AWS, customers can instantly extract text and data from virtually any document, such as loan applications and medical forms, without manual effort.

# SageMaker

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/c7tgpvim9ms3gt12tjyo.png)
 
* SageMaker is a fully-managed platform that enables developers and data scientists to quickly and easily build, train, and deploy machine learning models at any scale. SageMaker removes all the barriers that typically slow down developers who want to use machine learning.

* Machine learning often feels a lot harder than it should be to most developers because the process to build and train models, and then deploy them into production is too complicated and too slow. First, you need to collect and prepare your training data to discover which elements of your data set are important. 

* Then, you need to select which algorithm and framework you’ll use. After deciding on your approach, you need to teach the model how to make predictions by training, which requires a lot of compute. Then, you need to tune the model so it delivers the best possible predictions, which is often a tedious and manual effort. 

* After you’ve developed a fully trained model, you need to integrate the model with your application and deploy this application on infrastructure that will scale. All of this takes a lot of specialized expertise, access to large amounts of compute and storage, and a lot of time to experiment and optimize every part of the process. In the end, it's not a surprise that the whole thing feels out of reach for most developers.

* SageMaker removes the complexity that holds back developer success with each of these steps. SageMaker includes modules that can be used together or independently to build, train, and deploy your machine learning models.

# SageMaker Ground Truth

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5u7ra2g1j7kk7xpiawwd.png)
 
* SageMaker Ground Truth helps you build highly accurate training datasets for machine learning quickly. SageMaker Ground Truth offers easy access to public and private human labelers and provides them with built-in workflows and interfaces for common labeling tasks. 

* Additionally, SageMaker Ground Truth can lower your labeling costs by up to 70% using automatic labeling, which works by training Ground Truth from data labeled by humans so that the service learns to label data independently.

* Successful machine learning models are built on the shoulders of large volumes of high-quality training data. But, the process to create the training data necessary to build these models is often expensive, complicated, and time-consuming. The majority of models created today require a human to manually label data in a way that allows the model to learn how to make correct decisions. 

* For example, building a computer vision system that is reliable enough to identify objects - such as traffic lights, stop signs, and pedestrians - requires thousands of hours of video recordings that consist of hundreds of millions of video frames. Each one of these frames needs all of the important elements like the road, other cars, and signage to be labeled by a human before any work can begin on the model you want to develop.

* Amazon SageMaker Ground Truth significantly reduces the time and effort required to create datasets for training to reduce costs. These savings are achieved by using machine learning to automatically label data. The model is able to get progressively better over time by continuously learning from labels created by human labelers.

* Where the labeling model has high confidence in its results based on what it has learned so far, it will automatically apply labels to the raw data. Where the labeling model has lower confidence in its results, it will pass the data to humans to do the labeling. 

* The human-generated labels are provided back to the labeling model for it to learn from and improve. Over time, SageMaker Ground Truth can label more and more data automatically and substantially speed up the creation of training datasets.

# Amazon Comprehend

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/uspyi1v6h346errzrck7.png)
 
* Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to find insights and relationships in text. No machine learning experience required.

* There is a treasure trove of potential sitting in your unstructured data. Customer emails, support tickets, product reviews, social media, even advertising copy represents insights into customer sentiment that can be put to work for your business. The question is how to get at it? As it turns out, Machine learning is particularly good at accurately identifying specific items of interest inside vast swathes of text (such as finding company names in analyst reports), and can learn the sentiment hidden inside language (identifying negative reviews, or positive customer interactions with customer service agents), at almost limitless scale.

* Amazon Comprehend uses machine learning to help you uncover the insights and relationships in your unstructured data. The service identifies the language of the text; extracts key phrases, places, people, brands, or events; understands how positive or negative the text is; analyzes text using tokenization and parts of speech; and automatically organizes a collection of text files by topic. 

* You can also use AutoML capabilities in Amazon Comprehend to build a custom set of entities or text classification models that are tailored uniquely to your organization’s needs.

* For extracting complex medical information from unstructured text, you can use Amazon Comprehend Medical. The service can identify medical information, such as medical conditions, medications, dosages, strengths, and frequencies from a variety of sources like doctor’s notes, clinical trial reports, and patient health records. 

* Amazon Comprehend Medical also identifies the relationship among the extracted medication and test, treatment and procedure information for easier analysis. For example, the service identifies a particular dosage, strength, and frequency related to a specific medication from unstructured clinical notes.

# Amazon Lex

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k3x5ye021m3wzo31v9lt.png)
 
* Amazon Lex is a service for building conversational interfaces into any application using voice and text. Lex provides the advanced deep learning functionalities of automatic speech recognition (ASR) for converting speech to text, and natural language understanding (NLU) to recognize the intent of the text, to enable you to build applications with highly engaging user experiences and lifelike conversational interactions. 

* With Amazon Lex, the same deep learning technologies that power Amazon Alexa are now available to any developer, enabling you to quickly and easily build sophisticated, natural language, conversational bots (“chatbots”).

* Speech recognition and natural language understanding are some of the most challenging problems to solve in computer science, requiring sophisticated deep learning algorithms to be trained on massive amounts of data and infrastructure. 

* Amazon Lex democratizes these deep learning technologies by putting the power of Alexa within reach of all developers. Harnessing these technologies, Amazon Lex enables you to define entirely new categories of products made possible through conversational interfaces.

# Amazon Polly

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/x5d4e97r0unoj9mvppl1.png)
 
* Amazon Polly is a service that turns text into lifelike speech. Polly lets you create applications that talk, enabling you to build entirely new categories of speech-enabled products. 

* Polly is an Amazon artificial intelligence (AI) service that uses advanced deep learning technologies to synthesize speech that sounds like a human voice. Polly includes 47 lifelike voices spread across 24 languages, so you can select the ideal voice and build speech-enabled applications that work in many different countries.

* Amazon Polly delivers the consistently fast response times required to support real-time, interactive dialog. You can cache and save Polly’s speech audio to replay offline or redistribute. And Polly is easy to use. 

* You simply send the text you want converted into speech to the Polly API, and Polly immediately returns the audio stream to your application so your application can play it directly or store it in a standard audio file format, such as MP3.

* With Polly, you only pay for the number of characters you convert to speech, and you can save and replay Polly’s generated speech. Polly’s low cost per character converted, and lack of restrictions on storage and reuse of voice output, make it a cost-effective way to enable Text-to-Speech everywhere.

# Amazon Rekognition

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ppjzk80dgkiq0095itw2.png)
 
* Amazon Rekognition is a service that makes it easy to add image analysis to your applications. With Rekognition, you can detect objects, scenes, and faces in images. You can also search and compare faces. The Amazon Rekognition API enables you to quickly add sophisticated deep-learning-based visual search and image classification to your applications.

* Amazon Rekognition is based on the same proven, highly scalable, deep learning technology developed by Amazon’s computer vision scientists to analyze billions of images daily for Prime Photos. Amazon Rekognition uses deep neural network models to detect and label thousands of objects and scenes in your images, and we are continually adding new labels and facial recognition features to the service.

* The Amazon Rekognition API lets you easily build powerful visual search and discovery into your applications. With Amazon Rekognition, you only pay for the images you analyze and the face metadata you store. There are no minimum fees, and there are no upfront commitments.

# Amazon Translate

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0shi3f5g3p2anppo7mkf.png)
 
* Amazon Translate is a neural machine translation service that delivers fast, high-quality, and affordable language translation. Neural machine translation is a form of language translation automation that uses deep learning models to deliver more accurate and more natural sounding translation than traditional statistical and rule-based translation algorithms. 

* Amazon Translate allows you to localize content - such as websites and applications - for international users, and to easily translate large volumes of text efficiently.

# Amazon Transcribe

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/s4rwezftk5qttgigy8mq.png)
 
* Amazon Transcribe is an automatic speech recognition (ASR) service that makes it easy for developers to add speech-to-text capability to their applications. Using the Amazon Transcribe API, you can analyze audio files stored in Amazon S3 and have the service return a text file of the transcribed speech. You can also send a live audio stream to Amazon Transcribe and receive a stream of transcripts in real time.

* Amazon Transcribe can be used for lots of common applications, including the transcription of customer service calls and generating subtitles on audio and video content. The service can transcribe audio files stored in common formats, like WAV and MP3, with time stamps for every word so that you can easily locate the audio in the original source by searching for the text. Amazon Transcribe is continually learning and improving to keep pace with the evolution of language.



# Amazon Forecast

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/bcwse141z84opqp5x9gw.png)
 
* Amazon Forecast is a fully managed service that uses machine learning to deliver highly accurate forecasts.

* Companies today use everything from simple spreadsheets to complex financial planning software to attempt to accurately forecast future business outcomes such as product demand, resource needs, or financial performance. 

* These tools build forecasts by looking at a historical series of data, which is called time series data. For example, such tools may try to predict the future sales of a raincoat by looking only at its previous sales data with the underlying assumption that the future is determined by the past. 

* This approach can struggle to produce accurate forecasts for large sets of data that have irregular trends. Also, it fails to easily combine data series that change over time (such as price, discounts, web traffic, and number of employees) with relevant independent variables like product features and store locations.

* Based on the same technology used at Amazon.com, Amazon Forecast uses machine learning to combine time series data with additional variables to build forecasts. Amazon Forecast requires no machine learning experience to get started. You only need to provide historical data, plus any additional data that you believe may impact your forecasts. 

* For example, the demand for a particular color of a shirt may change with the seasons and store location. This complex relationship is hard to determine on its own, but machine learning is ideally suited to recognize it. 

* Once you provide your data, Amazon Forecast will automatically examine it, identify what is meaningful, and produce a forecasting model capable of making predictions that are up to 50% more accurate than looking at time series data alone.

* Amazon Forecast is a fully managed service, so there are no servers to provision, and no machine learning models to build, train, or deploy. You pay only for what you use, and there are no minimum fees and no upfront commitments.

# Amazon Textract

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/h6diu7xchy6pwrge3nux.png)
 
* Amazon Textract is a service that automatically extracts text and data from scanned documents. Amazon Textract goes beyond simple optical character recognition (OCR) to also identify the contents of fields in forms and information stored in tables.

* Many companies today extract data from documents and forms through manual data entry that’s slow and expensive or through simple optical character recognition (OCR) software that is difficult to customize. 

* Rules and workflows for each document and form often need to be hard-coded and updated with each change to the form or when dealing with multiple forms. If the form deviates from the rules, the output is often scrambled and unusable.

* Amazon Textract overcomes these challenges by using machine learning to instantly “read” virtually any type of document to accurately extract text and data without the need for any manual effort or custom code. 

* With Textract you can quickly automate document workflows, enabling you to process millions of document pages in hours. Once the information is captured, you can take action on it within your business applications to initiate next steps for a loan application or medical claims processing. 

* Additionally, you can create smart search indexes, build automated approval workflows, and better maintain compliance with document archival rules by flagging data that may require redaction.

# Amazon Personalize

![image](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tkkn1rtao4y0uxu3kvmx.png)
 
* Amazon Personalize is a machine learning service that makes it easy for developers to create individualized recommendations for customers using their applications.

* Machine learning is being increasingly used to improve customer engagement by powering personalized product and content recommendations, tailored search results, and targeted marketing promotions. 

* However, developing the machine-learning capabilities necessary to produce these sophisticated recommendation systems has been beyond the reach of most organizations today due to the complexity of developing machine learning functionality. 

* Amazon Personalize allows developers with no prior machine learning experience to easily build sophisticated personalization capabilities into their applications, using machine learning technology perfected from years of use on Amazon.com.

* With Amazon Personalize, you provide an activity stream from your application – page views, signups, purchases, and so forth – as well as an inventory of the items you want to recommend, such as articles, products, videos, or music. 

* You can also choose to provide Amazon Personalize with additional demographic information from your users such as age, or geographic location. Amazon Personalize will process and examine the data, identify what is meaningful, select the right algorithms, and train and optimize a personalization model that is customized for your data.

* All data analyzed by Amazon Personalize is kept private and secure, and only used for your customized recommendations. You can start serving your personalized predictions via a simple API call from inside the virtual private cloud that the service maintains. You pay only for what you use, and there are no minimum fees and no upfront commitments.

* Amazon Personalize is like having your own Amazon.com machine learning personalization team at your disposal, 24 hours a day.

---

Hope this guide helps you with the Introduction to Machine Learning with AWS - Part-1. In the Next Blog Post, we will discuss more about different Machine learning Services that are available with AWS.

Let me know your thoughts in the comment section 👇
And if you haven't yet, make sure to follow me on below handles:

👋 **connect with me on [LinkedIn](https://www.linkedin.com/in/adit-modi-2a4362191/)**
🤓 **connect with me on [Twitter](https://twitter.com/adi_12_modi)**
🐱‍💻 **follow me on [github](https://github.com/AditModi)**
✍️ **Do Checkout [my blogs](https://aditmodi.hashnode.dev)** 

Like, share and follow me 🚀 for more content.

{% user aditmodi %}
# Python YouTube API

# 1. Aims, objectives and background

## 1.1 Description
In a world driven by digital content, YouTube has become a powerhouse for creators. Up to this day, it processes more than 3.5 billion searches per day and 1.2 trillion searches per year worldwide [[1]](https://www.globalreach.com/global-reach-media/blog/2020/01/28/the-2nd-largest-search-engine-on-the-internet). However, not every channel, nor every video, becomes popular as there is no complete certainty around how the YouTube algorithm works and the factors that lead to a video having many views.
As an enthusiast of both culinary arts and data analytics, I made this project to unveil the secrets behind the success of the most-subscribed food and drink YouTube channels in Mexico.

## 1.2 Aims and Objectives
By leveraging the YouTube API, I delve deep into their content to uncover patterns, insights, and strategies that contribute to a channel's popularity. Some of the questions that guide the project are:
- Do more likes equate to more views?
- What's the impact of user comments on a video's performance?
- Is there an ideal video duration?
- How the length of video titles correlates with views. Should it be short and catchy, or detailed and descriptive?
- How many tags do the most popular videos have?
- What's the best day of the week to upload content?
- What are the most frequently used words in video titles?

## 1.3 Methodology
The project takes a holistic approach by analyzing not just one, but the top nine food and drink YouTube channels in Mexico by subscribers [[2]](https://hypeauditor.com/es/top-youtube-food-drinks-mexico/). This comprehensive view offers a profound understanding of what captivates the Mexican audience.
The steps followed were:
1. Obtain video metadata via Youtube API for the top nine channels in the niche (this includes several small steps: create a developer key, request data, and transform the responses into a usable data format)
2. Preprocess data and engineer additional features for further analysis
3. Exploratory data analysis
4. Natural language processing
5. Conclusions

## 1.4 Impact and Contribution
This project isn't just about data; it's about empowering aspiring content creators in my country. By shedding light on the factors that contribute to the success of top food and drink channels in Mexico, I provide valuable insights for anyone looking to embark on a similar YouTube journey– whether you're a budding chef or a culinary storyteller.

## 1.5 Limitations
The dataset used in this research is sourced from real-world data, making it suitable for the project. I selected the top 9 most popular YouTube channels based on Hypeauditor's list of 'the top 1000 Food and Drink YouTube Channels in Mexico' [[2]](https://hypeauditor.com/es/top-youtube-food-drinks-mexico/). However, this list is based solely on subscriber count, even though other relevant metrics like views and engagement could be considered. Additionally, the choice of the top 9 channels may seem arbitrary given the vast number of channels on YouTube. There may be smaller channels that could be equally interesting for exploration.

## 1.6 Ethical Considerations of Data Source:
By the guidelines of the YouTube API, the usage of the API is provided free of charge, provided that applications adhere to a specified quota limit "to ensure that developers use the service as intended and do not create applications that unfairly reduce service quality or limit access for others." [[3]](https://developers.google.com/youtube/v3/getting-started). By default, each application is allocated 10,000 units per day, and if necessary, additional quota can be requested through the YouTube API Services by completing a form if the initial quota limit is reached.
It's important to note that all data obtained from the YouTube API is publicly accessible data, visible to anyone on the internet through YouTube. Therefore, there are no significant privacy concerns from my perspective. Furthermore, the data has been collected exclusively for research purposes in this case and is not intended for any commercial interests.

## 1.7 Acknowledgements
I would like to extend my appreciation to 'Thu Vu Data Analytics' for their invaluable guidance, as I drew inspiration from her video titled 'YouTube API for Python: How to Create a Unique Data Portfolio Project.' [[4]](https://www.youtube.com/watch?v=D56_Cx36oGY&t=558s&ab_channel=ThuVudataanalytics).

I used her code as a foundation for my Data Analysis project. However, I have made several modifications and enhancements to tailor the analysis to my specific goals and requirements. While the initial code provided valuable insights, I have adapted it to suit the unique aspects of my project.

## 1.8 References
[1] The 2nd Largest Search Engine on the Internet. (2020, January 28). Global Reach. https://www.globalreach.com/global-reach-media/blog/2020/01/28/the-2nd-largest-search-engine-on-the-internet

[2] Top 1000 canales de YouTube de Comida y bebida en México. HypeAuditor. https://hypeauditor.com/es/top-youtube-food-drinks-mexico/

[3] YouTube Data API Overview. (2022, March 4). Google. https://developers.google.com/youtube/v3/getting-started 

[4] Thu Vu data analytics. (2022, January 22). Youtube API for Python: How to Create a Unique Data Portfolio Project [video]. Youtube. https://www.youtube.com/watch?v=D56_Cx36oGY&t=558s&ab_channel=ThuVudataanalytics
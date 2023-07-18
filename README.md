# Assignment 2: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and many other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is ocassionally [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

Through this assignment, you will be able to answer questions about protests, including:

* What were the most attended and least attended protests in the US in the last 5 years?
* How many protests occurred in Washington state?
* How did the number of protests in 2019 compare to 2020, and why?
* Why are people protesting in the US? What are the biggest motivators?

## Learning objectives
By completing the assignment, you will develop or skills for:

- **Version control** tools for managing code (git and GitHub)
- Writing documents with **markdown** syntax
- Coding in R
- Thinking critcally about data.

# 1. Critical Analysis & Reflection: Before You Code

Before diving into this (or any) dataset, it's important to know where the data came from, and it's important to have or to seek out _domain familiarity_ — that is, knowledge about the topic of the dataset. Sometimes the topic is very narrow; more often it is expansive, as in the case of CountLove. We don't want to be "strangers in the dataset," as Catherine D'Ignazio and Lauren Klein describe it. To get more familiar, we are going to begin by doing some background reading.

**Note:** Please write your answers below under the heading "Your Responses and Reflections."

- First, please read [this FAQ](https://countlove.org/faq.html) from the CountLove website and the opening of [this blog post](https://www.tommyleung.com/countLove/index.htm).  **(R1a)** 

- Next, we would like you to read this [New York Times piece that uses CountLove data](https://www.nytimes.com/interactive/2020/06/13/us/george-floyd-protests-cities-photos.html) and that describes the Black Lives Matter protests that occurred in the summer of 2020. **(R1b)** Please summarize the main point or argument of this article.

Next, we're going to reflect about who collected this data, and what's actually inside it. 

**(R1c)** Who collected and shared the CountLove data, and what do they do for a living?

**(R1d)** As Klein and D'Ignazio remind us, when it comes to data, "what gets counted counts." What types of demonstrations does CountLove include in their data, and what types do they exclude? 

**(R1e)** How and where does CountLove get their data about the protests? 

**(R1f)** How does CountLove make their estimates about the number of people who attended a protest? What potential problems might arise from this method of estimation? 

**(R1g)** What are two central values of Count Love? Name and briefly describe them. (See the Envisioning Cards for a defintion of "value".)

**(R1h)** Name and briefly describe one direct stakeholder and one indirect stakeholder 

# 2. Coding in R: Parts 1-6
**Instructions**. Assignment instructions and prompts are in this file: [analysis.R](analysis.R).

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to think and write in English below, in this file (README.md).

**Formatting Your Responses and Reflections**.

* When formatting your written responses and reflections below, please *retain* all
reflection prompt IDs (e.g., R1a, R2a, etc.).
* Fill in the elipses (...) with your own words. 
* Remove expected word counts.
* To write clearly, use markdown code appropriately (e.g., **bold**, _italics_, and `code`). As appropriate, include images, links, and so forth.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: October 2022, Your Teaching Team_)

# 3. Critical Analysis & Reflection: After You Code

In the second chapter of *Data Feminism*, Klein and D'Ignazio describe 4 ways that data scientists can challenge power and take action:
> Taking action can itself take many forms, and in this chapter we offer four starting points:  
> (1) Collect: Compiling counterdata—in the face of missing data or institutional neglect—offers a powerful starting point as we see in the example of the DGEI, or in María Salguero’s femicide maps discussed in chapter 1.  
> (2) Analyze: Challenging power often requires demonstrating inequitable outcomes across groups, and new computational methods are being developed to audit opaque algorithms and hold institutions accountable.  
> (3) Imagine: We cannot only focus on inequitable outcomes, because then we will never get to the root cause of injustice. In order to truly dismantle power, we have to imagine our end point not as “fairness,” but as co-liberation.  
> (4) Teach: The identities of data scientists matter, so how might we engage and empower newcomers to the field in order to shift the demographics and cultivate the next generation of data feminists?  

**(R1h)** How does the CountLove project embody one or more of these 4 forms of challenging power? 

**(R1i)** What is the most interesting or surprising thing you learned from this analysis? Please answer in at least 2-3 sentences (2 points)

**(R1j)** What is a kind of analysis that you would like to do or that would be interesting to do with the CountLove data that you don't have the time or skills to accomplish at this moment? Please answer in at least 2-3 sentences (2 points)

## Your Responses and Reflections

### Critical Analysis & Reflection: Before You Code (questions above)

* **(R1a)** ... (about 25-50 words)
The creators of Count Love started collecting protest data in 2016 to address the lack of accessible protest information in the US, aiming to provide a factual record and make it more accessible for journalists. The data is used by organizations like the New York Times Protest Database.
* **(R1b)** ... (about 25-50 words)
The main point of the article is that the death of George Floyd in Minneapolis ignited a widespread movement against racism and police brutality in the United States. The article highlights the scale and intensity of the Black Lives Matter protests that took place in the summer of 2020, with demonstrations occurring in numerous cities and towns across the country. It describes the diverse participants, the peaceful nature of most protests, as well as instances of violence and destruction. The article raises the question of whether these protests will lead to lasting change and urges a closer examination of the challenges faced by black Americans.
* **(R1c)** ... (about 25-50 words)
Tommy Leung and Nathan Perkins, who are engineers and scientists collect and shared CountLove data.
* **(R1d)** ... (about 25-50 words)
CountLove includes public displays of protest that are not regular business, focusing on demonstrations that express dissent and demand change. They exclude awareness events, celebrations, reenactments, fundraising events, town halls, and political rallies.
* **(R1e)** ... (about 25-50 words)
CountLove obtains its protest data by crawling local newspaper and television sites on a daily basis. They gather information from news articles and record the most conservative attendance numbers mentioned in those articles.
* **(R1f)** ... (about 25-50 words)
CountLove estimates the number of attendees by recording the most conservative attendance number mentioned in news articles. However, this method relies on the accuracy of media reports and may be subject to biases, errors, and limitations in available information.
* **(R1g)** ... (bullet points fine; about 50 words)
Two central values of Count Love are accessibility and maintaining a factual record. They prioritize making protest data accessible to journalists and citizens while ensuring an accurate and comprehensive record of ongoing demonstrations, fostering transparency and informed civic engagement.
* **(R1h)** ... (bullet points fine; about 50 words)
One direct stakeholder of Count Love is the Crowd Counting Consortium (CCC), which collaborates with Count Love to gather protest data. An indirect stakeholder is the general public, who benefit from accessible and reliable protest data to stay informed and engage in civic participation.

### Part 3: Locations (`analysis.R`)
* **(R3a)** ... (about 25-50 words)
* **(R3b)** ... (about 25-50 words)
* **(R3c)** ... (about 25-50 words)

### Critical Analysis & Reflection: After You Code (questions above)
* **(R7h)** ... (100 words or more)
* **(R7i)** ... (50 words or more)
* **(R7j)** ... (50 words or more)

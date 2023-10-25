# InstiGPT Assignment

## Part 1: Chatbot creation

[**Google Colab Notebook Link**](https://colab.research.google.com/drive/1tLAWB3VR3H0Bt6g7-D7fQmgRvAyYT_GN?usp=sharing)

### Queries and responses(Llama-2-7b-chat):

1. What are the categories of student for choosing amount of registration credit load?
    
    Based on the provided context, there are six categories of students for choosing the amount of registration credit load:
    
    1. Category I - 54 credits
    2. Category II, III, IV - 48 credits
    3. Category V - 30 credits
    4. Category VI (ARP) - 24 credits
2. Can you give information about auditing a course?
    
    Yes, I can provide information about auditing a course. According to the context, a student who wants just an exposure to a course without obtaining a letter grade can register for the course in 'Audit' mode. The course can be audited provided it is offered in the semester, and students should give priority to clear core courses that are pre-requisites for other courses in subsequent semesters.
    
3. What is a B.Tech. Project?
    
    From the provided context, it can be inferred that a B.Tech. Project is a requirement for the Bachelor of Technology (B.Tech.) degree, or as a requirement for Honors, wherein a student under the guidance of a faculty member must summarize and present the results from literature in a written report and present it before a designated committee of faculty members. The project typically carries 3 credits.
    
4. What is an additional learning course?
    
    An additional learning course is a course that provides opportunities for students to learn in diverse areas outside of their degree program. These courses are designed to broaden a student's knowledge base and provide them with specialized skills and expertise that can be applied to their future careers. By taking these courses, students can earn additional credentials such as Minors or Honors, which can enhance their job prospects and increase their marketability in the workforce.
    
5. Give me info about branch changing?
    
    According to the requirements, shifts and changes of branch can be performed as long as there are valid requests, but there is a specific rule that states that no application for change of branch will be entertained during subsequent academic years after the beginning of the second academic year. Additionally, any branch change decisions made will be final and cannot be reversed (Reference: 250th Senate Meeting).
    

## Part 2:

1. The chatbot should be able to ensure information reliability and should not hallucinate at all. It should have informational access to many things like resobin, personal profile, and mainly internet. It should be able to give references and mention occurrences in the documents.
More problems are alluded to in the below answers.
2. I made a chatbot where it first retrieves content by semantic search and then tries to answer. If a query is raised such that it can only be answered when combining contexts from multiple places, then this method won’t suffice. 
The chatbot doesn’t have a good user interface. By that I refer to the UI in the LLM side. For example, I can make it generate references to specific pages like Bing chat does. In the real use case (InstiGPT), we might use lot of documents, references, sites, etc… so that requires a lot of coding and innovative engineering.
My chatbot doesn’t have some kind of mechanism like re-prompting itself again if it feels like it doesn’t have enough information.
If it’s an especially long response time(Falcon 180B) my chatbot can’t be stopped mid-response.
My chatbot doesn’t have the capability of storing chat sessions to be continued later.
There might be other problems also I’m missing which I may get an idea of only when I start doing the coding/software engineering.
3. I struggle a lot when I try to create an academic plan. The chatbot should be versatile enough to reason and brainstorm with me, like highlighting pros and cons, finding unseeming tradeoffs I might need to make, etc.. It should have a personal profile of me containing all necessary information for the previously suggested ideas. Resobin integration would be very beneficial for that. 
I struggle when finding a professor whose work I have interest in for doing a research project. The chatbot should be able to find professors for me according to my interested research topics, this might require internet access like google scholar page of professors.
It should be able to handle the need of up to date information for some prompts/queries.
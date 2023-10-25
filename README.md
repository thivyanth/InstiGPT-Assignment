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
    

## **Part 2: Research and Analysis**

### 1. Main Problems:

- **Information Reliability and Avoiding Hallucinations**:
    - It’s important that InstiGPT provides reliable and factual information, steering clear of generating any false or misleading responses.
    - It is crucial to reduce chances of hallucinations, especially when there is no clear reference to the provided documents or data, ensuring the trustworthiness of the responses.
- **Access to External and Digital Information**:
    - Ensuring InstiGPT has comprehensive access to all digital information about the institute is fundamental.
    - There should be provisions for the chatbot to fetch data from various resources like Resobin, personal profiles, and the internet, ensuring it can reference specific occurrences in the documents and provide proper citations.
- **Combining Contexts from Multiple Sources**:
    - A significant challenge arises when a query necessitates the amalgamation of contexts from disparate sections of the documents or external sources. InstiGPT should be adept at handling such complexities to provide well-rounded responses.
- **User Interface and Experience**:
    - Enhancing the user interface on the LLM side is imperative to facilitate a more interactive and informative user experience.
    - InstiGPT should emulate advanced features seen in platforms like Bing Chat, enabling it to generate references to specific pages or documents seamlessly.
- **Scalability and Maintenance**:
    - With the anticipated integration of a myriad of documents, references, sites, etc., InstiGPT must be scalable and robust, necessitating extensive coding prowess and innovative engineering solutions.
- **Self-Prompting and Response Management**:
    - Incorporating mechanisms that allow InstiGPT to seek additional information autonomously when needed will enhance its ability to handle queries more effectively.
    - Addressing potential issues related to protracted response times and providing the capability to interrupt the chatbot mid-response are also critical.
- **Session Management and Continuity**:
    - InstiGPT should be proficient in storing chat sessions, allowing users to pick up right where they left off, ensuring a seamless user experience.
- **Navigational Assistance and Campus Knowledge**:
    - Having an intrinsic knowledge of the entire campus map and every significant location is vital for InstiGPT to assist in planning and navigation.
    - InstiGPT should serve as a central hub for navigating through various institutional sites, simplifying the user’s journey in finding pertinent information.
- **Mobile Accessibility**:
    - Recognizing that the majority of users will likely access InstiGPT via mobile phones, optimizing it for mobile accessibility is important.
- **Integration with External Applications**:
    - Ensuring seamless integration with widely used applications like Google Maps, institutional apps, and other pertinent tools will significantly enhance InstiGPT’s utility.
- **Networking and Finding Relevant Contacts**:
    - InstiGPT should facilitate easy networking, helping users find students and professionals within the institute who are working in specific fields of interest.
- **Staying Updated with Current Affairs**:
    - The ability for InstiGPT to keep users informed about the current affairs and happenings within the institute is essential, ensuring that the chatbot serves as a reliable source of up-to-date information.

### 2. Problems in My Chatbot:

- **Limited User Interface**:
    - The current assignment submission chatbot lacks a sophisticated user interface on the LLM side, making it less interactive and user-friendly.
- **Lack of Contextual Combining**:
    - The chatbot struggles to answer queries that require combining contexts from multiple places in the documents.
- **Inability to Stop Mid-Response**:
    - The chatbot currently cannot be stopped mid-response, which could be problematic for lengthy response times.
- **Lack of Session Continuity**:
    - The assignment submission chatbot does not have the capability to store chat sessions for continuation at a later time.

### 3. List of Potential User Queries:

- **Academic Planning**:
    - InstiGPT should excel in aiding users with their academic plans, delineating the pros and cons, and uncovering potential trade-offs that might need consideration.
    - It should provide personalized recommendations and insights based on the user’s academic history, utilizing integration with tools like Resobin for a more comprehensive experience.
- **Research and Professor Matching**:
    - Users should be able to rely on InstiGPT to find professors whose research interests align with theirs, necessitating access to up-to-date information from sources such as Google Scholar.
- **Networking and Finding Like-minded Individuals**:
    - InstiGPT should serve as a catalyst in connecting users with students and professionals within the institute who share similar interests, fostering a community of collaboration and shared knowledge.
- **General College Queries**:
    - From courses and placements to admission procedures and graduation requirements, InstiGPT should be a repository of knowledge, readily answering a wide array of college-related queries.
- **Current Affairs and Institutional Updates**:
    - Keeping users abreast of the latest happenings and current affairs within the institute is a critical functionality that InstiGPT should encapsulate.
# lingua-link
2024 INFO Capstone Project Website Repository: lingua-link

# Project Overview 
Lingua-Link is a peer-to-peer language learning mobile application that creates a safe and secure language exchange community. This app fosters meaningful conversation and cultural exchange between learners of different languages. 

Additional Links:
- [Capstone Website](https://cwills07.github.io/lingua-link/)
- [Capstone Presentation Deck](https://acrobat.adobe.com/id/urn:aaid:sc:us:89437343-e0fb-43e1-984e-7f25f75cf174)
- [Final Prototype Link](https://www.figma.com/proto/XCl5sOkAWiONGzEjBV1yW1/lingua-link-wirerames?page-id=8%3A2&node-id=923-9899&viewport=25%2C200%2C0.02&t=lkriwO0hukM3pJuA-1&scaling=scale-down&starting-point-node-id=702%3A7703&show-proto-sidebar=1)

# Summary of Market and User Research
We performed an extensive competitive analysis of the existing language learning market space:
- Analyzing key features and aspects of Duolingo, HelloTalk, Babbel, and Busuu
- Conducting usability testing of these existing apps to categorize challenges and benefits based on user needs

During this analysis, we identified a privacy and security gap that users experience when connecting with others online

We conducted surveys of target users regarding their language learning motivations, needs, purpose, and benefits/concerns of a peer-to-peer learning approach. We also conducted in-depth interviews about users' privacy and security concerns.

# Design and Testing Process
We created the user personas based off of our initial user research. 
We conducted usability testing on the mid-fidelity and high fidelity prototypes. 

From our preliminary user survey results, we found that that the primary reason why people stopped using language learning apps was due to a loss of interest and motivation (63.6%). Many participants reported a gap in how existing apps did not help them learn conversationally relevant skills.

Quotes:
"Apps haven't been very successful in simulating conversations. So it can be hard to practice actually talking and forming your own sentences in the apps"

"It felt like I was learning vocabulary that wouldn't be used conversationally and not applicable if I were to go to the country"

### SWOT Analysis of Duolingo and HelloTalk
Duolingo is one of the most popular and dominant language learning platforms that focuses on gamification as the primary learning modality. Whereas HelloTalk is a global language learning app that focuses on peer-to-peer connections through chat, voice call, and video call modalities. Duolingo's weaknesses included limited explanations of grammar and cultural concepts. HelloTalk's weaknesses included growing user concerns about privacy and security as more restrictions and authorizations are needed in the app. 

### User Validation of Key Concepts
As we conducted more user interviews and usability testing of existing apps, our users highlighted the importance of structured learning environments, valued community features that allow users to connect with native speakers, as well as consistency and motivation. However, our users did report privacy and security related concerns and hesitations with connecting with strangers online. 

### User Personas 
<img width="1104" alt="image" src="https://github.com/cwills07/lingua-link/assets/114948546/90645fec-8345-4a90-bd07-d15185e34ef5">

<img width="1104" alt="image" src="https://github.com/cwills07/lingua-link/assets/114948546/463dbc3a-2019-43a5-b932-1dbb7443cb5d">

# Feature Prototyping
Our research and design process informed the prototyping of the following key features:
1. Secure Onboarding
   - User verification through 2FA
   - Customizable avatars for users
   - Community guidelines
     
2. Verified User Matching
   - Users must approve lingua-link matches
   - Only approved matches can engage in conversation/chatting with each other
   - AI content and chat moderation
   - Flagging and blocking users for inappropriate behaviors
     
3. Personalized Language Learning
   - Users can practice lessons together
   - Customizable games and interactive lessons
   - Interactive progress tracking

# Development Roadmap
lingua-link's current project status is a design handoff available as open-source for any future capstone group to implement and code out the functionality. 

### Optimize Matching: leveraging user feedback, refining the matching system
- Develop algorithm that matches individuals based on aligned learning goals and interests
- Potential machine learning frameworks or models that could be helpful for finding similar individuals are k-means, divisive clustering, agglomerative clustering
- Another approach could be to train classification models, such as decision trees or logistic regression, to identify whether a pair of users would be a strong match, okay match, or no match
- scikit-learn package in Python is a great, easy-to-use, well documented machine learning package
   
### Personalized Learning: Implement customizable flashcards and conversation topics based on user preferences
- Focus on developing the content and conversation topics in a particular language that you are most familiar with, i.e. learning Spanish or English
- Research common everyday phrases for daily interactions, vocabulary, grammar, reading and writing
   
### Content and Security: Incorporate AI content moderation and user safety features into lingua-link
- Flag and Block feature
- Train AI model i.e. ChatGPT to monitor chat and filter out inappropriate language or messages that violate commmunity guidelines

Since lingua-link is designed to be a mobile application, we recommend either iOS or android platform development. 

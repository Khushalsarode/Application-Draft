# Outreachy Final Application Draft
---
### Wikimedia Foundation
### Proposal  
### Title: Create Scribe-Data Wiktionary based translation and synonym commands

---
**Name:** Khushal Sarode  
**Email:** khushalsarode.in@gmail.com  
**Location:** Jalgaon, Maharashtra, India  
**IRC nickname on Matrix:** khushalsarode <br>
**LinkedIn:** [Khushal Sarode](https://www.linkedin.com/in/khushalsarode/)  <br>
**Time Zone:** UTC+5:30 IST <br>
**Availability:** Available Full Time <br>
**Time Commitments:** Currently I am available full time to work also hunting Full time opportunity if any sudden course of action took place will be communicating with you.

----
## Time Commitments on Initial Application

You listed the following time commitments on your initial application. Please make sure they are correct and reflect your current time commitments:
> Currently, I am available full time to work along side hunting Full time opportunity, if any sudden course of action took place will be communicating with you. Time duration and commitments asked, I'm available to work on project.

### Are the time commitments listed above correct?
If any time commitments (like a job or school) are missing, please answer "no." If any start or end dates are incorrect, answer "no."
#### **Response**:
> [x]Yes / No
---
## Abstract
`Scribe-org` is an open source project which is a community of language enthusiasts, learners and developers creating tools to help people communicate with confidence.
It is an tool being developed for interested language learners with creative way, this is available for IOS ecosystem. The application provide an real time grammer, translations over keyboard which support to serval most used languages and its exanding too. The project Aim to breach the langauge barrier gap effectively by utilizing the data from wikidata by processing it.  
where as an subpart of project is `Scribe-Data` is a convenient command-line interface (CLI) for extracting and formatting language data from Wikidata and Wikipedia. Functionality includes allowing users to list, download, and manage language data directly from the terminal.

---
## Past Experience with This Community
I have benn working on Scribe-data project from pass few days and its quite interesting! Mentors are very friendly, guide when ever asked for help, listen to suggestions.
Also the contributors and quite friendly and share ideas with interacting each other. This is an first time i've gained such a experience with open source community project mission and objective. Working side to side with such fantastic contributors and maintainers i've been learning a lot. Before this i had never used an sparql query language but in this project while contributing i understand and contributed queries written in it, worked on some action flow to make task automate over repository.
Also worked on project documentation build using sphnix and learned about documentation and how its implemented for project like this one. Fix some error and build documentation to report broken link to maintainer/contributors.
This is just beginning there is more yet to learn and build! 😊😊

---

## Mentors

- Andrew McAllister  
- wkyoshida
- Henrik Thomasson
---

##  Experience and Contributions - INITIAL CONTRIBUTION
As applicatant selected for initail contribution, Have done some contibution in project code base as follows:
- 1. PR: https://github.com/scribe-org/Scribe-Data/pull/425
- Detail: Added nouns sparql query for latvian langauge by quering against nouns entity on wikidata. Query have been tested and executed on Wikimedia query editor.

- 2. PR: https://github.com/scribe-org/Scribe-Data/pull/272
- Detail: The issue was to expand the kurmanji verb entity by querying the wikidata language entity. To expand kurmanji verbs it has been queried against the other language entity for wikidata in sparql query language on wikidata query editor.

- 3. PR: https://github.com/scribe-org/Scribe-Data/pull/317
- Detail: Created and expanded data queries for kurmanji language on query.wikidata.org query service by wikidata, where preposition, verbs, nouns, adverbs and adjective for kurmanji language 'ku' where queried against english language entity and entity entries for grammatical parts to get as much as possible data for language to be process by scribe data.

- 4. PR: https://github.com/scribe-org/Scribe-Data/pull/433
- Detail: Created an Github action workflow to check documentation broken link and show broken link list for debugging and further work:
   1. Installs the necessary dependencies from requirements.txt
   2. Runs the Sphinx linkcheck builder to identify broken links.
   3. The results are displayed, and if broken links are found, the action will fail.
---
## Past Experience with Open Source Software
- Participated and completed girlscript summer of code 24 by contributing to some projects
- Participated and completed hacktoberfest by raising four PR 
- Contributed to tsparticle repository with 404 error theme pages
- Contributed to illa cloud and no code platform
- Contributed and written blogs for aviyel under aviyelXhacktoberfest22
- Current participant and contributor to girlscript summer of code extended 2024
---

## Past Experience with Other Communities
I have also been involved in other free software communities such as Girlscript summer of code which is an open source program just pretty alike google summer of code, they have project mainntainers, contributors, mentors, and core team who carry out program of duration three month. the program is score based which reflect on leaderboard, score based on work done in contibution divided into 3 levels. I had participated as contributed and raised request which fixed documentation, code, and added some features. Along with this they had arranged postman badge challenege which was also compeleted resulting in extra points. 

---

## Relevant Projects
 - **Project**: [SkyScribe Weather Forecast CLI based tool](https://github.com/Khushalsarode/SkyScribe-Weather-Forecast-clitool)
   - **Description:** An Cli based application tool for retriving an weather information of specific location using commands.
   - Used click package for creating command and command argument for project tool execution, logging for recording log while making request or requesting data
   - created an module and deployed at pypi using setuptools (setup.py file), we can install tool using pip and used the command line to get weather data. 
   - Skills gained:  Python programming, Logging of logs, API handling, creating and deploying packages modules, etc

---


## Outreachy Internship Project Timeline

## Phase I: Research and Designing  
**WEEK 1 + WEEK 2**

- **Week 1:** Research and Analysis of Wiktionary Data  
  **Objective:** Gain an in-depth understanding of Wiktionary’s structure and relevant SPARQL queries.  
  - Review existing documentation on Scribe-Data’s architecture, workflows, and its interaction with Wikidata.  
  - Discuss project expectations and milestones with mentors.  
  - Identify key data structures in Wiktionary relevant for translation and synonym extraction.  
  - Analyze how Wiktionary organizes translation and synonym data across multiple languages.  

- **Week 2:** Framework Designing  
  **Objective:** Outline the data fields needed for translations and synonyms, focusing on multilingual support.  
  - Design a framework for parsing Wiktionary dumps, ensuring compliance with its licensing requirements.  
  - Begin drafting potential queries and scripts to interact with Wiktionary data.  

---

## Phase II: Translations  
**WEEK 3 + WEEK 4**

- **Week 3:** Develop Translation Command Framework  
  **Objective:** Build the foundation for the translation command.  
  - Start developing SPARQL queries/.py scripts to fetch translations from Wiktionary for various languages.  
  - Implement a basic translation command using this data within Scribe-Data.  
  - Create a structure for storing translations in the appropriate Scribe-Data format.  
  - Expand the translation command to handle more languages and complex translation cases.  

- **Week 4:** Refining Translation Commands and Testing  
  **Objective:** Optimize and test the translation functionality.  
  - Optimize the SPARQL queries for efficiency, ensuring they handle large-scale datasets without performance issues.  
  - Begin unit testing to ensure the accuracy of translation outputs.  
  - Review progress with mentors to refine the approach.  
  - Develop additional unit tests to cover edge cases and language-specific nuances.  
  - Ensure translations are formatted properly for use within Scribe-iOS and Android apps.  

---

## Phase III: Synonyms  
**WEEK 5 + WEEK 6**

- **Week 5:** Develop Synonym Command Framework  
  **Objective:** Begin work on synonym extraction from Wiktionary.  
  - Analyze the structure of synonym data in Wiktionary.  
  - Draft SPARQL queries to fetch synonyms from Wiktionary for different languages.  
  - Implement the synonym command within Scribe-Data, ensuring it interacts correctly with the translation command.  
  - Expand the synonym command to support more languages and complex synonym relationships.  

- **Week 6:** Integration and Testing of Synonym Commands  
  **Objective:** Finalize synonym extraction and ensure its functionality.  
  - Refine SPARQL queries and optimize their performance to handle large datasets.  
  - Begin writing and implementing unit tests for the synonym command, focusing on edge cases like homonyms and multiple meanings to ensure synonym data is accurate and efficiently retrieved.  
  - Test the integration of synonym data with other components of Scribe-Data, ensuring compatibility with Scribe-iOS and Scribe-Android apps.  

---

## Phase IV: Enhancements in Translations and Synonyms Functionality  
**WEEK 7 + WEEK 8 + WEEK 9**

- **Week 7:** Parsing and Data Processing Improvements  
  **Objective:** Improve the efficiency of data parsing and processing.  
  - Work on parsing Wiktionary dumps efficiently, ensuring that large datasets can be processed quickly.  
  - Implement improvements to the overall data processing pipeline, focusing on memory management and speed.  
  - Begin documenting the workflow for parsing Wiktionary data and integrating it into Scribe-Data’s architecture.  
  - Review the progress with mentors and make necessary adjustments.  

- **Week 8:** Expanding Language Support for Commands  
  **Objective:** Broaden the scope of languages supported by both translation and synonym commands.  
  - Add support for additional languages based on priority and user demand.  
  - Refactor existing code to ensure it is adaptable for various language structures (e.g., agglutinative vs. inflectional languages).  
  - Continue to improve unit tests, focusing on new languages and ensuring no regressions in functionality.  
  - Test the expanded language support in collaboration with Scribe-iOS and Scribe-Android teams.  

- **Week 9:** Bug Fixes and Optimization  
  **Objective:** Ensure stability, fix bugs, and optimize performance.  
  - Identify and fix any bugs encountered during testing and user feedback sessions.  
  - Perform extensive code review and refactoring, focusing on code readability and maintainability.  
  - Optimize the performance of SPARQL queries and ensure smooth integration with the rest of the Scribe suite.  
  - Finalize documentation for the translation and synonym commands, ensuring it is easy to follow for future contributors.  

---

## Phase V: Testing and Platform Integration  
**WEEK 10 + WEEK 11**

- **Week 10:** Final Testing and Cross-Platform Integration  
  **Objective:** Conduct full-scale testing and integration with Scribe-iOS, Android, and Desktop apps.  
  - Perform end-to-end testing of both the translation and synonym commands within the broader Scribe ecosystem.  
  - Ensure that the commands function seamlessly across Scribe-iOS, Android, and Desktop.  
  - Collaborate with app developers to test how the data is consumed on different platforms and make necessary adjustments.  
  - Fix any remaining bugs and improve the user experience based on feedback.  

- **Week 11:** Final Testing and Cross-Platform Integration  
  **Objective:** Conduct full-scale testing and integration with Scribe-iOS, Android, and Desktop apps.  
  - Perform end-to-end testing of both the translation and synonym commands within the broader Scribe ecosystem.  
  - Ensure that the commands function seamlessly across Scribe-iOS, Android, and Desktop.  
  - Collaborate with app developers to test how the data is consumed on different platforms and make necessary adjustments.  
  - Fix any remaining bugs and improve the user experience based on feedback.  

---

## Phase VI: Conclusion  
**WEEK 12 + WEEK 13**

- **Week 12:** Final Enhancements and Documentation  
  **Objective:** Polish the project and finalize all documentation.  
  - Implement final enhancements based on user testing and mentor feedback.  
  - Complete the technical documentation for both translation and synonym commands, including code comments and usage examples.  
  - Write a user-facing guide for integrating these commands into Scribe’s apps.  
  - Conduct final performance tests to ensure everything runs efficiently.  

- **Week 13:** Project Wrap-Up and Final Submission  
  **Objective:** Finalize all deliverables and ensure smooth project closure.  
  - Share the final version of the project with the broader Scribe community for review.  
  - Conduct a demo or presentation of the translation and synonym commands to mentors and other stakeholders.  
  - Engage with the community to gather feedback and ensure future maintainability.  
  - Document community feedback for possible future improvements.  
  - Address any last-minute feedback or minor issues.  
  - Ensure all contributions are well-documented and prepared for handover to the Scribe community.  
  - Participate in a final retrospective meeting with mentors to reflect on the project and learnings.  
  - Celebrate project completion and prepare for future contributions to Scribe or similar open-source projects.  
  - Write a blog article summarizing all work done.  

---

## Afterward of Internship
- As a part of community and fully aware of implementation will continue contributions to Scribe-Org.
- Actively participate in the Scribe and Wikimedia community.
- Maintain code and documentation, and mentor beginners.
---

## Other Deliverables during the Internship
- Weekly blog posts on internship progress/experience/Tasked/feature implemented.
- Blog posts about experiences with the open-source community and the Scribe-Org.
- Regular communication with mentors and other community members.
- I love to help fellow peers who really like to do something, will help them to make learn and aware about this Extra curriculam impactfull things!

---
## About Me
I am Recently Graduated Student with Bachelor's degree in Computer Science & Engineering from G H Raisoni Insitute Of Engineering & Business Management, North Maharashtra University, Jalgaon. Since then i am on learning quest and upskilling my self to get full time job in information technology. I keen interest are into Python, Java, cloud technology, Devops, openSource contributions along side I am trying to learn ReactJS. 
I have participated and won some hackathons Hosted by MLH and continue to do so in free time, this help me learn and understand the implementation and learning of new things and integration while building.

---
## How did I learn about Outreachy?
Ecosystem over here is only about therotical learning and examination score! As the location of my education and college are in the city which is not so well technology aware, we can say most of the peoples here are Farmers, small scale business and factories. But the issue of staying in touch with latest tech updates and connection and sharing was smoothly solved with linkedin and internet. There over linkedin i got to know about most of opensource programs, after that i searched and viewed some videos over youtube regarding the same. I was not confident enough to apply and Self-doubt will i be able to do this. Then last time I applied for the initial application but it was rejected, but again this fall i applied and got main `you are selected as intern!` This was quite an experience and milestone for me!

---

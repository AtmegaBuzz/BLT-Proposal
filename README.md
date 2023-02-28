
# **Mentors**

	Donnie
	Aryan Ranjan

# **Personal Info**

**Name:** Swapnil Shinde

**Email:** swapnilshinde9382@gmail.com

**TimeZone:** India (UTC +5.30)

**GitHub:** [AtmegaBuzz](https://www.github.com/AtmegaBuzz)

**Slack:** AtmegaBuzz

**University:** Savitribai Phule Pune University

**Current Year:** 2nd Year (Expected Graduation : 2025)

**Degree:** Bachelor of Engineering (BE) in Computer Science

# About Me

I'm currently pursuing a BE (bachelor of engineering) in Computer Science at Savitribai Phule Pune University in India.
I started learning Python programming in my first year of college and later started learning backend programming and became familiar with frameworks like Flask and Django, Along with studying front-end programming using JavaScript libraries such as React, Next, and React-Native. I have expertise unit testing Python code using pytest and Selenium and enjoy learning about backend programming, cyber security, and low level system concepts. Additionally, I worked as the MLH Fellowship's prep fellow, where I and the other fellows learned the basics of contributing to open source.


# ABOUT ME & WHY I CHOSE THIS PROJECT

Ever since I began learning computer science, open source has been a huge source of passion for me.
I've always wanted to give back to the community, and by participating in GSOC, I'll gain exposure to opensource projects that are ready for use in the industry and receive mentoring on how to write software with clean code and use design paradigms and patterns from mentors with a lot of experience in open source. They can help me along the way and advance my opensource journey by pointing me in the correct direction.

I'm choosing OWASP for a particular reason. The majority of the tools I used when I first began learning about cybersecurity ZAP, Top 10, etc were from OWASP, and OWASP Top 10 helped me understand and learn about the top 10 web vulnerabilities.
The advancement of cybersecurity technologies, in my opinion, is also essential for helping businesses secure their networks. The importance of information security has increased considerably in recent years.
I believe that by making a contribution to OWASP, I will be able to contribute to this crucial area, which many people are unaware of and lack access to.

I choose BLT Project because I like the overall idea of reporting bug's found on the internet and anyone could report it by tagging the organizations which will be incentivized.
Also BLT aligns with my Stack i.e Django, Javascript, Blockchain.I also have a bit of understanding in blockchain (Bitcoin-core) and this project will help me improve my skills on stack listed above.


# Contributions in OWASP

I have started contributing to OWASP and contributed to projects **BLT, PyGoat, Threat-Dragon**.(add links) In Project BLT in total I have [54 merged BLT pr's](https://github.com/OWASP/BLT/pulls/AtmegaBuzz) , [14 solved BLT issues](https://github.com/OWASP/BLT/issues?q=assignee%3AAtmegaBuzz+is%3Aclosed+) and [13 raised BLT issues](https://github.com/OWASP/BLT/issues/created_by/AtmegaBuzz).

# **Project Details**

## BLT Frontend

Current BLT website has a lot of bugs and the UI implemented is not polished. As mentioned in the issue [New Design #696](https://github.com/OWASP/BLT/issues/696).
 I’ll be implementing the new designe’s of the following pages using Tailwind CSS.  


- ### Home Page

	Current home page does not contain a leaderboard for Top company, Top Testers and Recent Bugs.
	Adding the most popular bug section. In this section users can easily find the most trending bug and this will be filtered by the amount of likes and comments in the Bug from the backend.

	<br>
	<img src="/media/leaderboard.png"/>

- ### Start Bug Hunt Page

	Old start bug hunt page does not look so polished. Creating a new Bug hunt page with polished UI and background.
	
	<br>
	<img src="/media/bughunt.png" />

- ### Company Dashboard Page

	After registering the Company, the User will become admin of that domain and company. Users will see all their registered companies in a user’s company page and will be directly able to manage all the companies and add multiple users to manage the company and domain.

	<br>
	<img src="/media/company.png"/>


## BLT Backend

- ### API's for BLT Flutter

    - **Documentation and Testing (**[Django's Unit Test](https://docs.python.org/3/library/unittest.html#module-unittest)**)**
      - Providing good documentation makes it easy for contributors, consumers and maintainers to understand the functionality and maintain the project in the long run.
      - The API Documentation will be done in Swagger due to its simple UI and easy to understand API format.

      - Creating tests for the API’s is a key part in maintaining the project. It will help maintainers catch any bug’s early before deploying the project and ensure that BLT Flutter doesn't go down due to API failure.


    - **API Rate Limiter:**
      - To protect our backend from abuse, integrating an API rate limiter is an essential part. This will help in limiting the API calls per user. Thus protecting the Backend from bot's and scripts trying to access BLT data.
      - Best tool which fits the case is Django-Rest-Frameworks [API Throttling](https://www.django-rest-framework.org/api-guide/throttling/)
      - Image given below gives a better understanding of how Django REST API Throttling works.
	<br>
	<img src="/media/throtelling.png"/>


- ### Proof of Stake Coin (BACON Coin)

     - Giving rewards to bug hunters/reporters will boost their morale and give them motivation to participate more in Bug Hunting programs.
     - The plan is to integrate [Bitcoin-POS](https://github.com/BitcoinP0S/bitcoinpos) which works on Proof of Stake consensus algorithm to avoid the power consumption as compared to Proof Of Work (PoW) consensus.
     - **Reason** behind implementing our own chain is to make faster transactions and we will be the governing Authority.
     - This coin can be integrated with future ideas of exchanging the coins with merch or discounts in our premium programs.

	<br>
	<img src="/media/bitcoin.png"/>

- ### Private Issue Reporting

    - Some bug's can be crucial and cannot be displayed in public.
    - Allow companies to launch a private bug hunting program in which all the bugs reported by the hunters will be private by default and only the company which the program belongs to can see those bugs/vulnerabilities found.
    - Allow users to tag an organization to make the bug/issue found private and only accessible by the organization/company
   
	<br>
	<img src="/media/private.png"/>

# PROPOSED TIMELINE

## Commitments
My university will not be providing any sort of vacation due to disturbance in academic timeline because of the Corona Pandemic, but the attendance is not mandatory thus I will be able to provide 40 hrs per week. I might have exams between June-July, but I'm targeting a minimum commitment of 20hrs per week.
**The proposed duration of the project is 350 hrs.**


## Timeline

- ### **Before May 4**
	- Study about BLT core 
	- Get good understanding of the problem statements
	- Research about Bitcoin-POS 
	- Ask questions

- ### **May 4 - May 28**
	- Interact with mentors and community members.
	- Review/revise the design.

- ### **May 29 - June 20**
	- Implementing and Integrating new Frontend UI designs of Home, Start Bug Hunt.

- ### **June 20 - June 25**
	- Work on Company Profile Page and integrate with BLT Backend.

- ### **June 26 - June 4**
	- Implementing Private Issue reporting.

- ### **June 4 - July 10**
	- Start working on API rate Throttling/Limiting.

- ### **July 14**
	- Evaluation Phase 1
	
- ### **July 14 - July 20**
	- Start learning about Boitcoin-POS and required Blockchain concepts about Proof of Stake (POS) 
	- Learn how to create an independent chain by changing the genesis block.

- ### **July 20 - Aug 15**
	- Finish collecting information about the implementation.
	- Start creating the independent chain and create a bitcoin hot wallet and integrate the chain with Backend.
	
- ### **Aug 15 - Aug 21**
	- Finish some leftover work, document and write tests for the API’s 
	
- ### **Aug 28**
	- Evaluation Phase 2


# Deliverable's
- Evaluation Phase 1

	- **Home Page**
	- **Start Bug Hunt Page**
	- **Company Profile Page**
	- **Feature Private Issue Reporting**
	- **API rate Throttling/Limiter**

- Evaluation Phase 2

	- **Reward System using Bitcoin-POS**




# Why me?

Being a very enthusiastic individual in the CyberSec and open source fields, I enjoy learning about technology regardless of how difficult or simple its design is to implement.
I have a good foundation in integrating Full Stack solutions and I have almost 2 years of experience with frameworks like Django, Flask, and React. I am also skilled at developing and implementing APIs and have a basic understanding of blockchain concepts and mainnets including Bitcoin, Ethereum and Solana.

# After GSoC

I believe that once my GSOC is completed, I will know the codebase like the back of my hand and be comfortable making significant improvements to the project.
I will therefore contribute to OWASP BLT and other OWASP projects and attempt to put new ideas into practice.
If possible I will also try to maintain BLT and increase community engagement of BLT by posting about BLT on socials.

# References

- [https://owasp.org/www-community/initiatives/gsoc/gsoc\_sat](https://owasp.org/www-community/initiatives/gsoc/gsoc_sat)
- [https://owasp.org/www-community/initiatives/gsoc/gsoc2023ideas](https://owasp.org/www-community/initiatives/gsoc/gsoc2023ideas)
- [https://github.com/OWASP/BLT-Flutter](https://github.com/OWASP/BLT-Flutter)
- [https://github.com/owasp/blt/](https://github.com/owasp/blt/)
- [Figma Designs](https://www.figma.com/file/s0xuxeU6O2guoWEfA9OElZ/Design)


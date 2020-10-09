---
title: "Rating The Best Cyber Security Hiring Approaches"
date: 2020-10-04T00:00:00-00:00
draft: false
---

This is a cross-post from the [Security Goose Blog](https://securitygoose.com/blog/). Security Goose is a web application I created for screening cyber security job candidates with online technical assessments. It currently has 0 users. I work on it in my free time.  
&nbsp;  
&nbsp;  

##### Imagine you have 100 people in a room. They all want to work for you in the single cyber security position you have open. How do you pick the best person?

The tech industry created technical interviews as an answer to this problem. The goal is to find the best candidate for a role by judging technical skill at scale. False negatives are acceptable, but false positives can be costly. Companies that get many applications can afford to pass on some good candidates. There will always be another good candidate in line. Hiring the wrong person, on the other hand, can cost the company tens of thousands of dollars.  
&nbsp;  
There are many methods that people use to find the ideal cyber security candidate. The best approaches are both accurate at judging technical skill, and can be used on a large candidate pool.  

![Accurrate vs Scalable Cyber Security Hiring Approaches](/img/blog/tech-assessment-matrix1.png)  
When considering a hiring strategy, think about how it fits into this matrix.  
&nbsp;  

#### College GPA

Rating:  *scalable, but not accurate*  
For comparing new grads, GPA is a simple metric that applies to all candidates. You can use it on a large group of candidates, but it is not a good predictor of technical skill. If a student gets a C in History, it hurts their GPA but doesn’t indicate anything about their computer skills.  

#### Free-for-all Interview Quesions

Rating:  *not scalable, not accurate*  
Companies rarely spend significant time honing their interview questions for cyber security positions. It's far easier to ask a few random engineers to handle onsite interviews. The engineers come up with their own questions, which creates a varying interview experience. Some engineers ask high-level questions about the candidate's background. Others probe deeply into the candidate's technical knowledge. And some engineers resort to asking security trivia questions like, "What port does X service run on?"  

It's horrible. Without standardization, it's impossible to compare candidates. The lack of standards means engineers assess candidates based on subjective impressions. That biases the selection process toward confident candidates. Of course, the ability to communicate matters. However, this approach skews the results toward candidates who **sound like** they know what they're doing rather than ones who actually know what they're doing.  

#### Job Experience

Rating:  *somewhat scalable, accuracy varies*  
By looking at someone’s resume, you can see if they have done what you’re looking for before. If they have, hire them to do it again for you. Simple.  

I wish it was that easy. It’s hard to tell from a resume how much someone contributed to a project versus how much their team members contributed. What if you’re hiring for a task somewhat related to a task they have done before, but you’re not sure how much of their skills will translate?  

#### Referrals

Rating:  *works if you have more friends than me*  
Hiring based on someone’s reputation in your own network is a tried and true method. You don’t have to burden yourself with judging someone’s technical skill because your trusted friend did that for you. The only limitation is the size and quality of your network. What if the best candidate for a position is outside your network? What if someone refers their acquaintance, but they aren’t sure about their skill level?  

#### Take-Home Projects

Rating:  *accurate for individuals, not scalable*  
The best way to see if someone is good at a task is to watch them actually do it. Some companies will assign a small take-home project related to the work that they expect a candidate to do. They often compensate candidates for time spent on the project. Even though this method is a great way to judge someone’s technical skill, it takes too much time and money to assess 100 candidates.
Comparing candidates can be tricky with take-home projects. To compare candidates accurately, the project needs to be the same between them. It's one thing to pay someone to complete a feature that you already planned on making. It's another to pay someone to complete a project that doesn't benefit the company directly.

#### Whiteboard Coding Questions

Rating:  *decent for developers, terrible for cyber security positions*  
Whiteboard coding questions are like the SAT for developers. The SAT material isn’t the material that students learn in college. It’s related material that can be tested in a scalable way. Motivated students study for the SAT. They buy practice books with answers and even hire tutors. Some developers take a similar approach, studying for whiteboarding questions. They read Cracking the Coding Interview and practice [Leetcode](https://leetcode.com/) in their spare time. Like studying for the SAT, the strategy works.  

Some people argue that the developers who practice Leetcode show effort. They claim practicing is evidence that they will give the same effort to their job. I’m not convinced. Even if it was true, judging effort isn’t the goal of technical interviews. Remember, the goal is judging technical skill at scale.  

Still, candidates need some amount of technical ability to pass whiteboarding questions. You get to see how candidates approach a problem, even if they don’t solve it. In the absence of a better method, this might be the best option for screening **software engineers**.  

Unfortunately, whiteboarding questions fall short when applied outside of software engineering...  

![Cyber Security Skills vs Development Skills](/img/blog/SecurityVSDevelopment.png)  
You’re testing for this when you ask whiteboard coding questions to security candidates*  
&nbsp;  

There is some overlap between development skills and security skills. It might not be what you’re looking for though, and whiteboarding questions don’t test it.

#### Capture the Flag Challenges

Rating:  *scalable and accurate, perfect for cyber security positions*  
CTF (Capture the Flag) challenges are the best scalable test of cyber security skill. They can be a snapshot of something you do on the job. Hiring a Penetration Tester? Create a challenge where the candidate has to exploit a vulnerable system. Hiring a SOC Analyst? Give the candidate some malicious network traffic to analyze. Their performance on the challenge correlates with their performance on the job because the challenge **IS** the job.  

The downside is running these challenges can come with significant overhead costs. You have to dedicate time to create realistic challenges. Setting up the infrastructure to support giving all candidates the challenges is hard. I created [Security Goose](https://securitygoose.com) to solve that problem. [Security Goose](https://securitygoose.com) is a platform where companies can screen cyber security job candidates using CTF-style challenges. There is a question library of pre-made challenges. You get to spend more time doing what you care about rather than setting up cyber security technical assessments.

![Accurrate vs Scalable Cyber Security Hiring Approaches with Details](/img/blog/tech-assessment-matrix2.png)  
[Try Security Goose for free](https://securitygoose.com/employers/sign_up) to get your cyber security hiring approach to be both accurate and scalable.  

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
*This diagram isn’t perfect and there is a small overlap in every sub-discipline. That doesn’t mean you should test for it.  

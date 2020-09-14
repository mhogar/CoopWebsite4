# Work Term 4+5: Camis

## Abstract

This website is about my (Ryan Stamp's) fourth and final co-op work term: the company, my experience on the job, and most importantly, the goals I had going in and the skills I took away. By reading this website, I hope you, the reader, learn something about my experience at Camis, and hopefully get inspired to figure out what you might want to take away from your future endeavors.

## Company and Products

Camis is a company that makes reservation and accommodation software for campgrounds. Their clients consist of many provinces in Canada and a few American clients. For a full list, visit
<a href="http://goingtocamp.com/">goingtocamp.com.</a> 
Camis' main product is the reservation software, but also provides hardware and a call center to clients. The software has gone through many versions, from the older (mostly legacy now) "Everest" software to the newer Camis 5. The software itself takes many forms and UIs, but the main ones being the desktop applications for in park and call center use and the website that campers interact with directly.

## Locations

Camis' main office is in Guelph, but they also have a few offices in the states, those being in Ann Arbor, Cumberland, and Kenosha.

## Culture and People

Overall Camis has a fantastic culture and atmosphere. Although most of my work term was spent working from home, I would still say the culture held up. The company held several distance events such as a photo scavenger hunt and a fully remote hackday. This along with the employees themselves creates a very welcoming environment, well still managing to keep productivity high. Often there will be demos and presentations to show the employees working in a different field what is going on in other places in the company. Overall, I found these very informative and interesting.

## Job Description

### Job Overview

Unlike my previous work term at Camis, my job this time around concentrated entirely on the newer Camis 5 software. In the software itself, I mainly focussed on the sale feature. This included the UI and processes for selling a product, but also the areas of the software for configuring products. Most of my work was done in the desktop app which is written in C#. Additionally, during July, I changed to a different squad that focussed on the booking aspects of the software, such as the reservation workflow and the various configuration aspects that are involved with that. On this squad, I worked a lot more on the web application than I did on the previous squad. The web app uses the angular framework and is primarily written in typescript.

### Skills on the Job

Since I have worked for Camis during a previous work term, I found myself getting up to speed rather quickly. I was pleasantly surprised by how much I remembered from nearly 2 years ago and how easily I was able to apply it. That being said, there were still some skills I had to learn on the job. Notably, this time around I was using git for source control as opposed to TFS. Although I do have plenty of experience with git, I had never used bitbucket before so that was something I did have to learn. I also had to learn typescript and angular, neither of which I had ever used before. They had a learning curve to them, and I would say I struggled with them the most in the beginning. But with many things, practice makes perfect and I found myself confidently writing new features for the web app by the end.

## Learning Goals

### Learning Goal 1

The first goal for my first term was to learn and be a part of the stages of developing large features, from idea conception to production deployment. I thought it would be an interesting subject to experience that I have not had an opportunity to learn in past work terms due to their shorter length. I continued to work on this goal over the entire 8 months, but I still reflected on what I had learned during the first half. During my work term, I had the chance to be part of implementing a rentals feature into the software. However, due to some mismanagement and various other issues, the feature barely got past the planning phases so I did not get a chance to learn about the 2nd half of the feature delivery process. Although, that was not a total loss as more time spent in the planning phases allowed me to learn more about them than I might of otherwise. I got to learn about requirements gathering where all the team members should be present and the problem is described so requirements can be generated. I also learned about implementation brainstorming meetings, which are more dev focussed, where software solutions are discussed and higher up devs can also be brought in for more experienced input. In the end, although I did not get a chance to learn about the entire process, I did get to learn a lot about the first half and I continued my learning about the second half in the next four months.

### Learning Goal 2

The second goal for my first term was to learn techniques for managing and developing large software systems. I got to learn about unit testing and design pattern techniques. I learned how to use mocking in my unit tests to mock dependencies and allow the testing of complex algorithms. I gained experience with dependency injection where dependencies are specified through interfaces and their concrete implementations are supplied by another class. This is particularly effective as it allows for implementations to be swapped out easily and massively increase code reuse. However, I did not get to learn much about Camis' CI pipeline as I had wished. Teachings about the pipeline were planned, but it was difficult to find the time where the people capable of teaching were available. Also, the pipeline went through some major changes towards the end of the term so that made learning about the old pipeline a little pointless. In the end, the teachings were postponed to the second half of the work term, which I will reflect on in a later goal. Overall, learning how to manage these types of projects is an essential skill in any development job and will be useful for my future careers and personal projects.

### Learning Goal 3

The final goal for my first term was to continue to improve my communication. This has been an on-going goal across multiple work terms and is the area I feel like I struggle in the most. During the term, I felt like I had improved my communication and overall confidence.  I feel like I was never afraid to reach out for help when needed it or give it if I was able. In meetings, I didn't often say much, but the times I did speak up my manager had said it was always relevant and useful. One area I didn't get the chance to improve in much was in code review, which became a focus for one of my goals during the second term.

### Learning Goal 4

The first goal of my second term was to continue to learn and be a part of the stages of developing large features. In my first term, I only really got to learn about the planning phases, so this time I focussed my learnings on the later stages. However, similar to my first term, various delays prevented me from seeing the rentals feature through to completion, but I did get a lot more experience with the implementation process. This time I learned about UX designers' roles in implementation, where they will create mocks that developers then use to guide them in coding the feature. Various implementation strategy meetings can also take place at this time to brainstorm ideas on how to satisfy the mock using the existing system. Overall, although I didn't get a chance to experience every stage of the process first hand, I would say I learned a lot about how the various stages function and just how many different people are involved and how much work goes into and completing a feature.

### Learning Goal 5

The second goal of my second term was to continue to learn techniques for managing and developing large software systems. This time I focussed my learning on the CI pipeline and types of testing other than unit testing. During the term, I learned about the CI pipeline and how it maintains the project by building and performing various quality checks on each commit that's pushed. Examples of the things it does are running unit tests, calculating code coverage, and detecting code smells. It is also smart in how it functions by only building parts of the project that have been affected by the changes. Overall the pipeline can make sure the code pushed to the main branch meets the quality criteria expected. In terms of testing, I did get the chance to write some integration tests. I learned how they can be used to test code that relies on various services, such as a database, that regular unit testing could not test alone. I also learned how end-to-end testing is used to test the entire system. That is, by interacting with the same UI as users would. One disadvantage I learned about them, however, is just how frail they are. They heavily rely on the specific implementation of the UI and can break easily if it changes without updating the tests. Overall these other types of testing are useful and can test things regular unit tests cannot, but their disadvantages show that standard unit testing is still needed.

### Learning Goal 6

The final goal of my second term was to continue to improve my communication. This time I mostly focussed on code reviews to improve my communication, as that is the part of my original goal that I felt like I completed the least. During the term, I actively participated in code review, even more than I initially expected. This was mostly due to temporarily switching squads. This new squad was much larger and therefore had PRs being created more often. I felt like I improved in my confidence for leaving feedback and I was even thanked for my feedback in some cases. I also got the chance to demo some of my work to the company during an internal demo and a hackday event. I was definitely nervous, but I think I did well overall and I now feel more confident doing it again in the future. That is particularly beneficial since showing off your work to others will be an important skill to have going forwards.

## Conclusion

For my final work term, I am glad I got a chance to work for Camis again. Seeing how the company has changed over a couple of years since I were last there was cool to see. I was also pleasantly surprised just how quickly I got up to speed, despite the work this time around being quite different. Although I would say my biggest takeaway from this work term, however, is that there is always more to learn, even if it's a place you've been to previously. All in all, my coop journey has been full of great experiences and I will make sure to use all that I have learned in my future careers.

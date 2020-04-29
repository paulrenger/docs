# Welcome to tutify.org! 👨‍🏫

We're happy that you're interested in becoming part of our tutify community!

**TL;DR**
Tutify is an international open source community built by local partners to connect tutors and tutees. 
Please visit tutify.org to see if a Tutify partner is already available in your country. If no Tutify partner is operating in your country yet, feel free to start building a Tutify partner platform right now.

Let's start with giving you a brief overview of our concept, the code and everything that is important to know for now. 

## Concept
Education should be available to everyone. We, as Tutify Community, are building a platform to bring free tutoring from tutors to tutees to your country. 
The goal is not to provide a concurrence to many video/chat platforms/exchange forum, but rather to digitally establish a connection between university and school students. Then, the students support the pupils: how the exact tutoring looks like is left to each learning couple.
Tutify provides the infrastructure, to establish the connection, ensure security with the screening process and a user profile site with basic actions.

The main idea of tutify is the following:

Both pupils and students register on the platform with their name and an e-mail address. In addition, the subjects in which the pupil needs help or in which the student would like to offer help are listed there. These subjects do not necessarily have to be the same as the student's subjects in university. 
Next, the students are invited to a personal, digital screening interview. In these interviews, the students are tested for basic technical and educational skills and are familiarised with the values such as the Tutify code of conduct to prevent misuse of the platform. 
Afterwards, suitable learning pairs are formed using a matching algorithm and both sides are informed about the learning partners found. For digital learning support, Tutify provides a personal Jitsi link, with which video conversations can easily take place directly via the browser on the computer or via an app on mobile devices. In an initial digital meeting, precise teaching content is discussed and the further procedure clarified. In the further course of the project, however, students and pupils are free to choose the digital way in which they would like to network with each other. 
In order to prepare the students for digital learning support in the best possible way, guidelines are also provided for the discussions, in which both pedagogical tips and technical support are offered. Afterwards, the students coordinate the lessons independently and to the extent that it is useful and possible for both parties. Motivated students also have the opportunity to request and support other students in a user area.




## Tutify Screening
One essential step takes place between the registration from students and their actual matching - the so-called “screening”. The whole idea is that as a platform, which connects scholars with students we are responsible for that connection and gotta prohibit abuse of our service as good as possible. 

The current draft of our screening guidelines can be found [here](https://docs.google.com/document/d/15UIHRmB7yaaFyUVdFGxb81eoyQRiKCa8jRuxXFN9jLg/edit?usp=sharing).

The next step is to give a brief overview of our code. 

## Code
The code to run a tutify.org platform consists of differnt parts which are structured like the following
* **Screening Tool** – a tool that is used to verify tutors (university students) via an internet video identity check
    * _Backend_ which provides the API and acts as a bridge between the following two components...
    * _Tutors Frontend_ which is the frontend part that the tutors use in the verification process
    * _Screener Frontend_ which is the frontend part that the screeners of a tutify-organization use to verify tutors
* **Matching Algorithm** – a complex and highly optimized mathematical algorithm that is used to do matchings between tutors and tutees. 
* **User platform** – sophisticated platform where tutors and tutees can manage their matches, data etc. and which is protected via a login process. 
    * _Backend_ which provides and API and manage emails, user data etc. 
    * _User platform_ which provides the web frontend

You can find all the code [here](https://github.com/corona-school).

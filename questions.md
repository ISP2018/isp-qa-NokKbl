# Questions

**Q1:** According to *PAD* Tip 11 "Let Design Guide, Not Dictate", classes are described in terms of the CRC card design method, what is the CRC stand for? (Choose the best answer.)

:white_circle: Contents, References, Collaborators </br>
:white_circle: Class name, Responsibilities, Collaborators </br>
:white_circle: Contents, Requirements, Code </br>
:white_circle: Concepts, Responsibilities, Comments

</br>

**Q2:** What are the reasons to do unit testing? List at least 3 reasons.

</br>

**Q3:** According to The *7 Habits of Highly Effective Programmers* book, if you want to be effective programmers that lift up each other, what do you need to do? (Check all correct answers.)

- [ ] Read as many technical books as you can.
- [ ] Listening to teammates.
- [ ] Chatting with people.
- [ ] Learn how to use Docker and develop Graph APIs.
- [ ] Really understand the colleagues.

</br>

**Q4:** According to container management in *Docker in Production* book, what are 3 major locations to store the images you are creating? List and shortly describe each of the locations (How it runs? and when do you use it?).

</br>

**Q5:** According to Prototypes and Post-it Notes in *The Pragmatic Programmer* book, why should we use prototypes?


# Answers

**A1:**

:white_circle: Contents, References, Collaborators </br>
:radio_button: Class name, Responsibilities, Collaborators </br>
:white_circle: Contents, Requirements, Code </br>
:white_circle: Concepts, Responsibilities, Comments

> Ref: *PAD* Tip 11 "Let Design Guide, Not Dictate" (pp. 48-51)

</br>

**A2:**

These are some reasons from PAD:
- Unit testing provides instant feedback.
- Unit testing makes your code robust.
- Unit testing can be a helpful design tool.
- Unit testing is a confidence booster.
- Unit tests can act as probes when solving problems.
- Unit tests are reliable documentation.
- Unit tests are a learning aid.

> Ref: *PAD* Tip 19 "Put Angels on Your Shoulders" (pp. 78-81)

</br>

**A3:**
- [ ] Read as many technical books as you can.
- [x] Empathic listening to teammates.
- [ ] Chatting with people.
- [ ] Learn how to use Docker and develop Graph APIs.
- [x] Genuinely understand our colleagues.

> Ref: The *7 Habits of Highly Effective Programmers* book, No. 5 "Seek First to Understand, Then to Be Understood"

</br>

**A4:**

There're 3 major locations to store the images, those are

- **Docker Hub** - It's a location that is run by Docker and can contain public and private repositories. We may only want to use Docker Hub when we're testing the containers.

- **Docker Trusted Registry** - It's a location that is also run by Docker but provides the ability to get support from Docker. We'll use this option when we're in a company that uptime is necessary.

- **The locally run Docker registry** - Locally run by ourself to storage images. We'll use this option when we're running containers that store some private data and want to keep the data locked.

> Ref: Container image storage in *Docker in Production* book (p. 4)

</br>

**A5:**

We should use prototypes because we can analyze and ignore unimportant details easily and we also offer chances for correction to get away with incorrect results. Moreover, prototyping is much cheaper and faster to develop than full-scale production.

> Ref: Prototypes and Post-it Notes in *The Pragmatic Programmer* book (pp. 53-57)

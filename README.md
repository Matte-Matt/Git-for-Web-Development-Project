# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Task 1: Set up Project
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [x] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This should contain the link to your completed codepen from part 2 as well as the review questions/answers
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> main).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into main "STUDENT FORK".

## Task 2: MVP
1. fork this codepen https://codepen.io/BritHemming/pen/eYYEoPa?editors=1100
2. You will be marking up all of the HTML and styling it to look like this: https://codepen.io/BritHemming/full/jONmxOm using CSS
* this should be review from yesterday/ extra practice
3. After you are finished please copy the review questions into your .txt file and answer them
4. don't forget to add, commit and push your changes.

## Task 2b: Exit Ticket

Once you begin, you will have 15 minutes to answer the questions [here](https://app.codesignal.com/public-test/M94mbzuHGQoMg6F3e/w9GqZYCQ2YoZZf).

The completion of these questions is mandatory for MVP. However, passing the quiz doesn't affect your standing as a Lambda School student whatsoever. This is Lambda School testing itself! Please answer honestly and to the best of your ability without using external references.

## Task 3: Stretch
Stretch Review questions: 
    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the fix for the box model? 
Stretch Git Tasks
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the main branch.
  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 


1. What is Semantic HTML?  Correct use of HTML that makes sense to both the machines and users
    2. What is HTML used for?  To structure webpages 
    3. What is an attribute and where do we put it?  It is used to define elements and it can be used to include links and values.
    4. What is the h1 tag used for? How many times should I use it on a page? It's used for the title of a page and it should only be used once.
    5. Name two tags that have required attributes 1) Anchor 2) Button 3) Image
    6. What do we put in the head of our HTML document? Typically, as far as tags go; h1-h6, p, navigation, etc. It should be information normally found at the begining of a page. 
    7. What is an id?   An ID is a identifier for a tag, it should only be used once and it;s 
    8. What elements can I add an id to?  Any HTML elenent can have an ID
    9. How many times can I use the same id on a page?   Once per page
    10. What is a class?  Like an ID a class is a identifier however it can be used as much as needed as opposed to the ID that gets used once
    11. What elements can I add a class to?   Any HTML element 
    12. How many times can I use the same class on a page?  As many times as needed
    13. How do I get my link to open in a new tab?   By adding "_blank"
    14. What is the alt attribute in the image tag used for?   It provides alternate info/text incase the intended image is unavailable
    15. How do I reference an id?  # followed by the ID name
    16. What is the difference between a section and a div  A section defines parts of a document and div defines parts of the html and groups them in a container
    17. What is CSS used for?  Styling HTML
    18. How to we select an element? Example - every h2 on the page  By typing the element followed by { }
    19. What is the difference between a class and an id? - Give me an example of when I might use each one  The main difference is that Classes are used for multiple elements while ID's are used for a single element only. As and example I may want to put every paragraph tag in a class to style them all in a similar way, but I would maybe give a ID to a h1 tag or a Image tag to make it look very stylized
    20. How do we select classes in CSS?  This is done by typing " . " followed by the class name
    21. How do we select a p element with a single class of “human””?  p.human { }
    22. What is a parent child selector? When would this be useful?  It's basically the relationship between tags inside a container and the tags that are the contaner themselves. To give a simple example of this I would place Li tags being the child inside of UL or OL tags being the parent. Something done to the parent tags can affect the child tags however it doesn't work the other way around. This is useful in that way that you can style multiple tags nested in parent tags at the same time.
    23. How do you select all links within a div with the class of sidebar? a div .sidebar{ }
    24. What is a pseudo selector?  It's a keyword added to a selector that defines a special state or action
    25. What do we use the change the spacing between lines?  Line-height
    26. What do we use to change the spacing between letters?  Letter-spacing
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?  Captitalize, uppercase, lowercase
    28. How do I add a 1px border around my div that is dotted and black?  div {border-style: dotted;
                                                                                border-color: black;
                                                                                border-width: 1px; }
    29. How do I select everything on the page?  * { }
    30. How do I write a comment in CSS?  /* comment */
    31. How do I find out what file I am in, when I am using the command line?  PWD
    32. Using the command line - how do I see a list of files/folders in my current folder?  LS
    33. How do I remove a file via the command line? Why do I have to be careful with this?  RM  you want to be careful because this action will not be followed by a confirmation, it will just delete the selected file immediately
    34. Why should I use version control?  Because it moderates file information such as any changes and previous versions of a file
    35. How often should I commit to github?  Often, I think it should be done whenever you finish anything notable 
    36. What is the command we would use to push our repo up to github?  git push -u "file-name"
    37. Walk me through Lambda's git flow.   1. Fork it  2. Invite your collaborator(TL)  3. Clone the repo  4. Create your own branch to work on  5. At this point you should get some work done  6. Add and commit any and all changes made to the repo  7. When done with that you should push the commited changes to github  8. Make a pull request under my branch's name and add my TL as a reviewer  9. DONT MERGE, I don't do that and I believe thats the git flow!

Stretch Questions

    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the "fix" for the box model, in other words, how do we make all elements respect the width we've given them? 

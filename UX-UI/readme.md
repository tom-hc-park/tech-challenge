# UX/UI Candidate Quiz
## Task #1
Your task is to overhaul and improve Ambyint’s landing page, and generate a mock up of the new design.  (Tool of your choice.  For example: Figma, Whimsical, etc)

Go to the landing page on the Ambyint portal.  Here you will see the first page that a client will see.

Generate 5-10 questions that will help you in designing and building the updated landing page to send to Ambyint to answer.

URL: https://qa-portal.ambyint.io/login

UserName: quiz@ambyint.com

Password: \<Sent separately\>

![](Landing%20Page.png)

Present these questions back to your contact at Ambyint.

We will answer your questions and then proceed with making your suggestions / recommendations on what we could do to improve this page.  Explain what you’ve identified, what can be improved, and what you would do differently.

There is no expectation of you to create an HTML page or anything else.  The expectation is that there is an associated mock up with your new design.

## Task #2
Simple Star Wars character app

For every user, we’d like to display a card with the name of each character along with a random picture for each character (see <a href="https://picsum.photos/">Picsum photos</a> for random picture inspiration). Each character card should be colored based on their species and have some kind of animation when the user hovers over the card. When we click on a character’s card, more information should appear in a modal about the character.

In the character details modal, we’d like to display information about the person: name as the header of the modal, height displayed in meters, mass in kg, date person was added to the API (in dd-MM-yyyy format), number of films the person appears in and their birth year. We should also fetch information about the person’s homeworld and display its name, terrain, climate, and number of residents.

In addition to pagination, we’d also like the React developer to implement searching and filtering. To search, the user should enter a character name (partial or complete) and have all matching results returned. For filtration, the user should be able to select either the homeworld, film, or species of any character and see results. Don’t forget to combine the search with filters.

Stretch Goal: Add an integration test for testing the modal opens with the correct person’s information.

API: https://swapi.dev/

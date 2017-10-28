 "FriendFinder" application -- basically a dating app. This full-stack site will take in results from your users' surveys, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.
 Instructions

1.Your survey should have 10 questions of your choosing. Each answer should be on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

2.Your server.js file should require the basic npm packages we've used in class: express, body-parser and path.

Your htmlRoutes.js file should include two routes:


1.A GET Route to /survey which should display the survey page.

2.A default, catch-all route that leads to home.html which displays the home page.
Your apiRoutes.js file should contain two routes:

3.A GET route with the url /api/friends. This will be used to display a JSON of all possible friends.

4.A POST routes /api/friends. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.


#file directory
FriendFinder
- app
  - data
    - friends.js
  - public
    - home.html
    - survey.html
  - routing
    - apiRoutes.js
    - htmlRoutes.js
- node_modules
- package.json
- server.js





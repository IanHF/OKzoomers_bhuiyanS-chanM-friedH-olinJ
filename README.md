# Sportsball Cards by OKzoomers

**Roster/Roles**
- Saad Bhuiyan - `Frontend` (BOOTSTRAP)
  - Handle the frontend
  - Create templates
  - Routing
  - Styling with Bootstrap
- Matthew Chan - `Database Management`
  - Create a package for interacting with the database from backend
  - Continuously modify and update the package along the dev cycle
- Hannah Fried - `Project Manager`
  - Project manager
  - Make changes to repository when necessary
- Jacob Olin - `Backend Development`
  - Handle the backend
  - Handle caching to/from database
  - Search through database
  - send render-able information for Jinja/generally support front-end

**PROJECT PITCH**

Sportsball cards is a platform for:
- Testing your knowledge of your favorite basketball teams, and new ones via trivia quizzes!
- Upon winning said quizzes, winning prize virtual cards!
- Building a collection by card rarity, player stats, and more!
- And once you get that far, trading your cards with your friends!

*Won't you come join your friends and test your knowledge?*

**Nitty-Gritty**

Data retrieved from: [OpenTrivia API](https://opentdb.com/api_config.php), [balldontlie API](https://www.balldontlie.io/#getting-started ), and the [Image results API](https://serpapi.com/images-results ).

THis website should be able to offer users the ability to create accounts and then play trivia games for basketball. The games are run through the trivia API providing things like verification for correct/incorrect answers. The user should be able to win virtual trading cards based on their trivia success, for which the images on the cards come from our images API and the stats come from the basketball API.

Each new quiz generates a new request from the quiz API - then for each new card, the image API and Basketball API provide information to be rendered in a card division within bootstrap.

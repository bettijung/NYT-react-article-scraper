# NYT React Article Scraper
A web app allowing users to search the New York Times Articles API with a custom search criteria and read the resulting articles that render. Users have the option to save articles and read articles as well. MongoDB persists the data. This app is built with the MERN stack.

* Visit the deployed site <a href="https://react-nyt-app-2432545.herokuapp.com/">here</a> .

## View of the app


## Motivation
To create an app for people wanting to search news articles based on specific topics/words and date ranges, and to do so utilizing MongoDB, Express.js, React.js, and Node.js.

## Installation
- Visit the deployed site [here](https://react-nyt-app-2432545.herokuapp.com) for immediate use.
- Otherwise, *fork* and *clone* the GitHub repo to your local machine.
- Ensure that you have *Node.js* and *MongoDB* installed on your machine.
- Retrieve a personal *NYT API key* [here](https://developer.nytimes.com/).
- Start MongoDB locally by opening a CLI and entering ```mongod```. Leave this CLI window open in the background.
- Starting at the root of the repo, go to *client/src/utils/nyt/key.js* and on line 1, replace *'YOURAPIKEY'* with your api key.
- Open a new CLI. Navigate to the cloned directory. Install the npm dependencies and start the server.

    ```yarn install```
    ```cd client```
    ```yarn install```
    ```cd ..```
    ```yarn start```

- NYT Article Scraper runs locally on port 3000. Open your favorite web browser at *localhost:3000*.

## Technologies Used
- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://www.npmjs.com/package/express)
- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/en/)
- [Mongoose](http://mongoosejs.com/)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [Bootstrap](https://getbootstrap.com/docs/3.3/)
- [Axios](https://github.com/axios/axios)
- [React-Router](https://github.com/ReactTraining/react-router)
- HTML5, CSS3, JavaScript

### API Reference
- [New York Times Article Search API](https://developer.nytimes.com/article_search_v2.json)
# wkromar.github.io
Resume Technical Exercise at the beginning of my coding journey displaying my knowledge entering the profession. I came in knowing some C# and HTML and created a basic website displaying my previous experience and accomplishments unrelated to the field. This is more of a bookmark to show how far I have come in 20 weeks and how fast I can continue to grow. I am very proud of this.

# Author
- [Woody Kromar](https://github.com/wkromar)

# Built With
     HTML and CSS
     
     
     ## Deployment

### Heroku Prerequisite
1. Sign up for an account on [Heroku.com](https://www.heroku.com/)
2. Install Heroku CLI by typing `brew tap heroku/brew && brew install heroku` in Terminal

- [Additional installation notes and troubleshooting](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)

> Note: Your project also needs to have a git repository.

Run the following commands from within your project folder.

1. Authenticate by typing `heroku login` in Terminal
2. In terminal, navigate to your project folder and type `heroku create`
3. Type `git remote -v` to ensure it added successfully
4. In terminal, type `git push heroku main`
5. You will need to add a MONGO_URI to your config env on heroku.

## Production Build

Before pushing to Heroku, run `npm run build` in terminal. This will create a build folder that contains the code Heroku will be pointed at. You can test this build by typing `npm start`. Keep in mind that `npm start` will let you preview the production build but will **not** auto update.

- Start postgres if not running already by using `brew services start postgresql`
- Run `npm start`
- Navigate to `localhost:5000`


## Aknowledgments
    - Prime Digital Academy for teaching me Full-Stack Development
    - Dane Smith for his constant support
    - Zhu Cohort for their support and positivity
    - Myself, for having the courage and passion to start this journey with confidence that I would succeed

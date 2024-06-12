
### Resources
- [Tool: Eraser.io](https://app.eraser.io/workspace/E66Ksub1BkDxYb7mGIHT)
- [AWS Tutorial: Building a React App with Amplify, Cognito, and CI/CD with GitHub](https://www.youtube.com/watch?v=ma1FA2be8Ac)
- [Example](https://github.com/tinytechnicaltutorials/amplify-cognito-quiz)
- [Configure the amplify](https://docs.amplify.aws/gen1/javascript/tools/cli/start/set-up-cli/#configure-the-amplify-cli)

### Terminal Commands
Here are the terminal commands in order of appearance of the video.

- Setup the environment
    - npm install -g @aws-amplify/cli
    - amplify configure
    - npx create-react-app client
    - cd client
    - npm install aws-amplify @aws-amplify/ui-react

- initialize amplify config 
    - amplify init
    - amplify add auth
    - amplify push

- Develop the Demo
    - npm start
    - git init
    - git add .
    - git commit –m "Initial commit"
    - git branch –M main
    - git remote add origin <repository URL>
    - git push –u origin main

### Code Files
- App.js: The React application that's configured to use Cognito for authentication
- Quiz.js: The Quiz component
- quizData.js: The hard-coded questions and answers for the quiz

### System design
- [Eraser.io](https://app.eraser.io/workspace/E66Ksub1BkDxYb7mGIHT)

    ```
    // Define groups and nodes
    Amplify [icon: aws-Amplify]
    Cognito [icon: aws-cognito]
    GitHub [icon: github]
    VSCode [icon: vs-code]

    // Define conections 
    Amplify <> Cognito
    Amplify <> GitHub
    VSCode > GitHub
    ```

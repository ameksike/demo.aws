

### Terminal Commands

- Setup the environment
    - npm install -g @aws-amplify/cli
    - amplify configure
    - npx create-react-app client
    - cd client
    - npm install aws-amplify @aws-amplify/ui-react
    - npm start

- Initialize amplify config 
    - amplify init
    - amplify add auth
    - amplify push

- Develop the Demo

    - Create a new repository on the command line
        ```
        git init
        git add .
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/ameksike/tmp.git
        git push -u origin main
        ```
    - Push an existing repository from the command line
        ```
        git remote add origin https://github.com/ameksike/tmp.git
        git branch -M main
        git push -u origin main
        ```

### Code Files
- ```cognito-react\client\src\App.js```: The React application that's configured to use Cognito for authentication
- ```cognito-react\client\src\Quiz.js```: The Quiz component
- ```cognito-react\client\src\quizData.js```: The hard-coded questions and answers for the quiz

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

![eraser](../rsc/eraser.io.jpg)
![amplify.app](../rsc/aws.amplify.app.jpg)

### Resources
- [Configure Amplify](https://docs.amplify.aws/gen1/javascript/tools/cli/start/set-up-cli/#configure-the-amplify-cli)
- [Tool: Eraser.io](https://app.eraser.io/workspace/E66Ksub1BkDxYb7mGIHT)
- [AWS Tutorial: Building a React App with Amplify, Cognito, and CI/CD with GitHub](https://www.youtube.com/watch?v=ma1FA2be8Ac)
- [Example](https://github.com/tinytechnicaltutorials/amplify-cognito-quiz)
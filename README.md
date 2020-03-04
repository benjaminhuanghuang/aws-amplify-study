# aws-amplify-study
## Reference 
  AWS for Developers: AWS AppSync with GraphQL



## Setup
Install aws-amplify/cli
```
  sudo npm install -g @aws-amplify/cli

  amplify configure    # create a new IAM user and input IAM user certification
  # this command will create config and credentials under ~/.aws folder
```

Create React app
```
npx create-react-app amplify-react-app
cd amplify-react-app

npm i aws-amplify aws-amplify-react -S   # install react dependency
```

Initialise a project, execute the command within the root of our project.
```
awsmobile init 
```

Add auth
```
amplify add auth
```

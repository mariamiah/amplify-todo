# Todo Application with AWS amplify

 To-do application that lets you add tasks, see the tasks you added, and  add authentication using AWS Amplify.

## configure amplify

- npm i -g @aws-amplify/cli
- amplify configure
- npx create-react-app amplify-todo
- amplify init (set up the backend)
- amplify add api (setup the graphql api)
- npm i aws-amplify @aws-amplify/ui-react --save
- Modify app to include amplify config
- amplify add auth
- amplify push
- amplify add hosting
- amplify publish
- amplify delete (to delete the amplify application)
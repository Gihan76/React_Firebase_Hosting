# firebase hosting (deploy static website)
create a fresh react project `npx create-react-app Your-App-Name`
create a fresh project in firebase (https://console.firebase.google.com/)
go to hosting page

# install firebase tools
`npm install -g firebase-tools`

# Sign in to google account
`firebase login`

# build the react project to deploy
`npm run build`

# init react project in firebase
`firebase init`

# questions asked in cmd
? Are you ready to proceed? `Yes`
? Which Firebase features do you want to set up for this directory? Press Space to select features, then Enter to confirm your choices. Hosting: `Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys`

=== Project Setup
? Please select an option: `Use an existing project`
? Select a default Firebase project for this directory: `Your Sample Project in Firebase`
i  Using project `Your Sample Project in Firebase`

=== Hosting Setup
? What do you want to use as your public directory? `build`
? Configure as a single-page app (rewrite all urls to /index.html)? `Yes`
? Set up automatic builds and deploys with GitHub? `No`
? File build/index.html already exists. Overwrite? `No`

# deploy project in firebase hosting
`firebase deploy`

# Redeploy static website after changes

`npm run build`
`firebase deploy`


###### hosting URL ########
https://reactfbhosting.web.app
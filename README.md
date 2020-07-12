# react-firebase-starter

An example to deploy a react webapp on firebase hosting.

## Step by step

### How to create a Firebase project
Go to [Firebase console](https://firebase.google.com/). Select the Add Project. And follow the step by step to configure your firebase project.



### Create your webapp
```sh
npx create-react-app app
```

### Setup the Firebase environment
```sh
npm install -g firebase-tools
```

### Add Firebase into your project

Login Firebase with your Google account first

```sh
firebase login
```

To connect your local project to your Firebase project, run the following command from the root of your local project directory

```sh
firebase init
```

### Deploy your webapp

In app directory, build your react webapp

```sh
yarn build
```

To deploy to your site, run the following command from the root of your local project directory

```sh
firebase deploy
```

## Reference
* [How to deploy a react webapp on firebase hosting](https://medium.com/p/41abf06db13d)
* [Firebase hosting quickstart](https://firebase.google.com/docs/hosting/quickstart)

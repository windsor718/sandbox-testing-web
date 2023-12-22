# Sandbox Testing Web
A very simple website template to use for demo purpose.

## Hosting on firebase
Detailed steps are [here](https://firebase.google.com/docs/hosting).  
### Create a firebase project
Create your firebase porject from firebase UI/CLI. You can (optionally) use your existing Google Cloud projects.

### Install firebase CLI
Install the CLI - the detailed steps are [here](https://firebase.google.com/docs/cli#install_the_firebase_cli).
Make sure to login to your account:
```bash
firebase login --no-localhost
```

### Initialize your project
```bash
firebase init hosting
```

### Deploy to your site
```bash
firebase deploy --only hosting
```
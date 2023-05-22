# rosversity_website repo

# Update Website.
- once you update the website and have made all changes in html code need to follow these steps 
open terminal where the project contain then type below comment 
```sh
    firebase deploy
```

# To deploy a website in Firebase, you will need to follow the steps below:

- Create a Firebase project: Go to the Firebase Console and create a new project. You can give it any name you want.

- Install the Firebase CLI: You will need to install the Firebase Command Line Interface (CLI) to deploy your website. You can do this by running the following command in your terminal:
```sh
    npm install -g firebase-tools
```
-Authenticate: Once you have installed the Firebase CLI, you will need to authenticate with your Firebase account. Run the following command in your terminal:
  
```sh
firebase login
```  
- This will open a web page where you can sign in with your Google account.

- Initialize your project: Navigate to the root folder of your project and run the following command in your terminal:

```sh
firebase init
```

- This will start the Firebase initialization process. You will need to select "Hosting" as the Firebase product you want to use and then follow the prompts.

- Configure your site: During the initialization process, you will be prompted to configure your site. You can select the default values for most options, but you will need to specify the public directory where your website files are located.

- Deploy your site: Once you have completed the configuration process, you can deploy your website by running the following command in your terminal:

```sh
    firebase deploy
```

- This will upload your website files to Firebase Hosting and make your site live.

- That's it! Your website should now be live on Firebase Hosting. You can access it by visiting the URL provided by Firebase.



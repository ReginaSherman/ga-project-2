# Project Set Up and Deployment Guide

Make sure to set up your project following the steps listed in this document.

## Scaffold Your Project

1. Change into your `sei/projects` directory with:

  ```bash
  cd ~/sei/projects
  ```

2. Run Create React App to scaffold your project by typing the follow command in the Terminal and replacing where it reads `your-project-name` with your project name.  Use kebab-case (all lowercase with hyphens separating words) and make sure there are **no** spaces or special characters in the project name you choose.

  ```bash
  npx create-react-app your-project-name
  ```

3. Change directories into the newly created project directory:

  ```bash
  cd ~/sei/projects
  ```

4. Create a new file named `.env.local` (the name of this file must be exactly as written here) to store your API keys using the `touch` command in the Terminal:

  ```bash
  touch .env.local
  ```

4. Create your project's code repository on [Github](https://github.com/).

5. Once you've created your repository, copy the code in the section that reads **"…or push an existing repository from the command line"** and paste it in the Terminal.


## Deploying React Apps on Heroku

For this project, we'll be using Heroku to deploy our application.

### Setting Up Your Heroku Account

Before you can configure your project to run in Heroku, you'll need to create an account and install the Heroku CLI by following the steps below. This is a **one time setup** and will not need to be done for future projects.

1. Sign up for a free [Heroku account](https://signup.heroku.com/).

2. Install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) (Command Line Interface) tool for your specific operating system:

  #### Mac OS

  ```bash
  brew tap heroku/brew && brew install heroku
  ```

  #### Ubuntu

  ```bash
  sudo snap install --classic heroku
  ```

3. Once the installation is complete and you're returned to the command prompt, make sure the install was successful by typing `heroku -v`.  This should result in seeing a heroku version displayed in the Terminal.

### Configure Your Project on Heroku

To configure a React application for Heroku, follow the steps below.  This initial set up process must be followed **only one time for your project**.

1. Login to Heroku from the cli by typing:

  ```bash
  heroku login
  ```

2. Make sure you are **in your  local project directory** at the command prompt and if not, use `cd` to switch into your project directory.

  Next you'll create a project in Heroku.  The name of your project in Heroku must be **unique across all of Heroku**.  For this reason,  you may have try several times before you find a name that  is unique.  The project name in Heroku **does not** need to match your Github repository name or your local directory name.  Replace `myapp` below with your project name.

  ```bash
  heroku create myapp
  ```

  If the name is taken, you'll see a message like the following.   Just run the above command again with a different project name.

  ```bash
  Creating ⬢ myapp... !
   ▸    Name myapp is already taken
  ```

  You can also just type `heroku create` and Heroku will choose a random name for your project.

3. Run the following command in your project directory in Terminal to configure Heroku for React:

  ```bash
  heroku buildpacks:set mars/create-react-app
  ```

  You should get a message back in the Terminal that reads:

  ```bash
  Buildpack set. Next release on your-heroku-project-name will use mars/create-react-app.
  Run git push heroku master to create a new release using this buildpack.
  ```

### Deploying Your App

You will **continue to push your code to Github** as normal using:

```bash
git push origin master
```

In addition, when you wish to deploy or update the deployed version of your app, **you will also separately push to Heroku**. The command to deploy or update is:

```bash
git push heroku master
```

Pushing to heroku will kick off all of the build processes needed to create and serve a production optimized version of your app.  This process can occasionally take up to 10 minutes to complete. Once it  is completed, you should see a message that reads:

```bash
remote: https://your-heroku-project-name.herokuapp.com/ deployed to Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/your-heroku-project-name.git
 * [new branch]      master -> master
```

Use the URL that ends in `herokuapp.com` to visit your deployed app!

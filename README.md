# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: React

Let's kick it up a notch and build a modular and modern front end application using React!

Like with project one, the Unit 2 project is a chance to build a project that you can share with  future prospective employers to demonstrate your skills and evolution as a software engineer. You will be working individually for this project, but we will offer office hours and support via the issue queue throughout the project.

For this project, you **must** submit your idea to your squad leader in the form of a [project propsal](https://git.generalassemb.ly/seir-129/project-2#pre-project-deliverable-required) by noon EST Friday.

## Requirements

We'll be evaluating your projects against the following criteria.  Hard requirements are denoted with the terms **must** or **must not**.  Optional requirements use the term **may**.

#### Your app must:
- [ ] **Be a working, interactive, React application.**
  - [ ] It must only use React for DOM manipulation.
  - [ ] It must not produce errors or console logs when used.
  - [ ] It must not display any non-functional actions (_e.g._, buttons or links that do not work).
  - [ ] It must not be dependent upon or cause the page to refresh (it must be a SPA).
  - [ ] It must include at least two interactive features (_e.g._, the user can switch views to see more detail).
  - [ ] It must not contain any JavaScript alerts.
  - [ ] It must be properly indented and written with semantic, camelCase JavaScript and JSX.
  - [ ] It must be free from extraneous `create-react-app` files or code.  Specifically, you must remove the preloaded logo.svg and unused App.css style declarations.
- [ ] **Include data from a third-party API.**
  - [ ] It must contain at least one request to an API
  - [ ] You must use an environment variable to store any API keys if keys are required to make requests to the API you choose.  (We will review this process with you.)
  - [ ] Your API requests **must be made over https**.  Not all APIs support https (most do). Make sure that the API you use has a url that begins with **`https://` not `http://`**.
  - [ ] Each request must handle errors by displaying a message to the user and must not log the error to the console.
  - [ ] The data returned from the API must be used in the application.
- [ ] **Use React Router.**
    - [ ] It must use React Router for navigation.
    - [ ] It must not depend soley on the browser's navigation buttons.
- [ ] **Have at least 4 separate components.**
  - [ ] It must use stateless and stateful components appropriately.
  - [ ]  It may use class-based components or hooks for stateful components.
- [ ] **Be deployed to the Web.**
  - [ ] It must be accessible as an application on the Web (_see_ [Deploying React Apps on Heroku](deployment.md)).
  - [ ] It must separately have a public **GitHub** repository containing your code.
  - [ ] You must not commit your API keys to Github. (_see_ [Storing Your APIs Key](deployment.md))
- [ ] **Use Flexbox or CSS Grid for layouts.**
  - [ ] It must not use floats for layout or depend solely upon positioning elements with fixed or absolute position.
  - [ ] It may incorporate a component library or styling framework.
- [ ] **Be adequately documented on Github.**
  - [ ] Your Github repository must contain a brief description and link to the deployed application in the "website" section at the top of the Code tab.
  - [ ] Your Github repository must contain a README.md file for documentation that is properly formatted using [Github flavored markdown](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).
  - [ ] Your Github repository  README.md must include the following sections:
    - [ ] **Description:** Describe at a high level what your project is and the motivation for the project (_i.e._, what problem(s) your projects solves) and includes a **screenshot** of the application in the browser.
    - [ ] **Technologies Used:** A list of the languages, libraries and frameworks used in your application.
    - [ ] **Getting Started/Installation Instructions:** This would likely describe how to use the application and the steps to fork, clone and run the application.
    - [ ] **Contribution Guidelines:** This section should offer guidance on where and how users can contribute to your code, identify bugs, and propose improvements.
- [ ] **Use git for version control.**
  - [ ] Your project must contain frequent, cohesive commits dating back to the **first day** of the project week.

> ### :triangular_flag_on_post: IMPORTANT:
> To be clear,  **your app should be built in your own Github repository**. That means that you must create a new repo on your Github account. DO NOT build your app in this repository.

## Pre-Project Deliverable (Required)

You must make a proposal and submit it to your squad leader by Friday at noon.  Your squad leader will review and approve your proposal or meet with you to refine the scope.  Your proposal **must** include:

- A **description of the project** you'll be building with the objective described in non-technical language.
- Hand-drawn or digitally created **wireframes** outlining the key views within your app.
- A collection of **user stories representing project MVP**.  You may include additional information about post-MVP plans for your application.
- A link to the **API** you plan to use and an **example of the data response** you will use.
- A **visual of your component hierarchy**. Think of the the critical states of your project and identify the data that each component will need. Optionally, indicate which components need state and which components will recieve props.
- If you plan on incorporating a component library, include a link in your proposal.

> ### :triangular_flag_on_post: IMPORTANT:
> **YOU ARE REQUIRED TO SHOW THAT YOU CAN RECEIVE THE DATA NEEDED TO SUPPORT YOUR PROPOSAL**. Try out your API in the browser or using [Postman](https://www.getpostman.com/) before you get too emotionally invested in your idea to make sure the API works the way you think it does.

Use the **[Project Worksheet](/project-worksheet.md)** in this repository to prepare your proposal.  For additional guidance in completing the worksheet, refer to the [Project Proposal Example](project-proposal-example.md).

## APIs

Below are some collections of APIs you may consider.  None of these is a comprehensive list of all APIs that are available.  Also bear in mind that some APIs on these lists may no longer be available and others **may not be suitable** for this project because they are only available via http.

While you must incorporate data from an API, you are **not required** to use any of the listed APIs.  They are provided solely as examples.

- [Public APIs | toddmotto](https://github.com/toddmotto/public-apis)
- [Public APIs | abhishekbanthia](https://github.com/abhishekbanthia/Public-APIs)
- [Public APIs | n0shake](https://github.com/n0shake/Public-APIs)
- [Public APIs | public-apis](https://github.com/public-apis/public-apis)

## Getting Unstuck

- If you don’t know a good way, try a bad way. Don't hesitate to write messy code to solve short-term problems &mdash; ***refactor later***.
- **Read the docs**. Documentation often includes tutorials or code snippets that can help you get started, and learning to read documentation is crucial to your success as a developer.
- Try explaining your problem to your [**rubber duck**](https://rubberduckdebugging.com/).  There's a lot of psychology behind talking out a problem to find a solution.  In rubber duck debugging, the idea is that when you have to explain your code your are forced to examine your code with a different part of your brain.
- Give yourself a time limit.  Generally speaking, if you haven't found a solution on your own within an hour or two, it's time to ask for help.
- Take a break.  Sometimes the best thing you can do is walk away from the computer.  Get yourself a coffee, take the dog for a walk, anything that will give you time to reset for 10 minutes.  Then when you return to the problem, reread any code or pseudocode you've already written.

### Asking For Help

#### Instructor Support

The purpose of this project is for you to show us and future employers what you're capable of, so we want as much of the project to be your own, independent work as possible. Therefore, each student will be given 5 (five) tokens to ask for help. Each token will give you 20 minutes of one-on-one consultation time with your Squad Lead. Tokens are redeemable during regular class time or as determined by your Squad Lead. Tokens cannot be transferred between students - there is no black market for tokens.

An instructor will be assigned to each team and will check in with your team briefly every morning (whether via Slack or on Zoom). The purpose of these check-ins is NOT to discuss technical questions, but to answer questions about workflow and get a status checkin.

#### Github Issues

We strongly encourage you to file a Github issue prior to asking the instructors
for help directly. This will not only make you a better developer but a better
learner. Visit
[this readme](https://git.generalassemb.ly/DC-WDI/Administrative/blob/master/asking-for-help.md)
for more details on asking for help.

**You should use this time to ask for constructive feedback, so come with
questions prepared and specific things you'd like advice on.**

## Approach

#### 1. Plan
Spend a dedicated block of time to planning with ***wireframes*** and ***user stories*** so that your project time remains focused on producing the things that are necessary to satisfy the project requirements, and so you avoid [scope creep](https://en.wikipedia.org/wiki/Scope_creep).  Write out your [user stories](https://www.mountaingoatsoftware.com/agile/user-stories), keeping in mind that this is not a todo list but rather what specific users will want or need to do with your app. Next, critically review and pare them back to the absolute minimum necessary to satisfy the project requirements, always focusing on [Minimum Viable Product](https://www.youtube.com/watch?v=1FoCbbbcYT8).

#### 2. Follow the Thinking in React model

Once you have a solid plan for your features, follow the [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) model beginning by deconstructing your wireframes into components.

#### 3. Pseudocode

Write pseudocode before you write actual code. Think through the logic step by step, breaking down the big problem into smaller, easier to solve ones.

#### 4. Review and Pivot

Review your progress daily.  Make sure to take time at the end of each day to review your progress against the list of requirements.  This will help you to better manage your time throughout the project week.


## Tips

- **Commit early, commit often.**  Don't be afraid to break something because you can always go back in time to a previous version.
- **Focus on code not design.**  You must satisfy all of the project requirements.  There are no exceptions made for really good looking projects that don't work or fulfill the project requirements.  You will have plenty of time to enhance and style your project at the conclusion of the program.
- **Don't over extend yourself.**  You have grand ideas and we want you to push yourself, but one very important skill as a developer is to never take on more work than you can complete in the allotted time. You will not get credit for great ideas.  Execution and fulfillment of the project requirements is what you will be measured on both here and in your future professional lives.

## A Note on Plagiarism

Take a moment to re-familiarize yourself with the [plagiarism policy](https://git.generalassemb.ly/seir-1118/Administrative/blob/master/plagiarism.md), specifically on using work you find online and on work you do with other students.

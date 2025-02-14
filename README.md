# Dungeon-Delver

This repository stores the website created for a Bath University Software Processes and Modelling Module, crafted to teach students how to work in groups working on a software project. The website is incomplete and not working in areas but valuable lessons were learnt for all involved.

## Technologies Used
- Development: Next.js (React, Javascript, HTML, CSS)
- Testing: Playwright
- Database: Prisma

## Running the Website
First, run the development server:

```
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Getting Help

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

The idea is that Next.js configures both the front end and the back end of the website - without much use of alternative frameworks.

## Using Git

To clone the repository, use the command
``` 
git clone https://github.com/hd2802/Dungeon-Delver
```

To start writing code, create a branch

``` 
git checkout -b <branch-name>
```

Branch names can be anything but include your initials (so we know who authors what change) and some information about what the branch contains.

Try to keep each branch or commit confined to one domain. For example, if you need to edit both the frontend and backend, be sure to do this on different branches and different commits. 

Then, write some code!

When you are done and want to push it, run the following command

```
git add .
```

This stages all your changes for a commit - i.e. it means that all of the files that you have changed on your machine will be changed on the git repository. 

Commit the changes using the following command:

```
git commit -m "<commit-message>"
```
Commit messages need to start capitalised and describe the changes briefly, in the present tense. 

For example, suppose that I made a commit that changes this file, the commit message would be `Changes README.md` or something along those lines.

```
git push
```

Navigate to the repository and create a merge request.

Our repository is private so we cannot protect the main branch but please do not merge the branch straight away, even if Git approves it. 

For greater code quality we need to make sure that people approve the merge request and that it fulfills the requirement or task as needed.

Once your merge request has been approved by the rest of the team, your code has been integrated into the website! Well done! 

## Testing

The testing environment that we are choosing to use is Playwright. This allows for greater testing of web-specific applications.

To run tests:
```
npx playwright test
```

To view the report for the tests:
```
npx playwright show-report
```

To run the tests with a UI:
```
npx playwright test --ui
```

For information on writing tests and further information about playwright, see [Playwright website](https://playwright.dev/) 

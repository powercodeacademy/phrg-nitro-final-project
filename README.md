# Final Power Code Academy Project

Congrats! You made it! This is the Final Project in the Power Code Academy Bootcamp!

## Nitro

Instead of being a standalone codebase, this project will be constructed directly in Nitro. It is organized into 4 tiers. Completing `Tier 1` is the minimum requirement for moving on, but you should try to complete as many tiers as you can. Be sure to only work on one tier at a time. For example, do not start something in `Tier 3` if you have not yet completed `Tier 2`.

The core focus of this project is to exercise your ability to write React and use GraphQL, following defined conventions found in `nitro-web`. Use other files for examples and embrace Nitro's internal tools and libraries.

## Ask a lot of questions

For the most part, Nitro uses the newest tools, libraries, and technologies out there. However, the application started in 2009. So it also contains a lot of valuable, profitable, substandard, old code. Why "fix" something if it isn't broken? Changing code simply to use a newer system is risky. There has to be a clear reason to take that risk. If there is not a good reason, older code should not be changed.

There may be 3 different ways to accomplish a goal in Nitro. To decipher which coding approach may be the best to mimic, you have to ask. Lean on you instructor, TAs, and your team when the best way to make an addition is not clear.

One such example is functional components versus class components in React. Both exist in Nitro, but functional components are now the better and official way to write React (in both Nitro and React communities).

## General Requirements

As mentioned, your final project will not be a standalone codebase. Instead, it will be a Pull Request (PR) opened up against the `nitro-web` repository. Your PR should follow all best PR conventions:

### Github Pull Request Requirements

- Accurate PR title
- Correct team label as well as correct use of WIP label (xavier, WIP)
- Detailed PR summary that includes:
1. Complete sentences and paragraphs explaining your additions
1. Screenshots of all your additions

Each tier of the project has different demands. However, there are some universal requirements that apply throughout all tiers (and all development work you do in Nitro).

### Requirements for all tiers

- All React code must strictly adhere to ESLint conventions
- All Ruby code must strictly adhere to Rubocop linting conventions
- All of you code must not break any automated tests (`rspec` and `mocha`)
- Commits should be small and logical changesets. Read [this article](https://chris.beams.io/posts/git-commit/) about best practices with commits and apply its [seven rules](https://chris.beams.io/posts/git-commit/#seven-rules) to all of your Nitro commits.
- There must be a commit level divisions between each tier

## Tier Requirements

### Tier 1 (React & GraphQL)

- Create a new index OR show view in React
- View must use at least 3 Playbook kits
- View must load its initial content via a GraphQL query

### Tier 2 (React)

- Create a second view that displays a "new" form using [react-hook-form](https://react-hook-form.com/)
- View must use at least 3 Playbook kits
- Form must present an existing Nitro resource with a selectable relationship to another object. The form must have 5 inputs at minimum. Check off your Nitro resource with an instructor before starting this tier.

### Tier 3 (Ruby & GraphQL & React)

- Write the BE GraphQL Query logic needed to retrieve your Nitro resource
- Rework the form into an "edit" that first loads the resource via GraphQL

### Tier 4 (Ruby & GraphQL & React)

- Write the backend GraphQL Query logic needed to update (mutate) your Nitro resource
- Rework React form to successfully submit and update
- Add appropriate backend tests for your GraphQL additions
- Add appropriate frontend tests for your React additions

## Setup

Before you start, you must first identify what GraphQL Query / Nitro resource you will use for `Tier 1`. Coordinate with the instructor for your designated query from the list of available options.

Once you have your designated query, get Nitro up and running locally. Navigate to `http://localhost:3000/dev_docs/pca_final_projects`. This page renders a React component that you will replace with your project. It can be found in the `dev_docs` component in `nitro-web`.

Note you will have to get the project app set up by adding it to webpacker. In `app/javascript/packs/dev_docs.js` after line 7, add `PcaProjectApp: hot(module)(PcaProjectApp)`, and make sure to include `PcaProjectApp` in the list of imports on line 3. 


## Project Code Reviews

Instead of a one hour pairing session, you will have an interactive code review session with a PCA Evaluator. After your session is complete, you are tasked with completing all the requested changes offered by your code reviewer. This project is complete once you have acquired a green code approval from your reviewer.

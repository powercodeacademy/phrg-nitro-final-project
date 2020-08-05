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
- Correct team label as well as correct use of WIP label
- Detailed PR summary that includes:
1. Detailed complete sentences and paragraphs explaining your additions
1. Multiple screenshots of your additions (displaying all different states of use)

Each tier of the project has different demands. However, there are some universal requirements that apply throughout all tiers (and all developmetn work you do ever do in Nitro).

### Requirements for all tiers

- All React code must strictly adhere to ESLint and Flow Nitro JS conventions
- All Ruby code must strictly adhere to Rubocop linting conventions
- All of you code must not break any automated tests (`rspec` and `mocha`)
- There must be a commit level division between each tier
- Commits should be small and logical changesets. Read [this article](https://chris.beams.io/posts/git-commit/) about best practices with commits and apply its seven rules to all of your Nitro commits.

## Tier Requirements

So what is the project actually going to be about? Check out the Tier technical requirements below.

### Tier 1 (React & GraphQL)

- Create a new index or show view in React of a Nitro resource
- The new view must use at least 3 Playbook kits
- The new view must load its initial content via a GraphQL query (choosen from list provided by instructor)

### Tier 2 (React)

- Create a second view that displays a "new" form using Formik
- This view must use at least 3 Playbook kits
- The form should present an existing Nitro resource with a selectable relationship to another object. The form must have 5 inputs at minimum. Check off your Nitro resource with your instructor before proceeding.

### Tier 3 (Ruby & GraphQL & React)

- Write the backend GraphQL Query logic needed to retrieve (query) your Nitro resource
- Rework the form into an "edit" that first loads the resource via GraphQL

### Tier 4 (Ruby & GraphQL & React)

- Write the backend GraphQL Query logic needed to update (mutate) your Nitro resource
- Rework the form to successfully submit and update
- Add appropriate backend tests for your GraphQL additions
- Add appropriate frontend tests for your React additions

## Setup

TODO: Choosing query from instructor list. Instructions on where in `nitro-web` to add functionality.

## Project Code Reviews

Instead of a one hour pairing session, you will have an interactive code review session with a PCA Evaluator. After your session is complete, you are tasked with completing all the suggested upgrades by your code reviewer. This project is only complete once you have acquired a green code approval from your reviewer.

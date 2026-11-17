# Welcome to the Integrating With HubSpot I: Foundations Practicum

This repository is for the Integrating With HubSpot I: Foundations course. This practicum is one of two requirements for receiving your Integrating With HubSpot I: Foundations certification. You must also take the exam and receive a passing grade (at least 75%).

To read the full directions, please go to the [practicum instructions](https://app.hubspot.com/academy/l/tracks/1092124/1093824/5493?language=en).

**Put your HubSpot developer test account custom objects URL link here:** https://app.hubspot.com/contacts/52323809/objects/2-73082104/views/all/list

## About this app
A small Express + Axios + Pug app for a **Pets** custom object (properties: `name`, `species`, `age`).

- `GET /` lists the Pets records in a table.
- `GET /update-cobj` shows a form to create a new Pet.
- `POST /update-cobj` creates the Pet in HubSpot and redirects to the homepage.

The schema used to create the object is in `schema/pets.json`.

### Running locally
1. `npm install`
2. Copy `.env.example` to `.env` and set `PRIVATE_APP_ACCESS` (private app token with `crm.objects.custom.read`, `crm.objects.custom.write` and `crm.schemas.custom.read`) and `CUSTOM_OBJECT_TYPE`.
3. `node index.js` and open http://localhost:3000

___
## Tips:
- Commit to your repository often. Even if you make small tweaks to your code, it’s best to be committing to your repository frequently.
- The subject of the custom object is up to you. Feel free to get creative!
- Please create a test account and include your private app access token in your repo.
- Ensure you re-merge any working branches into the main branch.
- DO NOT ADD YOUR PRIVATE APP TOKEN TO YOUR REPOSITORY. 

## Pre-requisites:
- Using [Node](https://nodejs.org/en/download) and node packages
- Using [Express](https://expressjs.com/en/starter/installing.html)
- Using [Axios](https://axios-http.com/docs/intro)
- Using [Pug templating system](https://pugjs.org/api/getting-started.html)
- Using the command line
- Using [Git and GitHub](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

## Requirements
- All work must be your own. During the grading process we will check the revision history. Submissions that do not meet this requirement will not be considered.
- You must have at least two new routes in your index.js file and one new pug template for the homepage.
- You must create a developer test account and link to it in your README.md file. Submissions that do not meet this requirement will not be considered.

# Austin Soccer Votes
The AustinSoccerVotes.org website is a collaborative effort between [Austin Anthem](https://austinanthem.org) and [Los Verdes](https://losverdesatx.org) encouraging all Austin soccer supporters to vote for two very important propositions in the 2020 election. Fulfilling our commitment to our city council members to stay involved in local matters for the better.

# Technical Details
This site is powered by [Vue](https://vuejs.org/) and hosted on Microsoft Azure's Static Web Apps (Beta). Though it's mostly tables and basic HTML due to the timeline of the project.

## Quickstart
No fancy modifications here. Make sure you have [npm](https://www.npmjs.com/) installed, then, from the root directory of the project:
`npm install` installs all the node dependencies
`npm run serve` starts a development server and tells you where to hit it locally for development.

If you want a production build for some reason, then `npm run-script build` has you covered. In this case, GitHub Actions do all the magic to push it into Azure with literally no effort.
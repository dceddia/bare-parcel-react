## A Barebones React + Parcel Project

Create React App is awesome, but if you want to spin up a bunch of separate React apps locally, it can get pretty bloated when each project has its own installation of everything.

This project is a barebones React starter that expects you to have the `parcel` bundler installed globally.

It only includes `react` and `react-dom`.

This is a tradeoff: you'll save some space at the expense of losing the niceities that Create React App provides, like a good default linter config and friendly error reporting.

I wouldn't recommend using this for projects that will be long-lived, or deployed to production. But it's great for spinning up local projects.

## To Use This Project

1. Install Parcel globally, once. `npm install -g parcel`
2. Clone this repo
3. Run `npm install` (check out `node_modules`! It's only 3.6mb!)
4. Run `npm start`


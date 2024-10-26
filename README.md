## Job Listing Sample Web App

A sample job listing board with some simple functionality [Schooner Strategies](https://schoonerstrategies.com).

## Getting Started

- Project uses [Roots Bedrock](https://roots.io/bedrock/) see documentation

- Clone the repo
- Create a database and use .env.example to make a .env file
- Run `composer update` to install wp, the theme, and the plugins. /web will be your root folder.
- Run `wp theme activate joblisting` to activate the theme and `wp plugin activate --all` to activate both plugins
- Generate some jobs with `wp generate_job_posts --count=150`

## Objectives

- update the vue components in index.php to include the functionality included in the UI
- update single.php as appropriate
- add a 'Post Your Job' page with the included page template
# Serverless PHP on Vercel

Based on https://github.com/juicyfx/vercel-php

PHP is a [“community”/unofficial runtime](https://vercel.com/docs/runtimes#advanced-usage/community-runtimes) on Vercel.

## Demo

- https://php-serverless-on-vercel.vercel.app/api
- https://php-serverless-on-vercel.vercel.app/api/route2

## How to use

- Each file is a serverless process
- API files stored in the `/api` folder
- Routing maps to file names, e.g. `/api/route2.php` will map to the route `/api/route2`
  - You can override routing in `vercel.json` (this is now a [legacy prop](https://vercel.com/docs/cli#project-configuration/routes))
- Run `vercel` on command-line to push your project up on a preview URL. You can also connect Vercel to a GitHub repository and have it auto-deploy on code commits.

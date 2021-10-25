# Serverless PHP on Vercel

Based on https://github.com/juicyfx/vercel-php

PHP is a [“community runtime”](https://vercel.com/docs/runtimes#advanced-usage/community-runtimes) on Vercel.

## Example

https://php-serverless-on-vercel.vercel.app/api

## How to use

- API files stored in the `/api` folder
- Each file is a serverless process
- Needed? Routing set up in `vercel.json` (this is now a [legacy prop](https://vercel.com/docs/cli#project-configuration/routes))

** localtunnel for sharing project on cloud

npm install localtunnel -g

start the server

  - lt --port 3000
  - share the link

share with subdomain

  - lt --port 3000 --subdomain cloudtest

** npm-run-all for running tasks concurrently

with npm scripts, anything that starts with `pre` runs first, anything with `post` runs after

eslint-watch package add file watching functionality for lint file

  - "lint:watch": "npm run lint -- --watch"
  - '--' means pass the following as arguments

** decisions to make while setting up a testing framework

  - framework: mocha
  - assertion library: chai
  - where to run tests: node
  - where to place tests: alongside original
  - when to run tests: upon save

** push to github

  - `git add .`
  - `git commit -m "message"`
  - `git push `


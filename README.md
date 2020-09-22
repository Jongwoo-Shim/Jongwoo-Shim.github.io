
# Personal Website 
Based off of the al-folio template : https://github.com/alshedivat/al-folio

## Run Locally
1. Have Ruby installed on your system, and verify that it works.
2. Install bundler and jekyll : https://www.taniarascia.com/make-a-static-website-with-jekyll/
3. Run `bundle install` to fetch dependencies.
5. Run `bundle exec jekyll serve` to launch local server.
6. On your browser goto `http://127.0.0.1:4000/`.

## Deploy to Github Page
The deploy script will manage the deployment of the code in `master`.
```bash
$ ./bin/deploy [--user]
```
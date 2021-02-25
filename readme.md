This is the new ChairBot UI. Right now it's intert HTML/CSS and will need to be integrated into the primary project

## TODO
When you finish a task, put your initials and the date

- [X] Write TODO list (BSS 12/13)
- [X] Write responsive layout code (BSS 12/11)
- [ ] (optional) Test running with a Python Flask server (Breanne)
- [ ] Integrate into the main server: [github repo of server, clean branch](https://github.com/stoddabr/chairbot_server/tree/winter_cleaning) (Breanne)
- [ ] Sync old Javascript function calls to new UI (Breanne)
- [ ] Implement tap-goal (Avi)

## How to run
Opening up the index.html file directly in a browser will cause an error (CORS prevents some imports from happening)

To run the website properly, it needs to be served from a server. These steps will go through installing one type of server http-server by NodeJS
- Download nodeJS. This is a runtime environment for javascript that will enable you to run code such as a server https://nodejs.org/en/
- Now use node to install http-server . If node was properly added to your OS path then this should be as simple as running `npm i http-server` from a command line
Now the server should be installed on your computer. To run it, navigate to the directory with the index.html file you want to view and run `http-server` from your command line
If things work correctly, running `http-server` should trigger stdout that includes a local website link (something like http://localhost:8080). Opening that up in a browser should show make the website render properly

## Useful links
* How to import files https://stackoverflow.com/questions/8988855/include-another-html-file-in-a-html-file?page=1&tab=votes#tab-top
* Run with `http-server` (it's extremely simple once setup but requires [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)) https://www.npmjs.com/package/http-server 
* How to contribute to open-source projects (including this one) https://opensource.com/article/19/7/create-pull-request-github 
* Bootstrap CSS documentation https://getbootstrap.com/docs/5.0/getting-started/introduction/


# Visual-Regression
This is a demo of visual regression using phantom css.

## Steps

1. Create an index.html.
2. npm init
3. npm install http-server --save-dev
4. To run the server, let’s define a simple npm script. Just add the following scripts section to package.json Add "scripts": {
  "start": "http-server"
},
5. npm start
6. The index page will be accessible on the default address http://127.0.0.1:8080.
7. Run following on terminal : npm install phantomcss casperjs phantomjs-prebuilt --save-dev
8. Create a Test.js file add code to it.
9. Add the following script to package.json next to start: "test": "casperjs test test.js".
10. Run npm test




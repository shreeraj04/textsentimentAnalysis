# textsentimentAnalysis
Getting the sentiment of the entered text using the NLP node js library. For this we are using NodeJS Express

Steps:(which might be different from how you create)
1 npm i -g express-generator

2 express nlp -v hbs

3 cd nlp

4 npm i

5 npm start

6 code routes

Hurray! Express is now on..

Now install the nlp via->  npm install node-nlp

Once installation is done, check the index.hbs file which has a textarea to enter the text and click on analyze button. This will request server via api to analyse the sentiment of the entered text and responds with the json data as shown below:

comparative: 0 language: "en" numHits: 0 numWords: 1 score: 0 type: "senticon"__proto__: Object

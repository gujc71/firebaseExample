## simple board(CRUD) examples for firebase and Node.js(express) ##

This example is web boards focusing on data input / output for easy understanding of firebase (database).

Although the documentation provided with Firebase is well documented, it is difficult to understand how to use it because it is described as a function-oriented one.

So, this example is designed to make it easy to learn how to use Firebase through three simple web board codes (node.js + express):

1. board based on Realtime Database
2. board based on Cloud Firestore (beta)
3. authentication

### Install & Run ###
- source down from github
- npm install
- Edit app.js: Since the three examples do not run at the same time, you should modify the following code in app.js.
    
    app.use('/board1', require('./routes/board1'));
    
    //app.use('/board2', require('./routes/board2'));
    
    //app.use('/board3', require('./routes/board3'));

- Edit board1.js, board2.js and board3.js: set config for [firebase](https://firebase.google.com/docs/web/setup?authuser=0)
    
- npm start    
- http://localhost:3000/board1/boardList

    (http://localhost:3000/board2/boardList, http://localhost:3000/board3/boardList)




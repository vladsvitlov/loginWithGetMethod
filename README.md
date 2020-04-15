# loginWithGetMethod
Login application that is using doGet method to see the difference between doGet and doPost

when the client submits username and password, this information is requested by the LoginServlet via doGet method. This information is displayed on the screen and the webserver logs. For passing username and password, its better to use doPost method. Also, in doGet method the data is appended to the url which has 240 bytes limit, the data passed through doPost method has no limits.

# Node.js Rest APIs with Express & MySQL example


## Project setup
Please create database "testdb" in mysql and run following script
    ```
    CREATE TABLE `tutorials` (
    `id` int NOT NULL AUTO_INCREMENT,
    `title` varchar(255) NOT NULL,
    `description` varchar(255) DEFAULT NULL,
    `published` tinyint(1) DEFAULT '0',
    PRIMARY KEY (`id`)
    )

    ```


Please go to Directory  node-express-server

    ```
    npm install
    ```

    ### Run
    ```
    node server.js
    ```

Please go to Directory  react-client
    ```
    npm install
    ```

    ### Run
    ```
    npm start
    ```
Browse localhost and try adding, deleting or updating Tutorials data 
# Simple Restful API (ExpressJS, Sequelize, Mysql) with Different Callback Handling

This is example of Restful API's implementation using expressJs with Sequelize ORM and Mysql Database using different callback handling

## Setup and Installation

### Install Express Generator

```bash
npm install -g express-generator
```

### Initalize Sequelize ORM

``` bash
sequelize init
sequelize model:create --name Todo --attributes title:string,description:string
sequelize db:migrate
```

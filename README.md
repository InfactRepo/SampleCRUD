# SampleCRUD

Technologies : 
    Angular ,
    NodeJS , 
    ExpressJS framework , 
    MS SQL,
    JWT

## Development server
Use folowing commands to run Dev Env,

Run `npm install` 

Run `ng build` 

Run `node server.js`

Please change Data ase config information, before run those commands. 

## Seting up the DataBase,
    server: 'localhost', 
    database: 'sample_crud'.

    Tables 
        - user_login - 
        (id_user_login:INT-Primary Key,Auto Increment),
        (name:varchar),
        (email:varchar),
        (uname:varchar),
        (password:varchar)

        - product -
        (id_product:INT-Primary Key,Auto Increment),
        (name:varchar),
        (qty:INT),
        (price:FLOAT)


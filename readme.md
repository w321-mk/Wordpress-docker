# Local Wordpress Server

## Instructions
1. Create two folders (**wordpress** and '**mysql**') in the root directory as follows
```
    + wordpress
    + mysql
    + nginx
    |- default.conf
    ...
```
2. extract the wordpress installation files into the wordpress folder
3. start wordpress installation and setup with 
    ```
    docker compose up -d
    ```

4. whenever changes are made to the [docker-compose.yml](./docker-compose.yml) use 
    ```
    docker compose up -d --build
    ``` 


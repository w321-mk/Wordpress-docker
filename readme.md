# Local Wordpress Server

## Instructions
1. Create two folders (**wordpress** and '**mysql**') in the root directory. The [root](.) directory should be as follows
    ```
        + wordpress
        + mysql
        + nginx
        |- default.conf
        -.gitignore
        -docker-compose.yml
        -nginx.dockerfile
        -php.dockerfile
        -readme.md
    ```
2. extract the wordpress installation files into the [wordpress](./wordpress) folder
3. start wordpress installation and setup with 
    ```
    docker compose up -d
    ```

5. Go to [localhost](http://localhost:80) to begin setting up wordpress

### **NOTE**
whenever changes are made to the [docker-compose.yml](./docker-compose.yml) use 

    docker compose up -d --build

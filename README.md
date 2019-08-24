### Qiuck start
  
1. **Build image**
    ```sh
    docker build -t buisiness-server .
    ```
2. **Run container**
    ```sh
    docker run --rm -it -d -p 9999:9999 -v $(pwd):/app buisiness-server
     ```

3. **Create client folder**
    ```sh
    mkdir src/client && mkdir src/client/build
     ```

Additional commands
Features:
  * docker ps                  -- working container list
  * docker logs <container-id> -- read server logs
  * docker stop <container-id> -- stop detached container
  * docker exec -it <container-id> /bin/bash -- connect to container TTY
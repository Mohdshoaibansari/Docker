 Usage:
 
 1. Create Docker image with below command: 
 docker build -t first-lab .

2. Run the docker on detached mode and open container port 3000 and map it to 3000 port of host: 
 docker run -dp 3000:3000

3. Create Volume: docker volume create todo-db

4. Create docker container with persistent volume: docker run -dp 3000:3000 -v todo-db:/etc/todos

# DevOps Lab 2023-27

## Assignment TW1.4 – Container Management & Networking

### Student Details

**Name:** Aryan Bhandage  
**PRN:** 24070122501  
**Course:** DevOps Lab

---

## Objective

To understand Docker container management and networking by running, inspecting, stopping, and removing containers.

---

## Tasks Performed

- Ran a Docker container with port mapping (`8080:5000`)
- Accessed the Flask application using `http://localhost:8080`
- Listed running containers
- Stopped the running container
- Listed all containers
- Inspected container network settings
- Removed the container

---

## Commands Used

```bash
docker images
docker run -d -p 8080:5000 --name flask-network my-flask-app
docker ps
docker stop flask-network
docker ps -a
docker inspect flask-network
docker rm flask-network
```

---

## Files Included

- app.py
- Dockerfile
- requirements.txt

---

## Screenshots

All execution screenshots are available in the `screenshots` folder.

---

## Learning Outcomes

- Learned Docker container lifecycle
- Understood port mapping
- Managed running and stopped containers
- Inspected container network settings
- Removed Docker containers

---

## Conclusion

Successfully performed Docker container management and networking operations using a containerized Flask application.\

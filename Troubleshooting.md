# 🛠️ Task 5: Troubleshooting Scenario

## 🔹 Scenario 1: Docker container exits immediately after startup

### 1. Possible Reasons:
- Application crashes due to errors in code  
- Incorrect CMD or ENTRYPOINT in Dockerfile  
- Missing dependencies  
- Port or configuration issue  
- Environment variables not set  

### 2. How will you debug?
- docker logs <container_id>  
- docker run -it o2h-app /bin/bash  
- Check Dockerfile  
- Run app locally  
- Rebuild image  

---

## 🔹 Scenario 2: Application works locally but not on server

### 1. What will you check?
- Server configuration  
- Port and firewall  
- Environment variables  
- Network issues  
- Docker status  

### 2. How will you identify the issue?
- Check logs  
- ps -ef | grep node  
- netstat -tuln  
- curl http://localhost:3000  
- Compare local vs server  

---

## ✅ Conclusion
Troubleshooting means checking logs, configs, and fixing step by step.
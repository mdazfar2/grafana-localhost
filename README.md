# Grafana Setup 

## Firstly check if Your kubernetes cluster is running or not
![image](https://github.com/mdazfar2/grafana-localhost/assets/100375390/e0b1b4cc-cb0f-41f5-9700-c159da8edaba)

### Then install the helm chart by this command

```bash
helm install azfar .\grafana\
```

### Now check whether the chart of that name appears in the helm list or not
```bash
helm ls
```

### Check pods of your kubernetes is ready or not
```bash
kubectl get pods
```
### now get your pods of your if
```bash
kubectl get svc
```
### and the final is get your ip
```bash
minikube ip
```
**attach the port with your ip and run in your localhost browser**

## Let's Connect
Have questions, ideas, or just want to chat? Join the conversation on [Discord](https://discordapp.com/users/877531143610708028) or [Linkedin](https://linkedin.com/in/md-azfar-alam/) and also [Instagram](https://instagram.com/azfarxx_/)

Keep Learning! 🐍✨
Keep Sharing! 🐍✨.

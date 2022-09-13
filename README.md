# Bodhi Infra for Production
Copilot infrastructure for bodhd mandala.

## Deploy
init and deploy app + env
```
cop app init
cop env init
cop env deploy
```

init and deploy subql
```
cop svc init -n subql-node-karura -t "Backend Service"
cop svc init -n subql-node-acala -t "Backend Service"

cop svc deploy -n subql-node-karura
cop svc deploy -n subql-node-acala
```

init and deploy the pipeline
```
cop pipeline init
cop pipeline deploy
```
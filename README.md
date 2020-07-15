# sms_modem
[Enclude CRM Artefact]

### Pre-requisites
  - [Docker]
  - [Docker Compose]

### ./.env.prod
Create a file for the environment variables in the root directory called ".env.prod" with the following variables
```
WEBSOCKET_URI=wss://{web-service-ws-endpoint} # currently "wss://sms.enclude.ie"
WS_KEY={websocket-secret} #Must match WS_KEY in sms_webservice
```

### Docker Run Script
From root directory
```
docker-compose up --build -d
```
[Enclude CRM Artefact]: <https://enclude.lightning.force.com/lightning/r/CRM_Artefacts__c/a1c3X000004hElfQAE/view>
[Docker]: <https://docs.docker.com/get-docker/>
[Docker Compose]: <https://docs.docker.com/compose/install/>
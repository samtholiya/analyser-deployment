# analyser-deployment

Use the yaml file to deploy analyser web application to kubernetes
```
kubectl apply -f .\analyser-deployment.yaml
```
This deployment is for project analyser web application

Backend Code: [analyse-service](https://www.github.com/samtholiya/analyserService) [![Build Status](https://travis-ci.com/samtholiya/analyserService.svg?branch=main)](https://travis-ci.com/samtholiya/analyserService)

Frontend Code: [analyse-ui-service](https://www.github.com/samtholiya/analyser-ui) [![Build Status](https://travis-ci.com/samtholiya/analyser-ui.svg?branch=master)](https://travis-ci.com/samtholiya/analyser-ui)

Access UI at 30080 port

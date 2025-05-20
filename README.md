# education-service

```
git checkout -b education-service
helm create education-service
helm package  .\education-service\
touch index.yaml
helm repo index .
```

Добавление и установка хелма
```
helm repo add education-service-app https://netrogajsvetchu.github.io/education-service-app/
helm repo list
helm install education-test education-service-app/education-service
```
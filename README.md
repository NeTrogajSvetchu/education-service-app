# education-service
git checkout -b education-service
helm package  .\education-service\
touch index.yaml
helm repo index .

Добавление и установка хелма
helm repo add education-service-app https://
helm repo list
helm install education-test educ-test/education-service
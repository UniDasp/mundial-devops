# Mundial CI/CD Demo

Proyecto educativo para practicar:

GitHub -> GitHub Actions -> Amazon ECR -> Amazon EKS

## Ejecutar local

pip install -r requirements.txt
python app.py

## Docker

docker build -t mundial-app .
docker run -p 5000:5000 mundial-app

## Kubernetes

kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml

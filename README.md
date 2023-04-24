# HAT-manifest
HAT k8s manifest

# 파일 실행 순서

## backend service & deployment 생성

kubectl apply -f HAT-deployment.yaml

kubectl apply -f HAT-service.yaml

kubectl apply -f HAT-ingress.yaml

# KuberLesson2

Запустить комманду:
helm repo add mysql-repo https://charts.bitnami.com/bitnami && \
helm install mysql-test mysql-repo/mysql -f values.yaml && \
kubectl apply -f ingress-helm.yaml && \
kubectl apply -f lesson2-config.yaml && \
kubectl apply -f service.yaml && \
kubectl apply -f deployment.yaml

После импортировать Postam коллекцию Service Api Test.postman_collection.json и запустить.

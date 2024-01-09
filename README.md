# otus-hw10-k8s

Добавить запись в /etc/hosts для: arch.homework

Развернуть сервис в кластере k8s:
$ kubectl apply -f .

Удалить сервис из кластера:
$ kubectl delete -f .

Проверка:
$ curl http://arch.homework/health


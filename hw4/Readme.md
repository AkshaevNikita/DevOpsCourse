- Apply all confiiguration files using: ``kubectl apply -f <conf_file_name>``

- If status of your External_IP is pending, you can try to use ``kubectl expose deployment <deployment_name> --type=LoadBalancer --port=8080``

- Now you can connect to svc

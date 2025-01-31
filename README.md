# Traefik Load Balancer with FrankenPHP

To run all configurations, execute the following commands:
```bash
cd traefik-lb-frankenphp
kubectl apply -k .
```

Update the MariaDB volume to your local directory and the deployment volume to the path of your app website directory. The directory path should be specific, such as `/home/ubuntu/kubernetes/Traefik-lb-frankenphp/xxx`.

- **Adminer**: For managing the MariaDB database.
- **MariaDB**: Contains the database deployment for the app website.
- **Traefik**: Acts as the load balancer for the pods.
- **Ingress**: Balances the load and acts as a proxy.
- **Deployment**: Contains the app website.

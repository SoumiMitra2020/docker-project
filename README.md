# docker-project

To run the docker-compose file, run the following command:

docker-compose up -d

I've created the following containers:

NGINX

prometheus

alertmanager

prom2teams

I've created the containers in such a way that if NGINX is down, one alert will trigger at prometheus. Then the alert will be shown at Alertmanager UI and Prom2Team UI respectively.
Please check the Documentation.docx file for more details.

I've configured some Demo alerts in the alert.yml file to test this prometheus monitoring stack.

# Reference:

I’ve taken reference from the following to implement this project.

https://github.com/ablx/monitoring_stack

https://dev.to/ablx/series/12839

https://docs.docker.com/compose/

https://prometheus.io/docs/alerting/latest/alertmanager/


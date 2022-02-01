# rc_cube_monitoring

Example deployment of a docker-compose stack in [rc_cube UserSpace](https://doc.rc-cube.com/latest/en/userspace.html)
consisting of

* [Prometheus](https://prometheus.io) configured to scrape the rc_cube
  * reachable on port 9090
* [Grafana](https://grafana.com) with an example rc_cube dashboard
  * reachable on port 8080

Grafana is configured with anonymous access for viewing only.
Go to Dashboards -> Browse and open the rc_cube dashboard.

To make changes login to Grafana with user `admin`, password `admin` and set a new password.

In a real production deployment, it is highly advised to setup Grafana to use https!

![dashboard](img/rc_cube_monitoring-dashboard.png)

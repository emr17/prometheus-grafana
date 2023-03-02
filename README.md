Öncelikle conductor da metrikleri aktif edin :https://kandyio.atlassian.net/wiki/spaces/KBS/pages/21212594357/Netflix+Conductor+Metrics

Daha sonra prometheus.yml dosyasında hostu düzenleyin ve docker run -d -p 9090:9090 -v C:/Users/esevmis/Desktop/promet/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus

komutunu prometheus.yml dosyasının konumunu düzenleyerek çalıştırın.

Ardından aşağıdaki linklerden yardım alarak grafana kurulumu yapın ve grafana-prometheus bağlantısını sağlayın (ben grafanayı lokalimde kurdum):

https://medium.com/javarevisited/springboot-app-monitoring-with-grafana-prometheus-7c723f0dec15

https://refactorfirst.com/spring-boot-prometheus-grafana

Grafana nın default user ve passwordu = admin

Daha sonra grafana'da Conductor New DashBoard dosyasını import edin.



# Grafana dashboards

Some custom dashboards created for various purposes. Rather than reinventing the wheel the majority of them are based off ones I found in the Grafana market place with tweaks to make them work with my data.

- **Network Monitoring** (*Influxdb with telegraf plugins*): Monitors HTTP requests, DNS queries and ICMP (RTT, latency, packet loss)
  <img width="960" alt="Image" src="https://github.com/user-attachments/assets/5b9a1dff-30da-4092-8abd-8abcef76dce5" />

- **Server (phone) Monitoring** (*Prometheus with node-exporter*): Monitors OnePlus phone running pmOS, includes battery, CPU, Memory, Disk and networking (based off dashboard 1860)
  <img width="960" alt="Image" src="https://github.com/user-attachments/assets/f4dcabd5-8e98-438d-a7e1-166a23ecbf91" />

- **Prometheus Scraping** (*Prometheus*): Scrape instances and times for troubleshooting prometheus metric collection (based off dashboard 10876)
  <img width="960" alt="Image" src="https://github.com/user-attachments/assets/d068cc8f-4e6e-4af3-9fe7-9715089415b8" />

- **K3s Node and Pod Monitoring** (*Prometheus with node-exporter*): Monitors CPU, load, Memory, disk and networking of K3s nodes and pods as well as the same details and processes for the individual K3s pods and namespaces (based off dashboards 8171 and 19972)
  ![Image](https://github.com/user-attachments/assets/9c3ec749-0b6b-41be-afe3-28bfcfbda0b7)

- **Teltonika Dashboard** (*Prometheus with snmp-exporter*): Monitors CPU, load, signal and traffic on a Teltonika RUT950 4G WiFi router (based off dashboard 20004)
  <img width="960" alt="Image" src="https://github.com/user-attachments/assets/89be4789-8fd0-4826-909b-2c8904c05ea0" />

- **Victron Dashboard** (*Influxdb with telegraf plugins*): Uses Victron Cerbo GX to monitor MPPT solar, Multiplus charger & inverter, DC usage, batteries, fuel & water tanks and Ruuvi temperature sensors (based off dashboard 14400)
  ![Image](https://github.com/user-attachments/assets/2fd5f8a3-0f54-4a71-a14b-0ab890b99ec6)

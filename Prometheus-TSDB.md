# Prometheus TSDB

Slides: https://www.slideshare.net/Docker/how-and-why-prometheus-new-storage-engine-pushes-the-limits-of-time-series-databases

### Notes

  - The talk was about how the new version of Prometheus comes with a new TSDB, created by the team
  - In a few words they build another OpenTSDB on top of HBase
  - This won't make Prometheus Highly Available, we still have to deploy two Prometheus servers for HA

Prometheus Monitoring Setup

Steps:
1. Install Docker
2. Place prometheus.yml and docker-compose.yml in same folder
3. Run: docker-compose up
4. Open browser: http://localhost:9090
5. Check targets and metrics

Backend must expose:
http://localhost:8080/metrics

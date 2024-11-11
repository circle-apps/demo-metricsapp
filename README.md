```
npx ts-node --require ./instrumentation.ts app.ts
docker run -p 4317:4317 -p 4318:4318 --rm -v $(pwd)/collector-config.yaml:/etc/otelcol/config.yaml otel/opentelemetry-collector
curl http://localhost:8080/rolldice?rolls=5
```

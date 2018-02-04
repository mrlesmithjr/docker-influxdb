# docker-influxdb

Spins up a basic [InfluxDB](https://www.influxdata.com/time-series-platform/influxdb/)
container for testing.

# Usage

### Non-Persistent Storage

```bash
docker run -d -p 8086:8086 mrlesmithjr/influxdb
```

### Persistent Storage

```bash
docker run -d -v $PWD/.data:/var/lib/influxdb -p 8086:8086 mrlesmithjr/influxdb
```

## License

MIT

## Author Information

Larry Smith Jr.

-   [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   <mailto:mrlesmithjr@gmail.com>

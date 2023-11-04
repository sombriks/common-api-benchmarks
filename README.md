# [common-api-benchmarks](https://github.com/sombriks/common-api-benchmarks)

Benchmark for backend stack comparison.
Original article: https://www.inovex.de/de/blog/rust-vs-go-vs-c-vs-kotlin/

## Port list

| Service   | Portnumber |
|-----------|------------|
| Rust      | 8010       |
| Go        | 8020       |
| .Net API  | 8030       |
| .Net mAPI | 8040       |
| Ktor      | 8050       |
| Spring    | 8060       |

## Requirements

- docker 20+

## How to run

```bash
docker compose -f docker-compose.yml up -d
```


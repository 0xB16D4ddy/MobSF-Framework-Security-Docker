# MobSF framework Security with docker-compose.yml

## Introduce

This repo help run mobsf with docker easier

## Usage

To use this docker please clone this repo and run below comand:

```bash
docker compose up -d
```

Or if you just want to run temporary container image on your local machine, you can use the following commands:

```bash
docker pull opensecurity/mobile-security-framework-mobsf:latest
docker run -it --rm -p 8000:8000 opensecurity/mobile-security-framework-mobsf:latest
```

Credentials for access

```python
    username = mobsf
    password = mobsf
```

# mainwp-container

**Please note: This is a work in progress.**

#### Overview

A dockerised server for MainWP Dashboard, a selfhosted tool for managing WordPress sites.

#### Quickstart

```cp .env.example .env
git clone https://github.com/richarah/mainwp-container
cd mainwp-container
cp .env.example .env
docker-compose up -d
```

Open `localhost:8000/wp-admin` in your browser to complete the setup and access the dashboard.

#### A note on networking

By default, the setup uses the bridge network `wordpress_network`. This may be reconfigured in `docker-compose.yml`.

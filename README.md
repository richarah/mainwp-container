# mainwp-container

**Please note: This is a work in progress.**

#### Overview

A dockerised server for MainWP Dashboard, a selfhosted tool for managing WordPress sites.

#### Quickstart

```cp .env.example .env
git clone https://github.com/richarah/mainwp-container
cd mainwp-container
cp .env.example .env # substitute default vars for your own
docker-compose up -d # start MainWP server
```

Open `localhost:8000` in your browser to complete the setup. The dashboard will then be accessible under `localhost:8000/wp-admin`.

#### A note on networking

By default, the setup uses the bridge network `wordpress_network`. This may be reconfigured in `docker-compose.yml`.

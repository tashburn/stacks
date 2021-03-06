
# 🛠 [Resources](/stack/) / Technical / Backend
{:.no_toc}

* TOC
{:toc}


## Lists / Writeups
- https://mangadex.dev/mangadex-v5-infrastructure-overview/
- one-person deployment, self hosting: https://cprimozic.net/blog/my-selfhosted-websites-architecture/
- backend infrastructure list: https://github.com/khuedoan/homelab
- https://bookface.ycombinator.com/posts/58603

## Admin Interfaces
- https://www.getmotoradmin.com/


## Analytics
- https://news.ycombinator.com/item?id=29888599


## Automation
- Zapier
- Segment


## Caching
- Redis


## Config Formats
- https://amzn.github.io/ion-docs/
- toml 
- yaml
- json


## Continuous Integration / Continuous Deployment
- Github actions
- Cloudflare pages
- Gitlab operations
- Reflect: No-code test automation platform for web applications


## CMS
- Sanity
- GraphCMS
- getkirby.com


## Databases
- ArangoDB
- Mongodb
- Postgres
- FoundationDB
- Couchbase
- Couchdb (+replication)
- OrientDB
- Rethinkdb
- Riak
- Scylladb
- SQLite
- Ceph (used at CERN)
- https://planetscale.com/
- https://planetscale.com/
- EdgeDB


## Data Warehousing, ETL, ELT, Analytics
- https://airbyte.io/ (YC)
- https://bookface.ycombinator.com/posts/57629
- Snowflake
- Cube: https://cube.dev/
- Segment for customer data
- metabase
- stitchdata


## Deployment
- Ansible
- Terraform
- Docker
- [Docker alternatives](https://news.ycombinator.com/item?id=28371788)
- [Docker alternatives](https://matt-rickard.com/docker-desktop-alternatives/)
- Kubernetes (with Kubespray playbooks)
- Hashicorp Nomad
- Civo
- K3s
- Cloud Run


## Documentation
- https://counterexamples.org/distinctness-injectivity.html


## Email services
- Mailgun
- SES
- Sendgrid


## Hosting
- Vercel
- Netlify
- Digital Ocean
- AWS
- Azure
- Heroku
- Linode
- Vultr
- Hetzner 
- https://dokku.com (self-hosted Heroku)
- Porter (self-hosted Heroku
- Primcloud
- K3s
- https://www.kimsufi.com/us/en/ (cheap dedicated)
- OVH
- Fly.io https://fly.io/


## Https Proxy
- Caddy


## Internal Tools
- Budibase


## Issue Tracking
- [Linear](https://linear.app)
- Closed


## Javascript / Typescript
- server frameworks: nextjs, gatsby
- state management: Recoil
- immutability: ImmerJS
- local data persistence: PouchDB 
- microservices: Molecular.js
- ORM: Prisma
- misc: Stimulus
- [time library](https://github.com/you-dont-need/You-Dont-Need-Momentjs)


## Logging
- Promtail
- Loki
- Ceph's Object Gateway (Rados Gateway) for persistent storage


## Microservices
- Service Mesh:
  - Consul
  - Istio 
  - "Kubernetes cluster per region with a CNI like Kilo which establishes a peer-to-peer network over Wireguard tunnels"


## "Modern" Data Stack
- Snowflake
- Bigquery
- dbt
- Airflow
- Kafka


## Monitoring / Instrumentation / Alerting
- Checklist: https://littlewarden.com/features
- Uptime Robot
- Errbit (error catcher)
- https://speakerdeck.com/caitiem20/tackling-alert-fatigue
- https://www.kitchensoap.com/2013/07/22/owning-attention-considerations-for-alert-design/
- Sentry: error tracking, performance monitoring
- Prometheus (collection/storage)
- Cortex (using remote write)
- Grafana (charts)
- Telegraph + Influxdb
- Product Analytics: (https://satchel.com/web-analytics/)
  - June (YC)
  - Fullstory (customer interaction)
  - Mixpanel (+ One Signal?)
  - Amplitude
  - Heap
  - OpenReplay


# ORMs
- Typescript/JS: Prisma


## Payments
- Stripe
- https://primer.io/ (connects multiple payment providers and does failover)


## Secrets Management
- https://bookface.ycombinator.com/posts/58578#comment-160437
- Doppler
- EnvKey
- AWS Secrets


## Security / Authentication
- How to secure your SAAS startup
  - https://github.com/forter/security-101-for-saas-startups  
  - https://paragonie.com/blog/2017/04/checklist-driven-security-considered-harmful
  - https://simplesecurity.sensedeep.com/web-developer-security-checklist-f2e4f43c9c56
- checklist: https://securitycheckli.st/
- securing postgres: https://goteleport.com/blog/securing-postgres-postgresql/
- Keycloak
- Auth0
- Authentication Best practices:
  - https://stackoverflow.com/questions/3391242/should-i-hash-the-password-before-sending-it-to-the-server-side
  - https://code.tutsplus.com/tutorials/securely-handling-users-login-credentials--cms-20369
  - https://www.owasp.org/index.php/Authentication_Cheat_Sheet
  - https://stackoverflow.com/questions/549/the-definitive-guide-to-form-based-website-authentication
  - https://cloudplatform.googleblog.com/2018/01/12-best-practices-for-user-account.html
- Secrets Management
  - Vault 
- "we also make sure to run on private networks, and that any user-facing application is kept behind a WAF. For this, we use the popular ModSecurity alongside the OWASP foundation's Core Rule Set and monitor closely or automatically block suspicious requests."


## Version Control
- git
- perforce
- plasticSCM


## Virtual Machines
- KVM
- LXC
- Management:
  - Proxmox


## Web App Platforms (db, auth, storage, hosting)
- Firebase
- Meteor
- Appwrite (open source Firebase alternative)
- Supabase (open source Firebase alternative)


## Web App Packaging as Native
- Flutter
- React Native


## Miscellaneous
- html boilerplate: https://www.matuzo.at/blog/html-boilerplate/
- Airtable (curation)
- noip.com (DNS for internet-connected devices)
- offline first, RxDB: https://rxdb.info/offline-first.html
- devops as solo-preneur: https://news.ycombinator.com/item?id=28838132
- tunneling: https://github.com/anderspitman/awesome-tunneling

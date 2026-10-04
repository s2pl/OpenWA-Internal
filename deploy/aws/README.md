AWS box compose files. Copy to the box as docker-compose.yml next to a real .env (never committed).
prod: openwa:prod on :2785, volume openwa_prod_openwa-data. uat: openwa:uat on :2786, volume openwa_uat_openwa-data.
Stop gracefully (compose stop_grace_period 60s) so Chromium can flush the session profile.

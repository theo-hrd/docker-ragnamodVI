## Steps:
 - change volume in `docker-compose.yml` where you want it to be
 - docker-compose up
 - open "volume/server-setup-config.yaml"
 - modify `checkOffline: yes` to `no` line `124`
 - uncomment and change `- url: https://media.forgecdn.net/files/3482/306/ftb-backups-2.1.2.2.jar` line `94`

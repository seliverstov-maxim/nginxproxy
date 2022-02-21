- `./bin/deploy`

on the server
- `./bin/gen-dh-params`
- `./bin/turn-on-vhost http serv1.dev73.ru`
- `dc up -d proxy`
- `./bin/request-ssl serv1.dev73.ru`
- `./bin/turn-on-vhost https serv1.dev73.ru`
- `dc restart proxy`

to turn off host: `./bin/turn-off-vhost https domain_name`
to turn on host: `./bin/turn-on-vhost https domain_name`
to upload project: `./bin/deploy`
to gen ssl conf: `./bin/gen-dh-params`

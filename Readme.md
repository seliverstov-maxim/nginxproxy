- `./bin/deploy`

on the server
- `./bin/gen-dh-params`
- `./bin/turn-on-vhost http serv1.dev73.ru`
- `dc up -d proxy`
- `./bin/request-ssl serv1.dev73.ru`
- `./bin/turn-on-vhost https serv1.dev73.ru`
- `dc restart proxy`

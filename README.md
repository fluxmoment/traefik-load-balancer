# Load Balancing with Traefik

## Automatic HTTPS
- modify email in traefik.yml:21
- HTTP to HTTPS redirect 

## Subdomain Routing
- see dyn-traefik.yml for example & modify accordingly
- Note Heroku requires a Host header equal to a myapp.herokuapps.com value. See the example in dyn-traefik.yml

### Get started
`docker-compose up -d`
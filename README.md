# Files for falmouth.lib.virginia.edu


# Development
## Requirements
- Docker running and set up on your computer
- Traefik set up
  - see [https://github.com/scholarslab/traefik ](https://github.com/scholarslab/traefik)
- A docker network named 'thenetwork'
- A copy of Omeka

## Run it
- `git clone https://github.com/scholarslab/falmouth.git`
- Change your local /etc/hosts file (Mac and Linux) 
- `docker-compose up`



# Changes made
## Omeka core files
- modified omeka/paths.php to use https only because it can't detect on it's own.

# To Do
- get omeka theme and plugin files into repository
- get changed Omeka paths.php file into repository

# Docker-ized PHP project scaffold

## Requirements:
- Expects reverse proxy container (i.e. https://github.com/mi-enfra/reverse-proxy)
- Configured host file

## How to Use:
`git clone git@github.com:mi-enfra/api-php-composer.git .`

`bash setup.sh`

- Configures project URL
- Builds image locally

`docker-compose up -d`
# dp-dev-site-local

Docker-compose for running web copies of babbage and zebedee-reader locally.

## Set up

- Build the docker web images for babbage & zebedee (instructions to follow)
- Set an environment args `WEB_CONTENT=` which points to your web copy of the site content.
- Run `docker-compose up`
- Go to http://localhost:8880/ and you should have the home page of the site.
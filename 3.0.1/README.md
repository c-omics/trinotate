# Trinotate-3.0.1

Trinotate-3.0.1 license: (see /usr/share/licenses/ within the container) 

## Useful Links

 * [package web-site](https://trinotate.github.io)
 * [container github-site](https://github.com/sglim2/docker-bio)
 * [Docker Hub](https://hub.docker.com/u/sglim2/)

## Example Usage
See the [container github-site](https://github.com/sglim2/docker-bio) for further usage documentation.

Start the container:
```bash
docker run -it sglim2/trinotate-3.0.1 bash
```

The Trinotate image contains the TrinotateWeb package. To run the trinotate web package you will need to start the container with an exposed port
```bash
docker run -it -p 8080:8080 sglim2/trinotate-3.0.1 run_TrinotateWebserver.pl 8080
```
Now point your browser to localhost:8080/cgi-bin/index.cgi to view the TrinotateWeb web page.


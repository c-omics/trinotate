# Trinotate

Trinotate license: (see /usr/share/licenses/ within the container) 

## Useful Links

 * [package web-site](https://trinotate.github.io)
 * [container github-site](https://github.com/c-omics/trinotate)
 * [Docker Hub](https://hub.docker.com/u/comics/)

## Example Usage
See the [container github-site](https://github.com/c-omics/) for further usage documentation.

Start the container:
```bash
docker run -it comics/trinotate bash
```

The Trinotate image contains the TrinotateWeb package. To run the trinotate web package you will need to start the container with an exposed port
```bash
docker run -it -p 8080:8080 comics/trinotate run_TrinotateWebserver.pl 8080
```
Now point your browser to localhost:8080/cgi-bin/index.cgi to view the TrinotateWeb web page.


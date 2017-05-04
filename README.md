# demo-ui5
A demo application to demonstrate using the OpenUI5 framework.

It uses the Northwind public OData database, this application is
just a nice frontend for the northwind backend.

## Getting Started

### Prerequisites

Make sure you've got [Docker](https://docs.docker.com/engine/installation/) 
and [docker-compose](https://docs.docker.com/compose/install/) installed.

### Steps

Download this repo:
```
$ git clone https://github.com/emmetog/demo-ui5.git
```

Then run docker-compose up from within the repo:
```
$ cd demo-ui5
$ docker-compose up
```

That's it. The first time you run it the image will be built, which 
might take a few minutes (subsequent builds will be much quicker though).
After the build finishes, go to this url in your browser:

[http://localhost:81](http://localhost:81)

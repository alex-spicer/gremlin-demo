# GREMLIN Demo

## Purpose
Demo consists of two docker-containers
* gremlin-server (port 8182)
* gremlin-graphexp javascript frontent (port 8183)

Both are started as docker-containers from a docker-compose file.
If you have docker-compose running you can simply start by tying 
`docker-compose up -d`

If you are on a windows machine and do not have native docker support (Win 8.1 and below), install vagrant and virtualbox.
Then you can start with `vagrant up`, ssh into the vbox (e.g. with putty)
and start the docker-containers there (Login is `vagrant`/`vagrant`, directory is `/vagrant`, )

If you are on linux or on Windows 10 you just can install docker-compose natively and start with `docker-compose`.

## To start
Just open http://localhost:8183 in your browser. In the screen press the `Search`-button

## Acknowledgements
This work relies on [graphexp](https://github.com/bricaud/graphexp) and [Gremlin-Server](https://hub.docker.com/r/bricaud/gremlin-server-with-demo-graph/) by [Benjamin Ricaud](https://github.com/bricaud/).

## License
See [LICENSE](https://github.com/joov/gremlin-demo/LICENSE). Graphexp is covered by [Apache-2.0-License](https://www.apache.org/licenses/LICENSE-2.0) and Gremlin-Server is covered by [MIT-License](https://github.com/bricaud/gremlin-server/blob/master/LICENSE).


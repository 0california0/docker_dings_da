# docker_dings_da
readme datei für das praktikum

hier passieren sachen

Microsoft Windows [Version 10.0.26200.8037]
(c) Microsoft Corporation. Alle Rechte vorbehalten.

C:\Users\Brygida>^wsl
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida$ docker
Usage:  docker [OPTIONS] COMMAND

A self-sufficient runtime for containers

Common Commands:
  run         Create and run a new container from an image
  exec        Execute a command in a running container
  ps          List containers
  build       Build an image from a Dockerfile
  bake        Build from a file
  pull        Download an image from a registry
  push        Upload an image to a registry
  images      List images
  login       Authenticate to a registry
  logout      Log out from a registry
  search      Search Docker Hub for images
  version     Show the Docker version information
  info        Display system-wide information

Management Commands:
  agent*      Docker AI Agent Runner
  ai*         Docker AI Agent - Ask Gordon
  builder     Manage builds
  buildx*     Docker Buildx
  checkpoint  Manage checkpoints
  compose*    Docker Compose
  container   Manage containers
  context     Manage contexts
  debug*      Get a shell into any image or container
  desktop*    Docker Desktop commands
  dhi*        CLI for managing Docker Hardened Images
  extension*  Manages Docker extensions
  image       Manage images
  init*       Creates Docker-related starter files for your project
  manifest    Manage Docker image manifests and manifest lists
  mcp*        Docker MCP Plugin
  model*      Docker Model Runner
  network     Manage networks
  offload*    Docker Offload
  plugin      Manage plugins
  sandbox*
  sbom*       View the packaged-based Software Bill Of Materials (SBOM) for an image
  scout*      Docker Scout
  system      Manage Docker
  volume      Manage volumes

Swarm Commands:
  config      Manage Swarm configs
  node        Manage Swarm nodes
  secret      Manage Swarm secrets
  service     Manage Swarm services
  stack       Manage Swarm stacks
  swarm       Manage Swarm

Commands:
  attach      Attach local standard input, output, and error streams to a running container
  commit      Create a new image from a container's changes
  cp          Copy files/folders between a container and the local filesystem
  create      Create a new container
  diff        Inspect changes to files or directories on a container's filesystem
  events      Get real time events from the server
  export      Export a container's filesystem as a tar archive
  history     Show the history of an image
  import      Import the contents from a tarball to create a filesystem image
  inspect     Return low-level information on Docker objects
  kill        Kill one or more running containers
  load        Load an image from a tar archive or STDIN
  logs        Fetch the logs of a container
  pause       Pause all processes within one or more containers
  port        List port mappings or a specific mapping for the container
  rename      Rename a container
  restart     Restart one or more containers
  rm          Remove one or more containers
  rmi         Remove one or more images
  save        Save one or more images to a tar archive (streamed to STDOUT by default)
  start       Start one or more stopped containers
  stats       Display a live stream of container(s) resource usage statistics
  stop        Stop one or more running containers
  tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
  top         Display the running processes of a container
  unpause     Unpause all processes within one or more containers
  update      Update configuration of one or more containers
  wait        Block until one or more containers stop, then print their exit codes

Global Options:
      --config string      Location of client config files (default "/home/nevio/.docker")
  -c, --context string     Name of the context to use to connect to the daemon (overrides DOCKER_HOST env var and
                           default context set with "docker context use")
  -D, --debug              Enable debug mode
  -H, --host string        Daemon socket to connect to
  -l, --log-level string   Set the logging level ("debug", "info", "warn", "error", "fatal") (default "info")
      --tls                Use TLS; implied by --tlsverify
      --tlscacert string   Trust certs signed only by this CA (default "/home/nevio/.docker/ca.pem")
      --tlscert string     Path to TLS certificate file (default "/home/nevio/.docker/cert.pem")
      --tlskey string      Path to TLS key file (default "/home/nevio/.docker/key.pem")
      --tlsverify          Use TLS and verify the remote
  -v, --version            Print version information and quit

Run 'docker COMMAND --help' for more information on a command.

For more help on how to use Docker, head to https://docs.docker.com/go/guides/
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida$ docker run -it --rm bsalgert/postgres:v1
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida$ sudo docker run -it --rm bsalgert/postgres:v1
[sudo] password for nevio:
Unable to find image 'bsalgert/postgres:v1' locally
v1: Pulling from bsalgert/postgres
d7ecded7702a: Pull complete
daee9001e881: Pull complete
020ec506a9a9: Pull complete
6fb1887789d5: Pull complete
cf13711e2d93: Pull complete
99c86b3ee082: Pull complete
d15ec67b8f25: Pull complete
4901ed08c960: Pull complete
4d36f395949b: Pull complete
79f0f9d42419: Pull complete
7e5e79cb13ce: Pull complete
f4ece806f018: Pull complete
433f50e81b26: Pull complete
ff87f7896919: Pull complete
fbffd8a8bfbd: Pull complete
9247a2ce79dd: Pull complete
Digest: sha256:142fd96174fbbd24996e1e3c9b6c09720caf86c9c8dd2444b43e3f5cdc0fecd0
Status: Downloaded newer image for bsalgert/postgres:v1
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - accepting connections
Database is ready!
Use \q to exit
Example: SELECT * FROM Movies;
psql (18.0 (Debian 18.0-1.pgdg13+3))
Type "help" for help.

postgres=# SELECT * FROM Movies
postgres-# \q
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida$ cd "C:\Users\Brygida\Documents\docker"
-bash: cd: C:\Users\Brygida\Documents\docker: No such file or directory
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida$ exit
logout

C:\Users\Brygida>cd C:\Users\Brygida\Documents\docker

C:\Users\Brygida\Documents\docker>docker
Usage:  docker [OPTIONS] COMMAND

A self-sufficient runtime for containers

Common Commands:
  run         Create and run a new container from an image
  exec        Execute a command in a running container
  ps          List containers
  build       Build an image from a Dockerfile
  bake        Build from a file
  pull        Download an image from a registry
  push        Upload an image to a registry
  images      List images
  login       Authenticate to a registry
  logout      Log out from a registry
  search      Search Docker Hub for images
  version     Show the Docker version information
  info        Display system-wide information

Management Commands:
  agent*      Docker AI Agent Runner
  ai*         Docker AI Agent - Ask Gordon
  builder     Manage builds
  buildx*     Docker Buildx
  compose*    Docker Compose
  container   Manage containers
  context     Manage contexts
  debug*      Get a shell into any image or container
  desktop*    Docker Desktop commands
  dhi*        CLI for managing Docker Hardened Images
  extension*  Manages Docker extensions
  image       Manage images
  init*       Creates Docker-related starter files for your project
  manifest    Manage Docker image manifests and manifest lists
  mcp*        Docker MCP Plugin
  model*      Docker Model Runner
  network     Manage networks
  offload*    Docker Offload
  plugin      Manage plugins
  sandbox*    Docker Sandbox
  sbom*       View the packaged-based Software Bill Of Materials (SBOM) for an image
  scout*      Docker Scout
  system      Manage Docker
  volume      Manage volumes

Swarm Commands:
  swarm       Manage Swarm

Commands:
  attach      Attach local standard input, output, and error streams to a running container
  commit      Create a new image from a container's changes
  cp          Copy files/folders between a container and the local filesystem
  create      Create a new container
  diff        Inspect changes to files or directories on a container's filesystem
  events      Get real time events from the server
  export      Export a container's filesystem as a tar archive
  history     Show the history of an image
  import      Import the contents from a tarball to create a filesystem image
  inspect     Return low-level information on Docker objects
  kill        Kill one or more running containers
  load        Load an image from a tar archive or STDIN
  logs        Fetch the logs of a container
  pause       Pause all processes within one or more containers
  port        List port mappings or a specific mapping for the container
  rename      Rename a container
  restart     Restart one or more containers
  rm          Remove one or more containers
  rmi         Remove one or more images
  save        Save one or more images to a tar archive (streamed to STDOUT by default)
  start       Start one or more stopped containers
  stats       Display a live stream of container(s) resource usage statistics
  stop        Stop one or more running containers
  tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
  top         Display the running processes of a container
  unpause     Unpause all processes within one or more containers
  update      Update configuration of one or more containers
  wait        Block until one or more containers stop, then print their exit codes

Global Options:
      --config string      Location of client config files (default
                           "C:\\Users\\Brygida\\.docker")
  -c, --context string     Name of the context to use to connect to the
                           daemon (overrides DOCKER_HOST env var and
                           default context set with "docker context use")
  -D, --debug              Enable debug mode
  -H, --host string        Daemon socket to connect to
  -l, --log-level string   Set the logging level ("debug", "info",
                           "warn", "error", "fatal") (default "info")
      --tls                Use TLS; implied by --tlsverify
      --tlscacert string   Trust certs signed only by this CA (default
                           "C:\\Users\\Brygida\\.docker\\ca.pem")
      --tlscert string     Path to TLS certificate file (default
                           "C:\\Users\\Brygida\\.docker\\cert.pem")
      --tlskey string      Path to TLS key file (default
                           "C:\\Users\\Brygida\\.docker\\key.pem")
      --tlsverify          Use TLS and verify the remote
  -v, --version            Print version information and quit

Run 'docker COMMAND --help' for more information on a command.

For more help on how to use Docker, head to https://docs.docker.com/go/guides/

C:\Users\Brygida\Documents\docker>wsl
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker
Usage:  docker [OPTIONS] COMMAND

A self-sufficient runtime for containers

Common Commands:
  run         Create and run a new container from an image
  exec        Execute a command in a running container
  ps          List containers
  build       Build an image from a Dockerfile
  bake        Build from a file
  pull        Download an image from a registry
  push        Upload an image to a registry
  images      List images
  login       Authenticate to a registry
  logout      Log out from a registry
  search      Search Docker Hub for images
  version     Show the Docker version information
  info        Display system-wide information

Management Commands:
  agent*      Docker AI Agent Runner
  ai*         Docker AI Agent - Ask Gordon
  builder     Manage builds
  buildx*     Docker Buildx
  checkpoint  Manage checkpoints
  compose*    Docker Compose
  container   Manage containers
  context     Manage contexts
  debug*      Get a shell into any image or container
  desktop*    Docker Desktop commands
  dhi*        CLI for managing Docker Hardened Images
  extension*  Manages Docker extensions
  image       Manage images
  init*       Creates Docker-related starter files for your project
  manifest    Manage Docker image manifests and manifest lists
  mcp*        Docker MCP Plugin
  model*      Docker Model Runner
  network     Manage networks
  offload*    Docker Offload
  plugin      Manage plugins
  sandbox*
  sbom*       View the packaged-based Software Bill Of Materials (SBOM) for an image
  scout*      Docker Scout
  system      Manage Docker
  volume      Manage volumes

Swarm Commands:
  config      Manage Swarm configs
  node        Manage Swarm nodes
  secret      Manage Swarm secrets
  service     Manage Swarm services
  stack       Manage Swarm stacks
  swarm       Manage Swarm

Commands:
  attach      Attach local standard input, output, and error streams to a running container
  commit      Create a new image from a container's changes
  cp          Copy files/folders between a container and the local filesystem
  create      Create a new container
  diff        Inspect changes to files or directories on a container's filesystem
  events      Get real time events from the server
  export      Export a container's filesystem as a tar archive
  history     Show the history of an image
  import      Import the contents from a tarball to create a filesystem image
  inspect     Return low-level information on Docker objects
  kill        Kill one or more running containers
  load        Load an image from a tar archive or STDIN
  logs        Fetch the logs of a container
  pause       Pause all processes within one or more containers
  port        List port mappings or a specific mapping for the container
  rename      Rename a container
  restart     Restart one or more containers
  rm          Remove one or more containers
  rmi         Remove one or more images
  save        Save one or more images to a tar archive (streamed to STDOUT by default)
  start       Start one or more stopped containers
  stats       Display a live stream of container(s) resource usage statistics
  stop        Stop one or more running containers
  tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE
  top         Display the running processes of a container
  unpause     Unpause all processes within one or more containers
  update      Update configuration of one or more containers
  wait        Block until one or more containers stop, then print their exit codes

Global Options:
      --config string      Location of client config files (default "/home/nevio/.docker")
  -c, --context string     Name of the context to use to connect to the daemon (overrides DOCKER_HOST env var and
                           default context set with "docker context use")
  -D, --debug              Enable debug mode
  -H, --host string        Daemon socket to connect to
  -l, --log-level string   Set the logging level ("debug", "info", "warn", "error", "fatal") (default "info")
      --tls                Use TLS; implied by --tlsverify
      --tlscacert string   Trust certs signed only by this CA (default "/home/nevio/.docker/ca.pem")
      --tlscert string     Path to TLS certificate file (default "/home/nevio/.docker/cert.pem")
      --tlskey string      Path to TLS key file (default "/home/nevio/.docker/key.pem")
      --tlsverify          Use TLS and verify the remote
  -v, --version            Print version information and quit

Run 'docker COMMAND --help' for more information on a command.

For more help on how to use Docker, head to https://docs.docker.com/go/guides/
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ SELECT * FROM Movies
SELECT: command not found
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker run -it --rm bsalgert/postgres:v1
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run -it --rm bsalgert/postgres:v1
[sudo] password for nevio:
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - accepting connections
Database is ready!
Use \q to exit
Example: SELECT * FROM Movies;
psql (18.0 (Debian 18.0-1.pgdg13+3))
Type "help" for help.

postgres=# SELECT * FROM Movies
postgres-# \q
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run -it --rm bsalgert/postgres:v1
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - accepting connections
Database is ready!
Use \q to exit
Example: SELECT * FROM Movies;
psql (18.0 (Debian 18.0-1.pgdg13+3))
Type "help" for help.

postgres=# docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
postgres-# docker run -d --name mydb bsalgert/postgres:v1 /demon.sh
postgres-# docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
postgres-# cd C:\Users\Brygida\Documents\docker
invalid command \Users
Try \? for help.
postgres-# \q
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker run -it --rm bsalgert/postgres:v1
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run -it --rm bsalgert/postgres:v1
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - accepting connections
Database is ready!
Use \q to exit
Example: SELECT * FROM Movies;
psql (18.0 (Debian 18.0-1.pgdg13+3))
Type "help" for help.

postgres=# cd C:\Users\Brygida\Documents\docker
invalid command \Users
Try \? for help.
postgres-# docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
postgres-# docker ps
postgres-# exit
Use \q to quit.
postgres-# \q
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker ps
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker run -it --rm bsalgert/postgres:v1
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run -it --rm bsalgert/postgres:v1



localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - accepting connections
Database is ready!
Use \q to exit
Example: SELECT * FROM Movies;
psql (18.0 (Debian 18.0-1.pgdg13+3))
Type "help" for help.

postgres=#
postgres=# docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
postgres-#
postgres-# \q
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ ls
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
[sudo] password for nevio:
psql:/script.sql: error: could not read from input file: Is a directory
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run --rm -v $(pwd)/script.sql:/script.sql -e SQ
L_FILE=/script.sql bsalgert/postgres:v1 > result.log
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run -d --name mydb bsalgert/postgres:v1 /demon.
sh
c5bf3d3ccc5cd14f2e0ce1f491b915324cd72fecf79e2ceca6f542dd6d681810
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker ps
CONTAINER ID   IMAGE                  COMMAND                  CREATED          STATUS          PORTS      NAMES
c5bf3d3ccc5c   bsalgert/postgres:v1   "docker-entrypoint.s…"   22 seconds ago   Up 21 seconds   5432/tcp   mydb
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker ps
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker ps
CONTAINER ID   IMAGE                  COMMAND                  CREATED              STATUS              PORTS      NAMES
c5bf3d3ccc5c   bsalgert/postgres:v1   "docker-entrypoint.s…"   About a minute ago   Up About a minute   5432/tcp   mydb
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker exec -it mydb bash
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker exec -it mydb bash
root@c5bf3d3ccc5c:/# ls
bin   demon.sh  docker-entrypoint-initdb.d  home  lib64  mnt  proc  run   srv       sys  usr
boot  dev       etc                         lib   media  opt  root  sbin  start.sh  tmp  var
root@c5bf3d3ccc5c:/# cd homse
bash: cd: homse: No such file or directory
root@c5bf3d3ccc5c:/# cd home
root@c5bf3d3ccc5c:/home# ls
root@c5bf3d3ccc5c:/home# cd ..
root@c5bf3d3ccc5c:/# exit
exit
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker run --rm -v $(pwd)/script.sql:/script.sql -e SQL_FILE=/script.sql bsalgert/postgres:v1 > result.log
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ ls
result.log  script.sql
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ cat result.log
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - no response
localhost:5432 - rejecting connections
localhost:5432 - accepting connections
Database is ready!
Use \q to exit
Example: SELECT * FROM Movies;
SELECT * FROM Movies;
 movie_id |                        title                        | releasedate | genre_id |  budget   | openingweek |  profit   | runtime | certificate | sequelof |        distribution
----------+-----------------------------------------------------+-------------+----------+-----------+-------------+-----------+---------+-------------+----------+----------------------------
        1 | Avatar - Aufbruch nach Pandora                      | 2009-12-17  |        1 | 237000000 |    77025481 | 760505847 |     162 |          12 |          | 20th Century Fox
        2 | Titanic                                             | 1997-12-14  |        2 | 200000000 |    28638131 | 658672302 |     194 |          12 |          | Paramount Pictures
        3 | Star Wars: Das Erwachen der Macht                   | 2015-12-14  |        1 | 245000000 |   247966675 | 936627416 |     136 |          12 |          | Walt Disney Studios
        4 | Jurassic World                                      | 2015-12-14  |        1 | 150000000 |   204600000 | 652177271 |     124 |          12 |          | Universal Studios
        5 | The Avengers                                        | 2012-04-11  |        3 | 220000000 |   207438708 | 623279547 |     143 |          12 |          | Walt Disney Studios
        6 | Fast & Furios 7                                     | 2016-03-15  |        4 | 190000000 |   147187040 | 350034110 |     137 |          12 |          | Universal Studios
        7 | Avengers: Age of Ultron                             | 2015-04-13  |        3 | 250000000 |   191271109 | 458991599 |     141 |          12 |        5 | Walt Disney Studios
        8 | Harry Potter und die Heiligtümer des Todes – Teil 2 | 2011-07-11  |        5 | 125000000 |   169189427 | 380955619 |     130 |          12 |          | Warner Bros. Entertainment
        9 | Die Eiskönigin – Völlig unverfroren                 | 2011-10-11  |        6 | 150000000 |    67391326 | 400736600 |     102 |           0 |          | Walt Disney Studios
       10 | Die Schöne und das Biest                            | 2017-03-17  |        5 | 160000000 |   174750616 | 503974884 |     129 |           6 |          | Walt Disney Studios
       11 | Fast & Furious 8                                    | 2017-04-04  |        4 | 250000000 |    98786705 | 225697400 |     136 |          12 |        6 | Universal Studios
       12 | Iron Man 3                                          | 2013-04-12  |        4 | 200000000 |   174144585 | 408992272 |     130 |          12 |          | Walt Disney Studios
       13 | Minions                                             | 2015-06-11  |        4 |  74000000 |   115200000 | 336029560 |      91 |           0 |          | Universal Studios
       14 | The First Avenger: Civil War                        | 2016-04-28  |        3 | 250000000 |   179139142 | 408080554 |     147 |          12 |          | Walt Disney Studios
       15 | Transformers 3 – Die dunkle Seite des Mondes        | 2011-06-29  |        3 | 195000000 |   115886050 | 352358779 |     154 |          12 |          | Paramount Pictures
       16 | Der Herr der Ringe: Die Rückkehr des Königs         | 2003-12-17  |        5 |  94000000 |    72629713 | 377019252 |     201 |          12 |          | New Line Cinema
       17 | James Bond 007: Skyfall                             | 2012-11-01  |        4 | 200000000 |    88364714 | 304360277 |     143 |          12 |          | Metro-Goldwyn-Mayer
       18 | Transformers: Ära des Untergangs                    | 2014-07-17  |        3 | 210000000 |   100038390 | 245428137 |     165 |          12 |       15 | Paramount Pictures
       19 | The Dark Knight Rises                               | 2012-07-26  |        3 | 250000000 |   160887295 | 448130642 |     164 |          12 |          | Warner Bros. Entertainment
       20 | Toy Story 3                                         | 2010-07-29  |        6 | 200000000 |   109000000 | 414984497 |     103 |           0 |          | Walt Disney Studios
(20 rows)

nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker ps
CONTAINER ID   IMAGE                  COMMAND                  CREATED         STATUS         PORTS      NAMES
c5bf3d3ccc5c   bsalgert/postgres:v1   "docker-entrypoint.s…"   4 minutes ago   Up 4 minutes   5432/tcp   mydb
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker exec -it mydb bash
root@c5bf3d3ccc5c:/# psql -U postgres -d postgres
psql (18.0 (Debian 18.0-1.pgdg13+3))
Type "help" for help.

postgres=# SELECT* FROM Movies
postgres-# SELECT * FROM Movies;
ERROR:  syntax error at or near "SELECT"
LINE 2: SELECT * FROM Movies;
        ^
postgres=# select * from Movies;
postgres=# exit
root@c5bf3d3ccc5c:/# exit
exit
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker ps
CONTAINER ID   IMAGE                  COMMAND                  CREATED         STATUS         PORTS      NAMES
c5bf3d3ccc5c   bsalgert/postgres:v1   "docker-entrypoint.s…"   7 minutes ago   Up 7 minutes   5432/tcp   mydb
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ docker stop mydb
permission denied while trying to connect to the docker API at unix:///var/run/docker.sock
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker stop mydb
sudo docker ps
mydb
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$ sudo docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
nevio@DESKTOP-U5HVH5T:/mnt/c/Users/Brygida/Documents/docker$

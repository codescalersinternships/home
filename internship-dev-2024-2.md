## intro 
This is a rough plan of the development internship program for 2024 -8 to 10 weeks program-. The intern need to be able to reason about the code, and be able to write tests (units and integration), then they should be able to contribute to the daily work with the team.


## Week 0

In this week we spend some time to get familiar with the basics of linux, git, shell, and how to read the documentation

- https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J ( lect 1-7)
- Effective Shell: https://effective-shell.com
- Linux Intro/Essentials https://lym.readthedocs.io/en/latest/ (till Linux Services, package management (apt only), networking commands)
- Reading manpages of `echo, env, cat, wc, head, tail, yes, true, false, tree`
- git https://www.atlassian.com/git (branches, commit, log, merge, rebase, tag, github flow)

### extra
- audit courses https://www.coursera.org/professional-certificates/google-it-support
- https://ubuntu.com/server/docs

## Week 1

We get our feet with learning the fundamentals of Go, and start developing small utilities in Go.

- Go fundamentals [gobyexample](https://gobyexample.com)
- coreutils https://github.com/codescalersinternships/home/issues/105: `echo, env, cat, wc, head, tail, yes, true, false, tree` (use gobyexample to speed up things)
- build your own git https://leshenko.net/p/ugit/# (5 steps)


## Week 2

We introduce you to the testing, writing unit tests, configuring github workflows.

- [learn Go with tests](https://quii.gitbook.io/learn-go-with-tests/)
- INI Parser project with tests https://github.com/codescalersinternships/home/issues/21 
- Github [Workflows](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
- build your own git https://leshenko.net/p/ugit/# (5 steps)


## Week 3

In this week we develop a small http service and we cover how to test it and how to build a client to consume its api

- Datetime server https://github.com/codescalersinternships/home/issues/144
- HTTP Service testing
- DateTime http client https://github.com/codescalersinternships/home/issues/145
- [context package](https://medium.com/rungo/understanding-the-context-package-b2e407a9cdae)
- build your own git https://leshenko.net/p/ugit/# (5 steps)

### Extra

- [go101](https://go101.org/article/101.html)
- [ultimatego](https://github.com/hoanhan101/ultimate-go)

## Week 4

In this week we get familiar with docker and docker compose, what they do, and how to build a docker image, and how to reduce its size. Then we go through REST API, Swagger, and Postman. and we will build a small client that consumes the pokemon Restful API service. 

- Docker
- Multistaged builds https://fabianlee.org/2020/01/26/golang-using-multi-stage-builds-to-create-clean-docker-images/
- Docker compose
- REST API
- Swagger
- Postman
- pokemon API https://pokeapi.co/ (create http client for pokemon API + tests) https://github.com/codescalersinternships/home/issues/146
- build your own git https://leshenko.net/p/ugit/# (5 steps)

### Resources

- docker docs https://docs.docker.com/engine/install/ubuntu/
- https://www.youtube.com/watch?v=3c-iBn73dDE
- https://www.youtube.com/watch?v=pTFZFxd4hOI
- https://www.youtube.com/watch?v=HG6yIjZapSA
- https://www.youtube.com/watch?v=PrusdhS2lmo
- https://www.youtube.com/watch?v=X48VuDVv0do
- docker docs https://docs.docker.com/engine/install/ubuntu/
- https://www.youtube.com/watch?v=3c-iBn73dDE
- https://www.youtube.com/watch?v=pTFZFxd4hOI
- https://www.youtube.com/watch?v=HG6yIjZapSA
- https://www.youtube.com/watch?v=PrusdhS2lmo
- multistaged builds https://fabianlee.org/2020/01/26/golang-using-multi-stage-builds-to-create-clean-docker-images/
- https://www.youtube.com/watch?v=X48VuDVv0do


## Week 5

Here we introduce you to the concept of MVC.

- Secret Note MVC https://github.com/codescalersinternships/home/issues/153
- build your own git https://leshenko.net/p/ugit/# (5 steps)


## Week 6

In this week we will redo the project as SPA, by providing two services: an API service and a frontend that consumes that API -next week-
- Secret Note API https://github.com/codescalersinternships/home/issues/152

## Week 7
- Frontend https://github.com/codescalersinternships/home/issues/152 
- build your own git https://leshenko.net/p/ugit/# (5 steps)


### Resources

- Frontend track https://github.com/MohamedElmdary/cat-frontend-circle-road-map
- https://github.com/MohamedElmdary/frontend-session-resources
- [Vue.js](https://vuejs.org/)
- [React Megatutorial](https://blog.miguelgrinberg.com/post/the-react-mega-tutorial-chapter-1-modern-javascript)
- https://selenium-python.readthedocs.io/locating-elements.html
- https://www.toolsqa.com/selenium-webdriver/selenium-locators/
- https://filiphric.com/cypress-basics-selecting-elements
- Cypress https://testautomationu.applitools.com/advanced-cypress-tutorial/

Testing session: https://docs.google.com/presentation/d/1ljUyCXWN-ZF3FyNDUOYXoyOrEagy_DoXWeL5wDMF47Y/edit?usp=sharing

## Week 8 (onboarding to threefold)
Starting from that week the intern should be able to write testable code and can be introduced to our platform and projects. Best intro the platform by manually testing the capabilities and reporting issues on the normal of the enduser. 

- Intro to Codescalers and TFGrid Platform
- How to write a bug report https://www.softwaretestinghelp.com/how-to-write-good-bug-report/
- Manual Testing 
- Namespaces, CGroups, Docker
- The Dashboard and deploying your first machine on the threefold grid)
- Terraform and deploying your virtual machines machines on the threefold grid)
- Rust fundamentals
- Manually Testing the platform (intro to testlodge -qa tool we use to develop and track our tests-)

## Week 9-end of internship week 10 distributed on teams (sdk-go, zos, sdk-ts, sdk-dart)

- 4 solutions
- GPU services integration *
- ZOS service rewrites in rust
- Freeflow twin
- Threefold Connect *
- Planetary Desktop/mobile App
- Increase code coverage
- Deployments web builder (drag/drop)
- IaC
- heroku like system on the grid maybe? gridify pushing forward


## Extra tasks

- RESP Parser https://github.com/codescalersinternships/home/issues/275
- dotenv https://github.com/codescalersinternships/home/issues/208
- Makego https://github.com/codescalersinternships/home/issues/157
- Busybox img https://github.com/codescalersinternships/home/issues/103
- NTP https://github.com/codescalersinternships/home/issues/141
- BMP Width/Height https://github.com/codescalersinternships/home/issues/142
- Msgpack https://github.com/codescalersinternships/home/issues/240
- [bitcask paper](https://github.com/codescalersinternships/home/issues/37)


## Sessions
- REST API
- GraphQL
- Protobuf
- gRPC
- Concurrency
- Blockchain
- Vue
- Docker/CGroups
- Testing
- Redis
- UNIX Programming
- Caddy
- Zinit
- Flist
- Raft
- Packer
- Zig
- TLS
- Encryption (symmetric/asymmetric)
- 12 factor apps https://12factor.net
- Github flow https://docs.github.com/en/get-started/quickstart/github-flow
- Building a small busybox based distro

## daily work 
- write your own git: https://leshenko.net/p/ugit/#
- [creating package in 2022](https://mathspp.com/blog/how-to-create-a-python-package-in-2022)
- [python](https://docs.python.org/3/tutorial/index.html)
- [django rest framework DRF](https://www.django-rest-framework.org/)
- [pymotw](https://pymotw.com/3/) 
- [jinja](https://jinja.palletsprojects.com/en/2.10.x/)
- [bottle](https://bottlepy.org/docs/dev/)
- [exploreflask](https://exploreflask.com/en/latest/)
- [flask megatuorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
- [TDD with python/django](https://www.obeythetestinggoat.com)
- [redis university](https://university.redis.com)
- [redis in action](https://redislabs.com/redis-in-action/) is a book that will help you to know redis by practice.
- The following topics are important to know about Redis:
  - Data structures
  - Pub/Sub [Guide link 1](https://redis.io/topics/pubsub) | [Guide link 2](https://www.tutorialspoint.com/redis/redis_pub_sub.htm) | [Video](https://youtu.be/33N1mgiRYK0)
  - Data persistence (snapshots & AOF) [Guide link](https://redis.io/topics/persistence)  | [Video](https://youtu.be/Hbt56gFj998?t=2042)
  - Transactions [Guide link](https://www.tutorialspoint.com/redis/redis_transactions.htm)
  - Distributed locking [Guide link1](https://redis.io/topics/distlock) | [Guide link2](https://medium.com/@rohansaraf/distributed-locking-with-redis-ecb0773e7695)
  - Resp Protocol [Guide link](https://redis.io/topics/protocol)
### Software development process / testing

- Trunk based development https://trunkbaseddevelopment.com/


## networking
- [CCNA/CCNP](https://www.youtube.com/playlist?list=PL77yNtB4-LjnN2FU3h1v5hIJOHZfW9ugq)



## linux 
- effective shell: https://effective-shell.com
- [ubuntu server guide](https://help.ubuntu.com/lts/serverguide/)
- [nginx](https://www.nginx.com/)
- [debian handbook](https://debian-handbook.info)
- [tmux](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)
- [building root filesystem](https://emreboy.wordpress.com/2012/12/20/building-a-root-file-system-using-busybox/)
- [coredns](https://coredns.io)
- https://www.nginx.com/blog/what-are-namespaces-cgroups-how-do-they-work/ 
- https://www.youtube.com/watch?v=8fi7uSYlOdc
- [build container in 500Lines](https://blog.lizzie.io/linux-containers-in-500-loc.html)
- [unix programming](https://stevens.netmeister.org/631/#syllabus)
- 
## Raft/Distributed systems
- https://learn.particular.net/courses/distributed-systems-design-fundamentals-online
- slides: https://thesecretlivesofdata.com/raft/
- https://raft.github.io
- https://en.wikipedia.org/wiki/Raft_(algorithm)

## binary serialization
- https://capnproto.org/
- https://google.github.io/flatbuffers/
- https://developers.google.com/protocol-buffers

## Optional:
- Kubernetes
- Helm Charts
- Blockchain (substrate, cosmos, solidity?)

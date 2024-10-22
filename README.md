HTTP(S) benchmark tools, testing/debugging, & restAPI (RESTful)
---------------------------------------------------------------
*Located in alphabetical order (not prefer)*

HTTP(S) Benchmark Tools
=======================
* [__ab__](http://en.wikipedia.org/wiki/ApacheBench) – slow in single-threaded can be made more efficient by [`taskset`](https://man7.org/linux/man-pages/man1/taskset.1.html), written in `C`
* [__ali__](https://github.com/nakabonne/ali) – Generate HTTP load and plot the results in real-time, written in Go (`golang`)
* [__apib__](https://github.com/apigee/apib) – most of the features of ApacheBench (`ab`), also designed as a [more modern replacement](https://github.com/apigee/apib#design), written in `C`
* [__autocannon__](https://github.com/mcollina/autocannon) – fast HTTP/1.1 benchmarking tool written in Node.js
* [__baloo__](https://github.com/h2non/baloo) – Expressive end-to-end HTTP API testing made easy, written in Go (`golang`)
* [__baton__](https://github.com/americanexpress/baton) – HTTP load testing, written in Go (`golang`)
* [__Bencher__](https://bencher.dev/) - A suite of continuous benchmarking tools designed to catch performance regressions in CI
* [__bombardier__](https://github.com/codesenberg/bombardier) – Fast crossplatform HTTP benchmarking tool, written in Go (`golang`)
* [__cassowary__](https://github.com/rogerwelin/cassowary) – is a modern HTTP(S), intuitive & cross-platform load testing tool, written in Go (`golang`)
* [__curl-loader__](http://curl-loader.sourceforge.net/) – performance loading of various application services and traffic generation, written in `C`
* [__ddosify__](https://github.com/ddosify/ddosify) – High-performance load testing tool, written in Go (`golang`)
* [__drill__](https://github.com/fcsonline/drill) – Drill is a HTTP load testing application inspired by Ansible syntax, written in `Rust`
* [__fasthttploader__](https://github.com/hagen1778/fasthttploader) – benchmark (kinda ab) with autoadjustment and charts based on fasthttp library, written in Go (`golang`)
* [__fbender__](https://github.com/facebookincubator/fbender) – A load-testing command line tool for generic network protocols (`HTTP`, `DNS`, `DHCP`, …), written in Go (`golang`)
* [__fortio__](https://github.com/istio/fortio) – load testing library and command line tool and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats, written in Go (`golang`)
* [__gatling__](http://gatling.io) – High performance load testing framework based on Scala, Akka and Netty, written in `Scala`
* [__go-wrk__](https://github.com/tsliwowicz/go-wrk) – a HTTP benchmarking tool based in spirit on the excellent wrk tool ([`wg/wrk`](https://github.com/wg/wrk)), written in Go (`golang`)
* [__goad__](https://github.com/gophergala2016/goad) – Goad is an AWS Lambda powered, highly distributed, load testing tool, written in Go (`golang`)
* [__gobench__](https://github.com/cmpxchg16/gobench) – HTTP/HTTPS load testing and benchmarking tool, written in Go (`golang`)
* [__gohttpbench__](https://github.com/parkghost/gohttpbench) – `ab`-like benchmark tool run on multi-core cpu, written in Go (`golang`)
* [__goloris__](https://github.com/valyala/goloris) – Slowloris for NGINX DoS attack, written in Go (`golang`)
* [__goose__](https://github.com/tag1consulting/goose) - A modern, high-performance and flexible distributed HTTP(S) load testing tool, written in `Rust`
* [__h2load__](https://nghttp2.org/documentation/h2load-howto.html) - benchmarking tool for HTTP/2 and HTTP/1.1. It supports SSL/TLS and clear text for all supported protocols, written in `C`/`C++`
* [__hey__](https://github.com/rakyll/hey) – HTTP(S) load generator, ApacheBench (`ab`) replacement, formerly known as [__rakyll/boom__](https://github.com/rakyll/boom), written in Go (`golang`)
* [__htstress__](https://github.com/arut/htstress) – multithreading high-load bechmarking services (>5K rps), written in `C`/`Linux`
* [__httperf__](https://github.com/httperf/httperf) – difficult configuration, slow and single threaded, written in `C`
* [__httping__](https://github.com/folkertvanheusden/httping) - Ping with HTTP requests, see http://www.vanheusden.com/httping/, written in `C`
* [__httpit__](https://github.com/gonetx/httpit) - A rapid http(s) benchmark tool, written in `golang`
* [__inundator__](https://github.com/opsengine/inundator) – A simple and high-throughput HTTP flood program, written in `C`/`Linux`
* [__jmeter__](http://jmeter.apache.org/) – Apache  JMeter™, pure application designed to load test performance both on static and dynamic resources, written in `Java`
* [__k6__](https://github.com/loadimpact/k6) - A modern load testing tool scriptable in ES6 JS with support for HTTP/1.1, HTTP/2.0 and WebSocket, written in Go (`golang`)
* [__locust__](https://locust.io/) – easy-to-use, distributed load testing tool with real-time web UI. Simulates a swarm of concurrent users, the behavior of each of them is defined by your python code. Written in `Python`
* [__lor-axe__](https://github.com/ajmwagar/lor-axe) – A multi-threaded, low-bandwidth HTTP Slowloris DoS tool that handles connections and sockets in parallel, written in `Rust`
* [__mgun__](https://github.com/byorty/mgun) – A modern tool for load testing HTTP servers, written in Go (`golang`)
* [__molotov__](https://github.com/tarekziade/molotov) - A simple `Python` 3.7+ tool to write load tests
* [__NBomber__](https://github.com/PragmaticFlow/NBomber) – Modern and flexible load testing framework for Pull and Push scenarios, designed to test any system regardless a protocol (HTTP/WebSockets/AMQP etc) or a semantic model (Pull/Push), written in F# (`F Sharp`)
* [__Netling__](https://github.com/hallatore/Netling) – Netling is a load tester client for easy web testing., written in C# (`C Sharp`)
* [__oha__](https://github.com/hatoo/oha) – HTTP load generator, inspired by rakyll/hey with tui animation, written in `Rust`
* [__pewpew__](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress testing tool for websites and web services, written in Go (`golang`)
* [__plow__](https://github.com/six-ddc/plow) – A high-performance HTTP benchmarking tool with real-time web UI and terminal displaying, written in Go (`golang`)
* [__pounce__](https://github.com/fredrikwidlund/pounce) – event-driven with a similar interface as `wrk` but with the ambition to potentially achieve lower latency and higher throughout, written in `C`
* [__rewrk__](https://github.com/ChillFish8/rewrk) – A more modern http framework benchmarker supporting HTTP/1 and HTTP/2 benchmarks, written in `Rust`.
* [__reqstress__](https://github.com/utkusen/reqstress) – a benchmarking&stressing tool that can send raw HTTP requests, written in Go (`golang`).
* [__salvo__](https://github.com/tarekziade/salvo) - A simple HTTP(S) load testing tool like [boom](https://github.com/tarekziade/boom), but based on [molotov](https://github.com/loads/molotov). `Python`
* [__siege__](http://www.joedog.org/siege-home/) – multithreaded concurrent connections and slow single-user, written in `C`
* [__slapper__](https://github.com/ikruglov/slapper) – Simple load testing tool with real-time updated histogram of request timings, written in Go (`golang`)
* [__slow_cooker__](https://github.com/BuoyantIO/slow_cooker) – A load tester focused on lifecycle issues and long-running tests, service with a predictable load and concurrency level for a long period of time, written in Go (`golang`)
* [__slowhttptest__](https://github.com/shekyan/slowhttptest) – Application Layer DoS attack simulator, written in `C++`
* [__sniper__](https://github.com/lubia/sniper) – powerful & high-performance http load tester, written in Go (`golang`)
* [__thrash__](https://github.com/TylerBrock/thrash) – HTTP Micro Benchmarker, written in Go (`golang`)
* [__tsung__](http://tsung.erlang-projects.org/) – Simulate stress users in order to test the scalability and performance of IP based client/server applications `HTTP`, `WebDAV`, `SOAP`, `PostgreSQL`, `MySQL`, `LDAP` and `Jabber`/`XMPP` servers, written in `Erlang`
* [__vegeta__](https://github.com/tsenart/vegeta) – HTTP load testing tool and library, written in Go (`golang`)
* [__weighttp__](https://github.com/lighttpd/weighttp) – multithreaded, but slower than htstress without keepalive, written in `C`
* [__welle__](https://github.com/rylev/welle) – ab (Apache Benchmark) like tool, written in `Rust`
* [__wrk__](https://github.com/wg/wrk) – multithreaded, ~~but doesn't offer concurrent connections and a keepalive switch~~, written in `C`/`Lua`
* [__wrk2__](https://github.com/giltene/wrk2) – constant throughput, correct latency recording variant of wrk, written in `C`/`Lua`

        Concurrent connections are enabled with:
          -c, --connections <N>  Connections to keep open
        And keepalive (which is default) can be disabled using:
          -H "Connection: close"
* [__yandex-tank__](https://github.com/yandex/yandex-tank) – Load and performance benchmark tool, written in `Python`/`C|C++|Asm` ([phantom](https://github.com/yandex-load/phantom))

Toolkit for testing/debugging HTTP(S) and restAPI (RESTful)
===========================================================
* [__bat__](https://github.com/astaxie/bat) – Go implement CLI, cURL-like tool for humans, written in Go (`golang`)
* [__Bruno__](https://www.usebruno.com/) – is a Fast and Git-Friendly Opensource API client
* [__curl__](https://github.com/curl/curl) – Powerful features command-line tool for transferring data specified with URL syntax, written in `C`
  - [Online curl command line builde](https://curlbuilder.com/)
* [__curlconverter__](https://github.com/NickCarneiro/curlconverter) – convert curl commands to python, javascript, php
* [__hoppscotch__](https://github.com/hoppscotch/hoppscotch) - API request builder
* [__DeepfakeHTTP__](https://github.com/xnbox/DeepfakeHTTP) – is a web server that uses HTTP dumps as a source for responses, written in `Java`
* [__httpie__](https://github.com/jkbrzt/httpie) – client, user-friendly curl replacement with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, written in `Python`
* [__HTTPie Desktop__](https://httpie.io/docs/desktop) – HTTPie Desktop is a cross-platform API testing client for humans. Use it to test REST, GraphQL, and HTTP APIs painlessly.
* [__curlie__](https://curlie.io) – If you like the interface of [HTTPie](https://httpie.org) but miss the features of [curl](https://curl.haxx.se), curlie is what you are searching for. Curlie is a drop-in replacement for `httpie` that use `curl` to perform operations, written in Go (`golang`)
* [__xh__](https://github.com/ducaale/xh) – Yet another [HTTPie](https://httpie.org) clone, written in `Rust`
* [__httpstat__](https://github.com/reorx/httpstat) - It's like curl -v, with colours
* [__hurl__](https://github.com/Orange-OpenSource/hurl) - Hurl is a command line tool that runs HTTP requests defined in a simple plain text format
* [__insomnia__](https://insomnia.rest/) - simple, beautiful, and free Desktop REST API client (`Mac`, `Windows`, and `Linux`)
* [__jaggr__](https://github.com/rs/jaggr) – JSON Aggregation CLI, Jaggr can be used to integrate [vegeta](https://github.com/tsenart/vegeta) with [jplot](https://github.com/rs/jplot), written in Go (`golang`)
* [__jq__](https://github.com/stedolan/jq) – is a lightweight and flexible command-line JSON processor, written in `C`
* https://github.com/marmelab/awesome-rest
* https://github.com/stepci/awesome-api-clients
* https://github.com/mrmykey/awesome-http-clients

SaaS/PaaS
=========
* [__BlazeMeter__](https://blazemeter.com/) – offers a cross-enterprise test automation framework for the entire technical team (developers, devops, ops and QA) throughout the product development lifecycle. Run continuous or ‘on demand’ testing for APIs, mobile apps and websites. Run from the cloud, on-premise or as a hybrid solution. Use with JMeter &amp; Selenium WebDriver &amp; integrate with your existing CI, CD &amp; APM tools.
* [__NewRelic__](http://newrelic.com/) – software analytics tool suite used by developers, ops, and software companies to understand how your applications are performing in development and production
* [__NGINX Amplify__](https://amplify.nginx.com/) – Visually identify performance bottlenecks, overloaded servers, or potential DDoS attacks. Improve and optimize NGINX performance with intelligent advice and recommendations. Get alerts when something is wrong with the delivery of your application. Plan capacity and performance for web applications. Keep track of systems running NGINX [<sup>1</sup>](https://www.nginx.com/blog/announcing-amplify/)
* [__k6.io__](https://k6.io/) - Open source load testing tool and SaaS for engineering teams. Powerful scripting and lots of CI/CD integration.
* [__RedLine13__](https://redline13.com/) - Cloud Based Load Testing to run JMeter, Gatling, or custom code load test plans at scale using low cost instance pricing.
* [__tracetest__](https://tracetest.io) – Use OpenTelemetry for testing and synthetic monitoring. Write your tests using `YAML`

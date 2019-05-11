HTTP(S) benchmark tools, testing/debugging, & restAPI (RESTful)
---------------------------------------------------------------
*Located in alphabetical order (not prefer)*

HTTP(S) Benchmark Tools
=======================
* [__ab__](http://en.wikipedia.org/wiki/ApacheBench) – slow and single threaded, written in `C`
* [__apib__](https://github.com/apigee/apib) – most of the features of ApacheBench (`ab`), also designed as a [more modern replacement](https://github.com/apigee/apib#design), written in `C`
* [__baloo__](https://github.com/h2non/baloo) – Expressive end-to-end HTTP API testing made easy, written in Go (`golang`)
* [__baton__](https://github.com/americanexpress/baton) – HTTP load testing, written in Go (`golang`)
* [__bombardier__](https://github.com/codesenberg/bombardier) – Fast crossplatform HTTP benchmarking tool, written in Go (`golang`)
* [__curl-loader__](http://curl-loader.sourceforge.net/) – performance loading of various application services and traffic generation, written in `C`
* [__drill__](https://github.com/fcsonline/drill) – Drill is a HTTP load testing application inspired by Ansible syntax, written in `Rust`
* [__fasthttploader__](https://github.com/hagen1778/fasthttploader) – benchmark (kinda ab) with autoadjustment and charts based on fasthttp library, written in Go (`golang`)
* [__fbender__](https://github.com/facebookincubator/fbender) – A load-testing command line tool for generic network protocols (`HTTP`, `DNS`, `DHCP`, …), written in Go (`golang`)
* [__finshir__](https://github.com/Gymmasssorla/finshir) – A coroutines-driven Low & Slow traffic sender, written in `Rust`
* [__fortio__](https://github.com/istio/fortio) – load testing library and command line tool and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats, written in Go (`golang`)
* [__gatling__](http://gatling.io) – High performance load testing framework based on Scala, Akka and Netty, written in `Scala`
* [__go-wrk__](https://github.com/tsliwowicz/go-wrk) – a HTTP benchmarking tool based in spirit on the excellent wrk tool ([`wg/wrk`](https://github.com/wg/wrk)), written in Go (`golang`)
* [__goad__](https://github.com/gophergala2016/goad) – Goad is an AWS Lambda powered, highly distributed, load testing tool, written in Go (`golang`)
* [__gobench__](https://github.com/cmpxchg16/gobench) – HTTP/HTTPS load testing and benchmarking tool, written in Go (`golang`)
* [__gohttpbench__](https://github.com/parkghost/gohttpbench) – `ab`-like benchmark tool run on multi-core cpu, written in Go (`golang`)
* [__goloris__](https://github.com/valyala/goloris) – Slowloris for NGINX DoS attack, written in Go (`golang`)
* [__hey__](https://github.com/rakyll/hey) – HTTP(S) load generator, ApacheBench (`ab`) replacement, formerly known as [__rakyll/boom__](https://github.com/rakyll/boom), written in Go (`golang`)
* [__htstress__](https://github.com/arut/htstress) – multithreading high-load bechmarking services (>5K rps), written in `C`/`Linux`
* [__httperf__](https://github.com/httperf/httperf) – difficult configuration, slow and single threaded, written in `C`
* [__inundator__](https://github.com/opsengine/inundator) – A simple and high-throughput HTTP flood program, written in `C`/`Linux`
* [__jmeter__](http://jmeter.apache.org/) – Apache  JMeter™, pure application designed to load test performance both on static and dynamic resources, written in `Java`
* [__k6__](https://github.com/loadimpact/k6) - A modern load testing tool scriptable in ES6 JS with support for HTTP/1.1, HTTP/2.0 and WebSocket, written in Go (`golang`)
* [__locust__](https://locust.io/) – easy-to-use, distributed load testing tool with real-time web UI. Simulates a swarm of concurrent users, the behavior of each of them is defined by your python code. Written in `Python`
* [__lor-axe__](https://github.com/ajmwagar/lor-axe) – A multi-threaded, low-bandwidth HTTP Slowloris DoS tool that handles connections and sockets in parallel, written in `Rust`
* [__mgun__](https://github.com/byorty/mgun) – A modern tool for load testing HTTP servers, written in Go (`golang`)
* [__pounce__](https://github.com/X4/pounce) – evented, but results fluctuate, it's sometimes faster than `htstress`, written in `C`
* [__siege__](http://www.joedog.org/siege-home/) – slow and single threaded, written in `C`
* [__slapper__](https://github.com/ikruglov/slapper) – Simple load testing tool with real-time updated histogram of request timings, written in Go (`golang`)
* [__slow_cooker__](https://github.com/BuoyantIO/slow_cooker) – A load tester focused on lifecycle issues and long-running tests, service with a predictable load and concurrency level for a long period of time, written in Go (`golang`)
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
* [__curl__](https://github.com/curl/curl) – Powerful features command-line tool for transferring data specified with URL syntax, written in `C`
  - [Online curl command line builde](https://curlbuilder.com/)
* [__curlconverter__](https://github.com/NickCarneiro/curlconverter) – convert curl commands to python, javascript, php
* [__httpie__](https://github.com/jkbrzt/httpie) – client, user-friendly curl replacement with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, written in `Python`
  * [__curlie__](https://curlie.io) – If you like the interface of [HTTPie](https://httpie.org) but miss the features of [curl](https://curl.haxx.se), curlie is what you are searching for. Curlie is a drop-in replacement for `httpie` that use `curl` to perform operations, written in Go (`golang`)
* [__jaggr__](https://github.com/rs/jaggr) – JSON Aggregation CLI, Jaggr can be used to integrate [vegeta](https://github.com/tsenart/vegeta) with [jplot](https://github.com/rs/jplot), written in Go (`golang`)
* [__jq__](https://github.com/stedolan/jq) – is a lightweight and flexible command-line JSON processor, written in `C`
* [__httpstat__](https://github.com/davecheney/httpstat) - It's like curl -v, with colours

SaaS/PaaS
=========
* [__BlazeMeter__](https://blazemeter.com/) – offers a cross-enterprise test automation framework for the entire technical team (developers, devops, ops and QA) throughout the product development lifecycle. Run continuous or ‘on demand’ testing for APIs, mobile apps and websites. Run from the cloud, on-premise or as a hybrid solution. Use with JMeter &amp; Selenium WebDriver &amp; integrate with your existing CI, CD &amp; APM tools.
* [__NewRelic__](http://newrelic.com/) – software analytics tool suite used by developers, ops, and software companies to understand how your applications are performing in development and production
* [__NGINX Amplify__](https://amplify.nginx.com/) – Visually identify performance bottlenecks, overloaded servers, or potential DDoS attacks. Improve and optimize NGINX performance with intelligent advice and recommendations. Get alerts when something is wrong with the delivery of your application. Plan capacity and performance for web applications. Keep track of systems running NGINX [<sup>1</sup>](https://www.nginx.com/blog/announcing-amplify/)


Links
=====
- [Multi-Mechanize | Performance Test Framework](http://testutils.org/multi-mechanize/)
- [Performance test tools list](http://www.opensourcetesting.org/performance.php)
- [REST API client](https://insomnia.rest/) - simple, beautiful, and free REST API client (`Mac`, `Windows`, and `Linux`)

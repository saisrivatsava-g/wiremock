# wiremock

## Overview
WireMock is a library for stubbing and mocking web services. It constructs a HTTP server that we could connect to as we would to an actual web service.

When a WireMock server is in action, we can set up expectations, call the service, and then verify its behaviors.

## Maven Dependencies
In order to be able to take advantage of the WireMock library, we need to include the following dependency in the POM:
```
<dependency>
    <groupId>com.github.tomakehurst</groupId>
    <artifactId>wiremock</artifactId>
    <version>2.14.0</version>
</dependency>
```


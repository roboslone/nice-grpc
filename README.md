# nice-grpc

A gRPC library that is nice to you.

## Features

- Written in TypeScript for TypeScript.
- Modern API that uses Promises and Async Iterables for streaming.
- Easy cancellation propagation with
  [`AbortSignal`](https://developer.mozilla.org/en-US/docs/Web/API/AbortSignal).
- Client and server middleware support via concise API that uses Async
  Generators.

## Packages

- [nice-grpc](/packages/nice-grpc) — server and client library for Node.js.
- [nice-grpc-web](/packages/nice-grpc-web) — client library for the Browser.
- [nice-grpc-common](/packages/nice-grpc-common) — a package containing common
  data structures and types for `nice-grpc` and `nice-grpc-web`.
- [nice-grpc-client-middleware-deadline](/packages/nice-grpc-client-middleware-deadline)
  — client middleware that adds support for setting call deadline.
- [nice-grpc-client-middleware-retry](/packages/nice-grpc-client-middleware-retry)
  — client middleware that adds automatic retries to unary calls.
- [nice-grpc-server-middleware-terminator](/packages/nice-grpc-server-middleware-terminator)
  — server middleware that makes it possible to prevent long-running calls from
  blocking server graceful shutdown.
- [nice-grpc-server-health](/packages/nice-grpc-server-health) —
  [Health Checking Protocol](https://github.com/grpc/grpc/blob/master/doc/health-checking.md)
  implementation.
- [nice-grpc-server-reflection](/packages/nice-grpc-server-reflection) —
  [Server Reflection](https://github.com/grpc/grpc/blob/master/doc/server-reflection.md)
  support.
- [nice-grpc-error-details](/packages/nice-grpc-error-details) — experimental
  [Rich Error Model](https://grpc.io/docs/guides/error/#richer-error-model)
  support.
- [nice-grpc-opentelemetry](/packages/nice-grpc-opentelemetry) —
  [OpenTelemetry](https://opentelemetry.io/) instrumentation.
- [nice-grpc-prometheus](/packages/nice-grpc-prometheus) —
  [Prometheus](https://prometheus.io/) monitoring.

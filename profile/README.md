# Deboa Client

Deboa Client is the home of the Deboa ecosystem: a Rust-focused HTTP client platform built for modern async applications, API clients, and developer-friendly tooling.

Our projects center on Deboa, a straightforward and flexible HTTP client library for Rust, with support for multiple runtimes, protocol extensions, and ergonomic helpers for real-world API work.

## What we build

- Core HTTP client libraries for Rust
- Runtime-specific adapters for async ecosystems
- REST and resource-oriented client tooling
- Serialization, TLS, WebSocket, multipart, and HTTP/3 support
- Templates and utilities to help teams get started faster

## Core repositories

- [deboa](https://github.com/deboa-client/deboa)  
  The main Rust HTTP client library, designed to be runtime-agnostic and developer-friendly.

- [deboa-macros](https://github.com/deboa-client/deboa-macros)  
  Convenience macros that simplify request creation and response handling.

- [deboa-contrib](https://github.com/deboa-client/deboa-contrib)  
  Additional functionality and extensions for the Deboa ecosystem.

- [vamo](https://github.com/deboa-client/vamo)  
  A REST client wrapper built on top of Deboa for cleaner, DRY API access patterns.

- [vamo-macros](https://github.com/deboa-client/vamo-macros)  
  Macros for resource-oriented client generation and API definitions.

## Runtime integrations

- [deboa-tokio](https://github.com/deboa-client/deboa-tokio)  
  Tokio runtime support.

- [deboa-smol](https://github.com/deboa-client/deboa-smol)  
  Smol runtime support.

- [deboa-compio](https://github.com/deboa-client/deboa-compio)  
  Compio runtime support.

- [deboa-glommio](https://github.com/deboa-client/deboa-glommio)  
  Glommio runtime support.

## Protocol and transport extensions

- [deboa-h3](https://github.com/deboa-client/deboa-h3)  
  HTTP/3 support.

- [deboa-tls](https://github.com/deboa-client/deboa-tls)  
  TLS-related capabilities.

- [deboa-ws](https://github.com/deboa-client/deboa-ws)  
  WebSocket support.

- [deboa-multipart](https://github.com/deboa-client/deboa-multipart)  
  Multipart request support.

## Tools and templates

- [deboa-test-utils](https://github.com/deboa-client/deboa-test-utils)  
  Shared utilities for testing Deboa-based code.

- [deboa-templates](https://github.com/deboa-client/deboa-templates)  
  Templates for bootstrapping Rust applications with Deboa.

## Why Deboa Client

We focus on building practical tooling for Rust developers who need:

- High-performance HTTP clients
- Flexible async runtime support
- Clean abstractions without excessive ceremony
- Strong developer ergonomics
- Extensible APIs for real-world services

## Getting started

For the core library:

```toml
deboa = "0.1"

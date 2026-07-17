<p align="center">
  <a href="https://github.com/your-org/fastcoap">
    <img src="https://github.com/user-attachments/assets/2448451a-9625-4f02-885f-45b0c8d1505d" alt="FastCOAP">
  </a>
</p>

<p align="center">
    <em>FastCOAP — a modern, high-performance Python framework for building CoAP applications and APIs.</em>
</p>

<p align="center">
<a href="https://github.com/your-org/fastcoap/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/darixsamani/fastcoap/tests.yml?label=tests" alt="Tests">
</a>
<a href="https://pypi.org/project/fastcoap">
    <img src="https://img.shields.io/pypi/v/fastcoap?color=%23009688&label=PyPI" alt="PyPI Version">
</a>
<a href="https://pypi.org/project/fastcoap">
    <img src="https://img.shields.io/pypi/pyversions/fastcoap?color=%23009688" alt="Python Versions">
</a>
<a href="LICENSE">
    <img src="https://img.shields.io/github/license/darixsamani/fastcoap" alt="License">
</a>
</p>

---

## Documentation

Coming soon...

## Source Code

https://github.com/darixsamani/fastcoap

---

**FastCOAP** is a modern, fast (high-performance) Python framework for building **CoAP (Constrained Application Protocol)** applications based on standard Python type hints.

Inspired by **FastAPI**, FastCOAP brings the same developer experience to the Internet of Things, making it easy to build scalable, maintainable, and production-ready CoAP services.

## Key Features

- ⚡ **Fast** — High-performance asynchronous framework built for CoAP communication.
- 🌐 **IoT-first** — Designed specifically for connected devices, edge computing, and constrained networks.
- 📡 **Native CoAP** — Full support for the Constrained Application Protocol.
- 🧩 **Simple & Intuitive** — Clean API inspired by FastAPI, with minimal boilerplate.
- 🚀 **Developer Friendly** — Modern Python features, type hints, dependency injection, and automatic validation.
- 📦 **Production Ready** — Modular architecture suitable for embedded systems, gateways, and cloud IoT platforms.
- 🔒 **Reliable** — Built with robustness, scalability, and maintainability in mind.
- 🐍 **Pythonic** — Leverages standard Python type annotations for an excellent developer experience.

## Why FastCOAP?

Building CoAP applications shouldn't feel different from building modern HTTP APIs.

FastCOAP provides an elegant programming model inspired by FastAPI while embracing the CoAP ecosystem. Whether you're developing applications for IoT devices, smart homes, industrial automation, or sensor networks, FastCOAP helps you write less code and ship faster.


## Dependencies

| Package | Purpose |
|---|---|
| `aiocoap` | Async CoAP server and client |
| `pydantic >= 2.0` | Request body validation and serialisation |
| `cbor2` | CBOR encoding / decoding |
| `typer` | CLI (`fastcoap run`, `fastcoap routes`) |
| `rich` | Pretty terminal output |
| `anyio` | Async primitives |
| `watchfiles` | `--reload` file watcher |

---




# gilfoyle [![godoc](https://godoc.org/github.com/dreamvo/gilfoyle?status.svg)](https://godoc.org/github.com/dreamvo/gilfoyle) [![build](https://img.shields.io/endpoint.svg?url=https://actions-badge.atrox.dev/dreamvo/gilfoyle/badge?ref=master)](https://github.com/dreamvo/gilfoyle/actions) [![goreport](https://goreportcard.com/badge/github.com/dreamvo/gilfoyle)](https://goreportcard.com/report/github.com/dreamvo/gilfoyle) [![Coverage Status](https://coveralls.io/repos/github/dreamvo/gilfoyle/badge.svg?branch=master)](https://coveralls.io/github/dreamvo/gilfoyle?branch=master) [![release](https://img.shields.io/github/release/dreamvo/gilfoyle.svg)](https://github.com/dreamvo/gilfoyle/releases)

Gilfoyle is a web application from the [Dreamvo project](https://dreamvo.com) that runs a self-hosted video streaming server. This application allows you to setup an enterprise-grade media encoding & streaming platform in minutes. Gilfoyle handles media upload, processing and streaming.

It's written in Golang, designed for [Kubernetes](http://kubernetes.io/) and runs as a single Linux binary with [PostgreSQL](https://www.postgresql.org/) and [RabbitMQ](https://www.rabbitmq.com/).

## Table of content

- [Features](#features)
- [Current status](#current-status)
- [Design](#design)
- [Roadmap](#roadmap)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Discussion](#discussion)

## Features

- Deploy a RESTful API and HLS server to manage and stream audio & video
- Handle media compression and encoding with [FFmpeg](https://ffmpeg.org/)
- Customize media renditions
- Monitoring: Prometheus exported metrics, embedded Web UI
- Media attachments: attach files such as captions or images to medias
- Enjoy highly scalable & cloud-native architecture

### What's next ?

- Media asset generation (thumbnail, video preview...)
- More supported formats (e.g: *360° videos, 60fps*...)
- Multi stream support (e.g: one audio stream per language)
- Authentication and delegated upload
- Live streaming
- [IPFS](https://ipfs.io/) support
- Encryption support

## Current status

It's a **Work In Progress**. As this project is very recent, it's under heavy development and not suitable for production yet. Please consider v0 as unstable. Want to contribute ? Check the [backlog](https://github.com/dreamvo/gilfoyle/projects/1).

## Design

See [this document](DESIGN.md) for a high level design and goals.

## Roadmap

### Phase 1 *(v0.1 - current)*

This first phase aim to build a first working version of this software with a minimum of test coverage and bug fixes. The first working version is v0.1.0 whose roadmap is [available here](https://github.com/dreamvo/gilfoyle/issues/40).

### Phase 2 *(v0.x)*

This second phase is about getting more contributors, feedbacks, bug fixes and more tests. Feedbacks and tests should make us able to create a roadmap for the first stable release (v1).

### Phase 3 (v1)

This third phase should allow us to make the program more stable and welcoming to new users. Stability will make us able to launch donation goals in order to continue improve the OSS project and build a SaaS product.

## Documentation

- For **contributors**: see [godoc](https://godoc.org/github.com/dreamvo/gilfoyle), [high-level design documentation](DESIGN.md)
- For **users**: see [user guide](https://dreamvo.github.io/gilfoyle/) (WIP) and [API documentation](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/dreamvo/gilfoyle/master/api/docs/swagger.json)
- The [GPL v3](LICENSE) license

## Contributing

This project is in an early stage. We appreciate feedbacks and [discussions](#discussion) about the design and [features](#features).

## Discussion

- [Discuss on GitHub](https://github.com/dreamvo/gilfoyle/discussions)
- [Report a bug](https://github.com/dreamvo/gilfoyle/issues/new)
- Follow us on [Twitter](https://twitter.com/dreamvoapp)
- Contact us at [contact@dreamvo.com](mailto:contact@dreamvo.com)

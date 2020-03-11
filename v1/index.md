---
layout: default
title: Filesystem abstraction for PHP
permalink: /v1/docs/
redirect_from:
    - /
    - /docs/
---

[![Author](https://img.shields.io/badge/author-@frankdejonge-blue.svg)](https://twitter.com/frankdejonge)
[![Source Code](https://img.shields.io/badge/source-thephpleague/flysystem-blue.svg)](https://github.com/thephpleague/flysystem)
[![Latest Version](https://img.shields.io/github/tag/thephpleague/flysystem.svg)](https://github.com/thephpleague/flysystem/releases)
[![Software License](https:////img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/thephpleague/flysystem/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/thephpleague/flysystem.svg?branch=v1.0)](https://travis-ci.org/thephpleague/flysystem)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/thephpleague/flysystem.svg)](https://scrutinizer-ci.com/g/thephpleague/flysystem/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/thephpleague/flysystem.svg)](https://scrutinizer-ci.com/g/thephpleague/flysystem)
[![Total Downloads](https://img.shields.io/packagist/dt/league/flysystem.svg)](https://packagist.org/packages/league/flysystem)
![php 5.5.9+](https://img.shields.io/badge/php-min%205.5.9-red.svg)

## About Flysystem

Flysystem is a filesystem abstraction library for PHP. By providing a unified interface
for many different filesystems you're able to swap out filesystems without application wide
rewrites.

Using Flysystem can eliminate vendor-lock in, reduce technical debt, and improve the testability
of your code.

## Getting Started

* **[Architecture](/v1/docs/architecture/)**: Flysystem's internal architecture
* **[Setup/Bootstrap](/v1/docs/usage/setup/)**: Load Flysystem and set up your first adapter
* **[Flysystem API](/v1/docs/usage/filesystem-api/)**: How to interact with your Flysystem instance

### Commonly-Used Adapters

* **[AWS S3](/v1/docs/adapter/aws-s3-v2/)**
* **[Azure](/v1/docs/adapter/azure/)**
* **[DigitalOcean Spaces](/v1/docs/adapter/digitalocean-spaces/)**
* **[Local](/v1/docs/adapter/local/)**
* **[Memory](/v1/docs/adapter/memory/)**
* **[Creating An Adapter](/v1/docs/advanced/creating-an-adapter/)**
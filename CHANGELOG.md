# Changelog

## 0.3.1 (2016-01-25)

* Fix CORS and auth token headers for `/_api/spec/swagger.json` resource
* Fix `allow_origin` handling for non-browser clients
* Ensure base path is prefixed with a forward slash
* Filter stderr from all responses
* Set Tornado logging level and Jupyter logging level together with `--log-level`

## 0.3.0 (2016-01-15)

* Support setting of status and headers in notebook-http mode
* Support automatic, minimal Swagger doc generation in notebook-http mode
* Support download of a notebook in notebook-http mode
* Support CORS and token auth in notebook-http mode
* Expose HTTP request headers in notebook-http mode
* Support multipart form encoding in notebook-http mode
* Fix request value JSON encoding when passing requests to kernels
* Fix kernel name handling when pre-spawning
* Fix lack of access logs in notebook-http mode

## 0.2.0 (2015-12-15)

* Support notebook-defined HTTP APIs on a pool of kernels
* Disable kernel instance list by default

## 0.1.0 (2015-11-18)

* Support Jupyter Notebook kernel CRUD APIs and Jupyter kernel protocol over Websockets
* Support shared token auth
* Support CORS headers
* Support base URL
* Support seeding kernels code from a notebook at a file path or URL
* Support default kernel, kernel pre-spawning, and kernel count limit
* First PyPI release

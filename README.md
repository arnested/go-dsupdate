# DS Update in Go

[![Maintainability](https://api.codeclimate.com/v1/badges/e7ce795acaeb8b2a5b61/maintainability)](https://codeclimate.com/github/arnested/go-dsupdate/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/e7ce795acaeb8b2a5b61/test_coverage)](https://codeclimate.com/github/arnested/go-dsupdate/test_coverage)
[![Build Status](https://travis-ci.com/arnested/go-dsupdate.svg?branch=master)](https://travis-ci.com/arnested/go-dsupdate)
[![Release](https://img.shields.io/github/release/arnested/go-dsupdate.svg)](https://github.com/arnested/go-dsupdate/releases/latest)
[![Go Report Card](https://goreportcard.com/badge/arnested.dk/go/dsupdate/)](https://goreportcard.com/report/arnested.dk/go/dsupdate)
[![CLA assistant](https://cla-assistant.io/readme/badge/arnested/go-dsupdate)](https://cla-assistant.io/arnested/go-dsupdate)
[![GoDoc](https://godoc.org/arnested.dk/go/dsupdate?status.svg)](https://godoc.org/arnested.dk/go/dsupdate)

Package dsupdate is a library for updating DS records with DK Hostmasters
proprietary DS Update protocol
(https://github.com/DK-Hostmaster/dsu-service-specification).

It is work in progress and not in a functional state (it doesn't even try to
update anything yet).

Besides eventually solving a use case for me the purpose of this project is also
me getting more familiar with Go, train TDD (which I've always postponed) and
try out some new techniques inspired by among others:

- Functional options for friendly APIs by Dave Cheney
(https://dave.cheney.net/2014/10/17/functional-options-for-friendly-apis)

- Vanity Go Import Paths by Andrew Brampton
(https://blog.bramp.net/post/2017/10/02/vanity-go-import-paths/)

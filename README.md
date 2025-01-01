# About

Contains a Go implementation of Tic-Tac-Toe (aka "XOXO"), written for the
Nakama game server. Includes pure Go implementations of a Tic-Tac-Toe Nakama
module, end-to-end unit tests for the Nakama module, and a Ebitengine client
that works with the Nakama module.

[![Tests](https://github.com/ascii8/xoxo-go/workflows/Test/badge.svg)](https://github.com/ascii8/xoxo-go/actions?query=workflow%3ATest)
[![Go Report Card](https://goreportcard.com/badge/github.com/ascii8/xoxo-go)](https://goreportcard.com/report/github.com/ascii8/xoxo-go)
[![Reference](https://pkg.go.dev/badge/github.com/ascii8/xoxo-go.svg )](https://pkg.go.dev/github.com/ascii8/xoxo-go)

## Overview

An overview of the primary directories in this repository:

* [xoxo](/xoxo) - Tic-Tac-Toe game logic and client in Go
* [nkxoxo](/nkxoxo) - a Tic-Tac-Toe Nakama module
* [ebxoxo](/ebxoxo) - a Ebitengine game client for Tic-Tac-Toe
* [fynexoxo](/fynexoxo) - a Fyne UI game client for Tic-Tac-Toe
* [gioxoxo](/gioxoxo) - a Gio UI game client for Tic-Tac-Toe

#### Command/Module entry points

* [cmd/nkxoxo](/cmd/nkxoxo) - the Nakama server module entry point
* [cmd/nkclient](/cmd/nkclient) - the testing client
* [cmd/ebclient](/cmd/ebclient) - the Ebitengine client entry point
* [cmd/fyneclient](/cmd/fyneclient) - the Fyne UI client entry point
* [cmd/gioclient](/cmd/gioclient) - the Gio UI client entry point

## Related Links

* [github.com/ascii8/nakama-go](https://github.com/ascii8/nakama-go) - a Nakama client for Go, with realtime WebSocket and WASM support
* [github.com/ascii8/nktest](https://github.com/ascii8/nktest) - a Nakama module testing package for Go
* [github.com/defold/game-xoxo-nakama-client](https://github.com/defold/game-xoxo-nakama-client.git) - a Nakama Tic-Tac-Toe client made with Defold
* [github.com/defold/game-xoxo-nakama-server](https://github.com/defold/game-xoxo-nakama-server.git) - a Nakama Tic-Tac-Toe server (Lua)

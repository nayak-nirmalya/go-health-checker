## HealthChecker

A tiny tool that checks wheather a website is running or is down.

Credits: [Akhil Sharma](https://github.com/AkhilSharma90)

## Installation

> This project needs to Go (At least 1.13) to compile.

**Get the Repo.**

```bash
go get github.com/nayak-nirmalya/go-health-checker
```

<div align="center">OR</div>
<br>

```bash
git clone github.com/nayak-nirmalya/go-health-checker
```

**Run Project.**

```bash
go run . --domain google.com
```

<div align="center">OR</div>
<br>

```bash
go build && ./go-health-checker --domain google.com
```

## Usage

```
NAME:
   HealthChecker - A tiny tool that checks wheather a website is running or is down.

USAGE:
   go-health-checker [global options] command [command options] [arguments...]

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --domain value, -d value  Domain name to check.
   --port value, -p value    Port number to check.
   --help, -h                show help (default: false)
```

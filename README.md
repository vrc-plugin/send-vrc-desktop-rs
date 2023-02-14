# send_vrc_desktop

[send_vrc_desktop](https://github.com/bootjp/send_vrc_desktop) written in Rust.

## Installation

```sh
cargo install --git https://github.com/vrc-plugin/send_vrc_desktop
```

## Usage

### PowerShell

```ps1
Invoke-WebRequest -Method POST -ContentType application/json -Body '{ "url": "https://www.youtube.com/watch?v=c-ZWPYJYiAg"}' http://localhost:11400/url
```

### curl

```sh
curl -X POST -H 'Content-Type: application/json' -d '{ "url": "https://www.youtube.com/watch?v=c-ZWPYJYiAg" }' http://localhost:11400/url
```

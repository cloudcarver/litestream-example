# litestream-demo

A self-hosted [litestream](https://github.com/benbjohnson/litestream) docker daemon example

### Prerequiste
Docker

### Quick start
1. create an s3 bucket following the [guide](https://litestream.io/guides/s3/) 

2. create a `litestream.yml` file and persistent database file in `./data`
    ```bash
    $ ./dev init
    ```

3. wirte down your aws credentials in `litestream.yml`

4. run litestream directly to validate your setup
    ```bash
    $ ./dev lite
    ```

### FAQ
Using [rootless docker](https://docs.docker.com/engine/security/rootless/)

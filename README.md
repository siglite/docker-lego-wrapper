# docker-lego-wrapper

[lego](https://github.com/go-acme/lego) using with docker.

## Feature

- Add `lego update` command
- Change default directory to `/etc/letsencrypt`

## Usage

```console
$ git clone https://github.com/siglite/docker-lego-wrapper
$ cd docker-lego-wrapper
$ ./lego
lego version v2.2.0 linux/amd64

[Commands]
    run      Register an account, then create and install a certificate
    revoke   Revoke a certificate
    renew    Renew a certificate
    dnshelp  Shows additional help for the --dns global option
    list     Display certificates and accounts information.
    help, h  Shows a list of commands or help for one command

[Additional Commands]
    update   Update docker image

[Certificates]
    No certificates found.
```

## License

MIT

## Author

Shun Ishihara <<sig@siglite.net>>

# Utilserve

Serve util files(e.g. .vimrc, .eslintrc ...)

Use [zeit/serve](https://github.com/zeit/serve) to serve, and [now](https://github.com/zeit/now-cli) as hosting.

## Usage

```
(if not installed)
$ yarn global add now

(install dependencies and then deploy)
$ yarn
$ now

(create alias)
$ now <alias|ln> your-app-default-host.now.sh alias-yours

(check)
$ now <alias|ln> ls
```

### with DNS (optional)

```
$ now <alias|ln> your-app-default-hose.now.sh alias.your.domain
```

This will print errors and how to resolve it.
Follow the guideline(e.g. Add TXT record, Add CNAME record...)

## Ref

- [Assign a Domain Name - ZEIT Documentation](https://zeit.co/docs/v1/getting-started/assign-a-domain-name#4.-using-a-custom-domain-with-a-cname)
- [Aliases and Domains - ZEIT Documentation](https://zeit.co/docs/v1/features/aliases)

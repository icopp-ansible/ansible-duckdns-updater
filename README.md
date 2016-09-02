# ansible-duckdns-updater

Install a DuckDNS updater via Homebrew. Does nothing on non-macOS platforms.

## Role Variables

`duckdns_subdomain` and `duckdns_token` will be prompted for if not supplied.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew) (included as repository dependency)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.duckdns-updater
```

```
  - hosts: all
    roles:
      - role: icopp.duckdns-updater
        duckdns_subdomain: xxxxx
        duckdns_token: xxxxx

```


## License

MIT

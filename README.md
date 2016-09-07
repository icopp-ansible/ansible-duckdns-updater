# ansible-duckdns-updater

Install a DuckDNS updater via Homebrew.

## Role Variables

`duckdns_subdomain` and `duckdns_token` must be supplied or all tasks will be skipped.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.duckdns-updater
        duckdns_subdomain: xxxxx
        duckdns_token: xxxxx
```

## License

MIT

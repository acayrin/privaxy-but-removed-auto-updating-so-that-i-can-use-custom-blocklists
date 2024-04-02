### [Barre/privaxy](https://github.com/Barre/privaxy) with removed auto blocklist updating part so that it can be used with custom blocklists

- `blocklist` includes urls of blocklist
- `exclusions` includes excluded domains
- no, the binary does not contain any backdoor nor sus images
- based on v0.4.0 with auto-update code removed

create a cronjob that runs the `fetch` script daily

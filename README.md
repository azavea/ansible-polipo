# ansible-polipo

An Ansible role for installing [Polipo](http://www.pps.univ-paris-diderot.fr/~jch/software/polipo/).

## Role Variables

- `polipo_version` - Polipo version
- `polipo_proxy_address` - The IP address where the proxy listens (default: `127.0.0.1`)
- `polipo_disable_indexing` - Flag to disable cache indexing (default: `true`)
- `polipo_disable_servers_list` - Flag to disable listing known servers (default: `true`)
- `polipo_allowed_clients` - Network from where clients are allowed to connect (default: `127.0.0.1/32`)


## Example Playbook

See the [examples](./examples/) directory.

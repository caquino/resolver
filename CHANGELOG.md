## v1.1.2:

### Bug

- [COOK-2977]: resolver cookbook has foodcritic failures

## v1.1.0:

* [COOK-1242] - collect nameservers using a server role, adds
  `from_server_role` recipe

## v1.0.2:

* 'node' went missing in the template.

## v1.0.0:

* [COOK-1089] - accept resolver options via attributes
* [COOK-1109] - return from resolver recipe if no nameserver attribute
  is set so resolv.conf doesn't get broken during the run
* [COOK-1150] - drop the empty element from the nameserver attribute array

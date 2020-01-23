## 2.1.0 (January 13, 2020)

ENHANCEMENTS
* Add support to both modules for setting custom API endpoint and ignoring SSL verification ([#23](https://github.com/ns1/ns1-ansible-modules/pull/23))

## 2.0.0 (August 05, 2019)

ENHANCEMENTS
* ns1_zone: Adds `dnssec` option
* ns1_record: Adds `record_mode` option to allow appending new answers or filters to existing values unspecified in the playbook or purging of unspecified values

IMPROVEMENTS
* Fixes support for Falsey option values
* Role now associated with dedicated `ns1` namespace in Ansible Galaxy
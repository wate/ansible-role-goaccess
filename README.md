goaccess
=================

Install goaccess

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `goaccess_maxmind_account`

MaxMindのアカウントIDとライセンスキー  
@see https://dev.maxmind.com/geoip/geolite2-free-geolocation-data

### `goaccess_maxmind_database_editions`

インストールするMaxMindのGeoIPデータベースのエディション

### `goaccess_maxmind_database_path`

GoAccessに設定するGeoIPデータベースのパス

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: goaccess
```

License
--------------

Apache License 2.0

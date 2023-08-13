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

### `goaccess_packages`

インストールするパッケージ

### `goaccess_install_geoipupdate`

geoipupdateをインストールするかどうか

### `goaccess_geoipupdate_maxmind_account_id`

MaxMindのアカウントID  
@see https://dev.maxmind.com/geoip/geolite2-free-geolocation-data

### `goaccess_geoipupdate_maxmind_license_key`

MaxMindのライセンスキー  
@see https://dev.maxmind.com/geoip/geolite2-free-geolocation-data

### `goaccess_geoipupdate_edition_ids`

インストールするGeoIPデータベースのエディション

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

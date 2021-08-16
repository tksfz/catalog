# phpldapadmin

![Version: 1.3.0](https://img.shields.io/badge/Version-1.3.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: auto](https://img.shields.io/badge/AppVersion-auto-informational?style=flat-square)

Web-based LDAP browser to manage your LDAP server

**Homepage:** <https://github.com/truecharts/apps/tree/master/charts/stable/phpldapadmin>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| TrueCharts | info@truecharts.org | truecharts.org |
| Ornias1993 | kjeld@schouten-lebbing.nl | truecharts.org |

## Source Code

* <https://gitlab.v2.rancher.geohub.space/g3s/i3s/i3s-helm-catalog>

## Requirements

Kubernetes: `>=1.16.0-0`

| Repository | Name | Version |
|------------|------|---------|
| https://truecharts.org/ | common | 6.8.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| env.PHPLDAPADMIN_HTTPS | string | `"false"` |  |
| env.PHPLDAPADMIN_TRUST_PROXY_SSL | string | `"true"` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"osixia/phpldapadmin"` |  |
| image.tag | string | `"0.9.0"` |  |
| service.main.enabled | bool | `true` |  |
| service.main.ports.main.port | int | `80` |  |
| strategy.type | string | `"Recreate"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)
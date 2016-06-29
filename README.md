Role Name
=========

...

Requirements
------------

...

Role Variables
--------------

| Variable Name             | Description              | Default                      |
| ------------------------- | ------------------------ | ---------------------------- |
| `httpd_php_conf_copy`     | Enable proxy to php-fpm? | `true`                       |
| `httpd_php_conf_dest`     | Config file location     | `/etc/httpd/conf.d/php.conf` |
| `httpd_php_conf_owner`    |  ... owner               | `root`                       |
| `httpd_php_conf_group`    |  ... group               | `root`                       |
| `httpd_php_conf_mode`     |  ... mode                | `0644`                       |
| `httpd_php_conf_seuser`   |  ... SE user             | `system_u`                   |
| `httpd_php_conf_serole`   |  ... SE role             | `object_r`                   |
| `httpd_php_conf_setype`   |  ... SE type             | `httpd_config_t`             |
| `httpd_php_conf_selevel`  |  ... SE level            | `s0`                         |
| `php_fpm_service_state`   | php-fpm service state    | `started`                    |
| `php_fpm_service_enabled` | php-fpm service enabled? | `true`                       |

Dependencies
------------

...

Example Playbook
----------------

...

    - hosts: serversthatneedphp70
      roles:
         - role: mcenirm.php70

License
-------

BSD

Author Information
------------------

...

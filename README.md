Timezone
========

Configure machine timezone


Role Variables
--------------

The only var is the timezone string and is optional 

tz_string: "Europe/Paris"


How to use 
----------
Default:

    - hosts: server
      roles:
         - role: timezone

Override default value:

    - hosts: server
      roles:
         - { role: timezone, tz_string: "Asia/Tokyo" }

License
-------

Licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


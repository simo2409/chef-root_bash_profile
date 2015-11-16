root_bash_profile Cookbook
==========================
This cookbook simply setups bash_profile for root user.

Requirements
------------
None

Attributes
----------
None

Usage
-----
#### root_bash_profile::default
Just include `root_bash_profile` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[root_bash_profile]"
  ]
}
```

Contributing
------------
Need help for testing following best practises, if you can help you are welcome!

License and Authors
-------------------
License: MIT

Authors:

Simone Dall'Angelo

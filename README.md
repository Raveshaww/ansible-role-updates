# Package Updates

A quick role meant to handle updating all APT and DNF packages on target hosts to the latest version. This doesn't necessarly need to be a role, but I was getting somewhat tired of simply repeating the same code from playbook to playbook.

# Requirements

None

# Role Variables

None

# Dependencies

None

# Example Playbook


    - hosts: servers
      roles:
         - raveshaww.updates

# License

BSD

# Author Information

This role was created in 2023 by [Austin Clark](https://github.com/Raveshaww). 

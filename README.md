# ansible-aws-inspector

This package installs the [Amazon Inspector](https://aws.amazon.com/inspector/) agent on your instance.

Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS.

# Tunables

* ```aws_inspector_download_url```(string) - The download url for the installation script
* ```aws_inspector_download_destination```(string) - The destination for the download

# Example Playbook

```
- hosts: servers
  roles:
     - role: telusdigital.aws-inspector
```

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* Alex Podobnik | [e-mail](mailto:alexandar.podobnik@gmail.com)

# destroy-lc

Destroy Launch Configuration

## Role Variables

* `lc.name`                   : Name of the launch configuration
* `lc.region`                 : Region to launch the ec2 instance to create the new AMI

## Example playbook

```yaml
- hosts: all
  roles:
    - destroy-lc
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)

## selenium [![Build Status](https://travis-ci.org/ThePixelDeveloper/ansible-selenium.svg?branch=master)](https://travis-ci.org/ThePixelDeveloper/ansible-selenium)

Set up selenium in Debian-like systems.

#### Requirements

* `java`

#### Variables

* `selenium_install_dir`: [default: `/opt`] Install directory
* `selenium_version`: [default: `2.44.0`] Install version

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - selenium
```

#### License

MIT

#### Author Information

Mathew Davies

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ThePixelDeveloper/ansible-selenium/issues)!

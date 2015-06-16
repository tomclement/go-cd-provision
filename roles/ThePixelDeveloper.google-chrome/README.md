## google-chrome [![Build Status](https://travis-ci.org/ThePixelDeveloper/ansible-google-chrome.svg?branch=master)](https://travis-ci.org/ThePixelDeveloper/ansible-google-chrome)

Set up google chrome in Debian-like systems.

#### Requirements

None

#### Variables

* `google_chrome_arch`: [default: `amd64`]: Architecture of target system.

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - google-chrome
```

#### License

MIT

#### Author Information

Mathew Davies

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ThePixelDeveloper/ansible-google-chrome/issues)!

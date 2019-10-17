# home-assistant-config-orb [![CircleCI status](https://circleci.com/gh/DallasO/home-assistant-config-orb.svg "CircleCI status")](https://circleci.com/gh/DallasO/home-assistant-config-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/dallaso/home-assistant-config)](https://circleci.com/orbs/registry/orb/dallaso/home-assistant-config) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/DallasO/home-assistant-config-orb/master/LICENSE)
CircleCI Orb that allows you to validate your Home Assistant config

## Usage

_For full usage guidelines, see the [orb registry listing](http://circleci.com/orbs/registry/orb/dallaso/home-assistant-config)._

### Example
It's as simple as adding this `.circleci/config.yml` file to the repository you use for your configuration. CircleCI will let you use their free tier if you choose a private repository - as long as you **only make a few changes per week**.

`.circleci/config.yml`
```yaml
version: 2.1
description: |
  Basic usage of this orb
  https://circleci.com/orbs/registry/orb/dallaso/home-assistant-config

orbs:
      hass: dallaso/home-assistant-config@0.0

workflows:
  main:
    jobs:
      - hass/check-config
```

**[See more examples and information in the Orb Registry](https://circleci.com/orbs/registry/orb/dallaso/home-assistant-config)**

## Contributing

We welcome [issues](https://github.com/DallasO/home-assistant-config-orb/issues) to and [pull requests](https://github.com/DallasO/home-assistant-config-orb/pulls) against this repository!

## Additional Resources
[CircleCI Orbs](https://circleci.com/docs/2.0/orb-intro/#section=configuration)  
[Home Assistant](https://www.home-assistant.io/)  
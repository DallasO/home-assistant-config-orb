# home-assistant-config-orb
CircleCI Orb that allows you to validate your Home Assistant config

## How to use
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

## Additional Resources
[CircleCI Orbs](https://circleci.com/docs/2.0/orb-intro/#section=configuration)  
[Home Assistant](https://www.home-assistant.io/)  

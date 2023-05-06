[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)

Temporary HACS integration for PG&E via Opower until https://github.com/home-assistant/core/pull/90489 is merged and released to core.
For documentation see https://github.com/home-assistant/home-assistant.io/pull/26793 or better the generated page at
https://deploy-preview-26793--home-assistant-docs.netlify.app/integrations/opower

# Installation

## HACS
1. [Add](http://homeassistant.local:8123/hacs/integrations) custom integrations repository: https://github.com/tronikos/opower-hacs
2. Select "Opower" in the Integration tab and click download
3. Restart Home Assistant
4. Enable the integration

## Manual
1. Copy directory `custom_components/opower` to your `<config dir>/custom_components` directory
2. Restart Home-Assistant
3. Enable the integration

## Enable the integration
1. Go to [Settings / Devices & Services / Integrations](http://homeassistant.local:8123/config/integrations). Click **+ ADD INTEGRATION**
2. Search for "Opower" and click on it
3. Restart Home Assistant


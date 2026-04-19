# Aircon (aircon)
A curated index of APIs, data sources, and developer resources related to air conditioning, HVAC (Heating, Ventilation, and Air Conditioning), and climate control systems. This topic collection covers smart thermostat APIs, building automation protocols, IoT climate APIs, and environmental data APIs used in residential, commercial, and industrial HVAC applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Air Conditioning, HVAC, Climate Control, IoT, Smart Home, Thermostat, Building Automation, Energy Management

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Google Nest Device Access API
The Nest Device Access API (Google Smart Device Management API) provides programmatic control over Nest thermostats, cameras, and doorbells. Supports reading thermostat state, setting target temperatures, switching HVAC modes, and managing heating/cooling schedules.

**Human URL:** [https://developers.home.google.com/nest/device-access](https://developers.home.google.com/nest/device-access)

#### Tags:

 - Thermostat, Smart Home, HVAC, Google, Nest

#### Properties

- [Documentation](https://developers.home.google.com/nest/device-access)
- [APIReference](https://developers.home.google.com/nest/device-access/api)
- [Discovery](https://smartdevicemanagement.googleapis.com/v1/$discovery/rest)

### Ecobee API
The Ecobee API provides access to ecobee smart thermostats for reading and writing thermostat data, managing schedules, reading sensor data, and implementing custom home automation. Supports OAuth2 authentication and provides access to thermostat runtime data, alerts, and equipment status.

**Human URL:** [https://www.ecobee.com/home/developer/api/introduction/index.shtml](https://www.ecobee.com/home/developer/api/introduction/index.shtml)

#### Tags:

 - Thermostat, Smart Home, HVAC, Energy Management

#### Properties

- [Documentation](https://www.ecobee.com/home/developer/api/introduction/index.shtml)
- [APIReference](https://www.ecobee.com/home/developer/api/introduction/index.shtml)

### Resideo (Honeywell Home) API
The Resideo API (formerly Honeywell Home API) provides access to Honeywell and Resideo smart thermostats and home security systems. Supports reading and controlling thermostat setpoints, modes, schedules, and fan operation. Uses OAuth2 and API key authentication.

**Human URL:** [https://developer.resideo.com](https://developer.resideo.com)

#### Tags:

 - Thermostat, Smart Home, HVAC, Honeywell

#### Properties

- [Documentation](https://developer.resideo.com)
- [APIReference](https://developer.resideo.com/docs)

### Sensibo API
The Sensibo API provides control over Sensibo Sky and Air devices that add smart functionality to existing mini-split and window AC units. Supports reading AC state, setting temperature and mode, scheduling, and accessing historical usage data.

**Human URL:** [https://sensibo.github.io](https://sensibo.github.io)

#### Tags:

 - Air Conditioning, Smart Home, IoT, Energy Management

#### Properties

- [Documentation](https://sensibo.github.io)
- [APIReference](https://sensibo.github.io)

### OpenWeatherMap API
OpenWeatherMap provides weather data APIs used in HVAC automation to adapt cooling/heating based on outdoor conditions. Offers current weather, forecasts, historical data, and air quality data relevant to climate control decisions.

**Human URL:** [https://openweathermap.org/api](https://openweathermap.org/api)

#### Tags:

 - Weather, Climate, Environmental Data, IoT

#### Properties

- [Documentation](https://openweathermap.org/api)
- [APIReference](https://openweathermap.org/current)

### Home Assistant REST API
The Home Assistant REST API provides access to all home automation entities including climate/HVAC entities. Supports reading thermostat state, setting temperature, changing HVAC mode, and triggering automations for air conditioning control.

**Human URL:** [https://developers.home-assistant.io/docs/api/rest/](https://developers.home-assistant.io/docs/api/rest/)

#### Tags:

 - Smart Home, HVAC, IoT, Open Source, Automation

#### Properties

- [Documentation](https://developers.home-assistant.io/docs/api/rest/)
- [APIReference](https://developers.home-assistant.io/docs/api/rest/)

## Features

| Name | Description |
|------|-------------|
| Thermostat Control | APIs for reading and setting thermostat temperature, mode, and schedule. |
| HVAC Mode Management | Switch between heating, cooling, auto, and fan-only modes programmatically. |
| Schedule Automation | Create and manage time-based HVAC schedules and programs. |
| Sensor Data Access | Read temperature, humidity, and occupancy sensor data from smart thermostats. |
| Energy Monitoring | Track HVAC runtime, energy consumption, and efficiency metrics. |
| Weather Integration | Combine outdoor weather data with HVAC control for predictive conditioning. |
| Smart Home Integration | Integrate HVAC control with broader smart home platforms (Google Home, Apple HomeKit, SmartThings). |

## Use Cases

| Name | Description |
|------|-------------|
| Smart Home Automation | Automate AC/heating based on occupancy, time, and weather conditions. |
| Energy Optimization | Reduce energy costs by dynamically adjusting HVAC based on occupancy and utility pricing. |
| Building Management | Commercial HVAC monitoring and control across multiple zones and buildings. |
| Comfort Monitoring | Track and maintain optimal temperature and humidity levels. |
| Remote Control | Control air conditioning remotely via mobile apps and API integrations. |
| Predictive Conditioning | Pre-cool or pre-heat based on weather forecasts and schedules. |

## Integrations

| Name | Description |
|------|-------------|
| Google Home | Integration with Google Home and Google Assistant for voice control. |
| Apple HomeKit | Integration with Apple HomeKit for iOS smart home control. |
| Amazon Alexa | Voice control via Amazon Alexa smart home skills. |
| Home Assistant | Open-source home automation platform with broad HVAC device support. |
| IFTTT | Automation via IFTTT applets for condition-based HVAC control. |
| SmartThings | Samsung SmartThings integration for HVAC devices. |

## Artifacts

Machine-readable API specifications and data schemas.

### JSON Schema

- [Thermostat](json-schema/aircon-thermostat-schema.json)
- [HVAC Schedule](json-schema/aircon-hvac-schedule-schema.json)
- [Sensor Reading](json-schema/aircon-sensor-reading-schema.json)
- [Energy Report](json-schema/aircon-energy-report-schema.json)

### JSON Structure

- [Thermostat Structure](json-structure/aircon-thermostat-structure.json)
- [HVAC Schedule Structure](json-structure/aircon-hvac-schedule-structure.json)
- [Sensor Reading Structure](json-structure/aircon-sensor-reading-structure.json)
- [Energy Report Structure](json-structure/aircon-energy-report-structure.json)

### JSON-LD

- [Aircon Context](json-ld/aircon-context.jsonld)

### Examples

- [Thermostat Example](examples/aircon-thermostat-example.json)
- [HVAC Schedule Example](examples/aircon-hvac-schedule-example.json)
- [Sensor Reading Example](examples/aircon-sensor-reading-example.json)
- [Energy Report Example](examples/aircon-energy-report-example.json)

## Vocabulary

- [Aircon Vocabulary](vocabulary/aircon-vocabulary.yaml) — Domain vocabulary mapping 5 resources, 5 actions, and 3 personas across HVAC and climate control APIs

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

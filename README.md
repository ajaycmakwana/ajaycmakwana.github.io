# Iglu Schemas for Adobe Commerce Events

This repository contains Iglu compatible JSON schemas used to validate custom adobe commerce events.

## Directory Structure

Schemas are organized using the following folder structure:

.
└── com.company

    └── custom_event

        └── jsonschema

            └── 1-0-0.json
            

Each schema follows the pattern:
```
<vendor>/<event_name>/jsonschema/<version>.json
```
## Available JSON schema

https://github.com/adobe/commerce-events/tree/a13d7787a2b84f58c11331898a2e4231a2d093e4/examples/events/snowplow-debugger
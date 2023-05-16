# Personal notes for OpenTelemetry Open Agent Management Protocol (OpAMP) 

Open Agent Management Protocol (OpAMP) is a network protocol for remote management of large fleets of data collection Agents.

This repository contains @pavolloffay personal notes about OpAMP.

## Demo - ObservIQ bindplane

[Follow official docs](https://docs.bindplane.observiq.com/docs/getting-started)

The agent is [a custom OpenTelemetry collector build](https://github.com/observIQ/observiq-otel-collector).
It wraps OpenTelemetry collector service and restarts it on config changes.
The collector uses [opamp-go](https://github.com/open-telemetry/opamp-go) to talk to the OpAMP server.

The [OpAPM server](https://github.com/observIQ/bindplane-op) provides UI to create collector configuration.

## References

* [OpAMP projects in OpenTelemetry](https://github.com/open-telemetry?q=opamp&type=all&language=&sort=)
* [Spec](https://github.com/open-telemetry/opamp-spec/blob/main/specification.md)

# Auxiliary Services for Advanced Compute Platforms
This repo contains help charts, automation, and more to support running auxiliary services (read: not provided by Red Hat) on Advanced Compute Platforms.

The code in this repo is provided as-is, and should be used as an example only.

## Available Services
| Name | Description | Required ACP Services |
| --- | --- | --- |
| Active Directory | Run an active directory forest on an ACP, with optional 62443-like configuration | <ul><li>Virtualization</li><li>IT Automation</li><li>Network Interface Management</li><li>Declarative State Management</li></ul> |
| AMQ Broker | Install Red Hat AMQ Broker Operator on Openshift and run a very minimal version of AMQ Broker Instance | <ul><li>Declarative State Management</li></ul> |

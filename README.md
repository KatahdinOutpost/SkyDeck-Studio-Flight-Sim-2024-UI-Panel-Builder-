# SkyDeck-Studio-Flight-Sim-2024-UI-Panel-Builder-
SkyDeck Studio is a self-contained, no-code cockpit panel builder concept for Microsoft Flight Simulator 2024 addon creators.

It lets users visually assemble cockpit-style panels using switches, knobs, lamps, gauges, and prebuilt flight-sim modules, then bind those controls to simulated SimVars and LVars. The app runs entirely from a single index.html file with no build tools, no backend, and no external dependencies.

**Overview**

SkyDeck Studio is designed for creators who want to prototype MSFS cockpit panels without hand-writing layout code.

The core workflow is:
Choose a project or template
Add cockpit controls or modules
Edit layout and bindings
Preview the panel
Export generated files

The current version is a local frontend prototype. It includes sample data, local persistence, editable controls, live export generation, and a dark glass-cockpit interface.

**Features**
Single-file app: index.html
No React, JSX, npm, build tools, or external dependencies
Runs directly in a browser

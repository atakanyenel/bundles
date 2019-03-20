# MQTT

## Overview

The `mqtt` bundle is a simple bundle which contains a ConfigMap and a Deployment. It deploy an mqtt app that sends events to kyma.

## Details

The bundle contains the following plans:
- Minimal, a plan which is not bindable and contains only necessary parameters.
- Full, which contains all possible parameters.

Binding returns one value with the ConfigMap name.

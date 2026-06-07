# Camunda IBM Exception To Change Risk Map

Exception-to-change risk map for Camunda incidents and IBM change-window exposure.

![ci](https://github.com/mizcausevic-dev/camunda-ibm-exception-to-change-risk-map/actions/workflows/ci.yml/badge.svg)

## Why this exists

This is a Kinetic Gain signal surface for Camunda, IBM. It turns fragmented operational facts into board-ready questions:

- Where are we exposed?
- Where can we save money?
- Where should we invest?
- What story do we tell with evidence?

## Signal lanes

- process timer drift
- batch handoff risk
- exception queues
- change-window exposure
- automation ROI
- SLA causality

## Stack signal

- Primary language signal: Java
- Vertical: Platform Engineering / AI Platform
- Portfolio family: Camunda + IBM
- Live surface: https://mizcausevic-dev.github.io/camunda-ibm-exception-to-change-risk-map/

## Local verification

~~~bash
npm test
~~~

The validation script checks the generated evidence payload and confirms the static board surface exists.

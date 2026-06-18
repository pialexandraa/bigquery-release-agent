## BigQuery Release Monitor
A lightweight, local proxy utility designed to intercept and structure the Google BigQuery release notes feed. As part of a course/competition from Kaggel and Google, this agent is a blend of machine generated code + a human-in-the-middle approach. Some of the code portions have been refined by me, as for example the dynamic port allocation for preview, the CI pipeline, and others.

Primarily, this tool uses AI-generated workflows + agent creation, and newly-launched and updated Google tools: such as Antigravity tools and technologies, including the CLI, IDE, and others.

## Overview
This project was built using an AI-augmented development workflow. Moving beyond basic "vibe coding," the application utilizes an AI-assisted foundation that was manually modified and strictly architected to ensure complete system control, resilience, and reliability.

### Core traits, architecture, and modifications:
* Man-in-the-Middle Strategy: Acts as a local interceptor, pulling the official unstructured XML/HTML feed and parsing it via regex into clean, machine-readable JSON.

* Dynamic Port Allocation: The core Flask server logic was manually rewritten to proactively scan for and bind to an available ephemeral port, permanently resolving local environment conflicts.

* Automated CI/CD & Testing: Fully integrated with GitHub Actions. The continuous integration pipeline automatically handles testing, building, and generating visual documentation for every release.

* Smart Caching: Employs a 10-minute in-memory cache to reduce external API load, bypass rate limits, and maintain system sovereignty.

## Preview
An open-source experiment in AI-assisted development and local system infrastructure.
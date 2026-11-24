# Backstage - Plugin Guide

## Overview
Developer portal platform built with TypeScript.

## Plugin Architecture
| Layer | Description |
|-------|-------------|
| Frontend | React plugins |
| Backend | Express services |
| Catalog | Entity discovery |
| Scaffolder | Project templates |

## Creating a Plugin
`bash
yarn backstage-cli create-plugin --name my-plugin
`

## Configuration
| File | Purpose |
|------|--------|
| app-config.yaml | App settings |
| catalog-info.yaml | Entity metadata |
| plugin/src/index.ts | Plugin entry |

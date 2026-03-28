# Project Context — cowork-social-automation

## Purpose
Social Content Automation Cowork Plugin for Claude Cowork. Packages domain-specific skills, commands, and an autonomous agent into a single installable plugin.

## Architecture
- **Skills (4):** post-generator, content-calendar, multilingual-adapter, performance-review
- **Commands (4):** /social:generate, /social:calendar, /social:translate, /social:report
- **Agent:** weekly-social-batch

## Design Decisions
- Skills contain the domain knowledge and step-by-step instructions
- Commands are lightweight entry points that invoke the right skill
- The agent chains multiple skills into an autonomous workflow
- MCP connectors declared in .mcp.json (user configures credentials)

## Installation
Cowork → Customize → Browse Plugins → Upload → select ZIP.

## Author
Artur Ferreira / The GEO Lab (thegeolab.net)

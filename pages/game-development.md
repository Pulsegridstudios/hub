---
title: Game Development
layout: wiki
permalink: /pages/game-development/
nav_group: development
nav_order: 0
nav_hidden: true
hero_image: /assets/images/control-room-banner.jpg
hero_title: Game Development
hero_subtitle: Systems, Scripting and Development Standards
status: reviewed
---

# Game Development

## Overview

This section outlines how to contribute to the **Looped Operations game**.

Development contributions must follow established standards to ensure:

- Stability  
- Performance  
- Consistency across systems  

All work should align with the existing structure and design principles.

---

## Technologies Used

Looped Operations is developed using the Roblox platform.

### Primary Languages

- **Luau (Roblox Lua)** — Core scripting language used for all game logic  
- **Roblox Studio APIs** — Used for services, events, and systems  

### Common Systems Used

- RemoteEvents / RemoteFunctions  
- ModuleScripts (for reusable systems)  
- Attributes (for system state)  
- Services (e.g. Players, RunService, ReplicatedStorage)

> ℹ️ **Note**  
> All contributors are expected to have a basic understanding of Luau scripting.

---

## Areas of Contribution

Development contributions may include:

- Reactor systems and simulation logic  
- UI systems and player interfaces  
- Backend scripting and system logic  
- Environment design and modelling  

---

## Development Principles

All systems should follow these principles:

- Keep systems **modular and reusable**  
- Avoid unnecessary complexity  
- Follow existing naming and folder structure  
- Prioritise performance over visual complexity  
- Ensure systems fail safely where possible  

---

## Code Standards

### General Rules

- Use clear and descriptive variable names  
- Avoid hardcoding values where possible  
- Use comments where logic is not immediately clear  
- Keep scripts focused on a single responsibility  

### Structure

- Use **ModuleScripts** for shared logic  
- Separate client and server logic properly  
- Store shared assets in `ReplicatedStorage`  
- Keep system scripts organised within folders  

### Example

```lua id="8sl8kd"
-- Good example
local ReactorService = {}

function ReactorService:SetPower(level)
	self.PowerLevel = level
end

return ReactorService
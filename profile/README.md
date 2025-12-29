# Ace of Pandea

## Next-Gen Ace Online Modern Server & Client

Ace of Pandea is a private modernization effort for the Ace Online game, built from experience and clear hindsight.

I released an initial version of this project and maintained it for over a year. That first attempt did not achieve the goals I set out to accomplish — due to gaps in knowledge, legacy server limitations, insecure protocol handling, outdated technology dependencies, and architecture decisions that didn't scale or hold up over time.

Rather than hide that reality, this project stands on it. Ace of Pandea is a second-generation effort that explicitly addresses what went wrong: modernizing server and client technology, improving security, building sustainable code structure, and moving beyond Windows-only dependencies.

## 🧠 Project Vision

Ace of Pandea aims to modernize the core technology stack of Ace Online by:

- Updating the server codebase to be secure, modular, and cross-platform
- Upgrading the client rendering engine from legacy DirectX9 to a modern API such as DirectX11 or equivalent
- Improving protocol handling, authentication, and security
- Enabling deployment on non-Windows platforms (e.g., Linux)

This effort focuses on correcting past shortcomings and building a foundation that can be maintained and evolved with confidence.

## 📈 Background & Motivation

A first iteration of the Ace of Pandea server was released and maintained for about one year, but ultimately did not meet its long-term objectives. The key issues encountered were:

- Legacy protocol insecurity (simple XOR encoding, no session protection)
- Weak memory safety and unstable server code
- Tight coupling with Windows-only technologies and DirectX9
- Lack of strong authentication and packet validation
- Difficulty maintaining and extending the codebase due to technical debt

Those challenges informed a broader, more structured approach. The current direction of Ace of Pandea directly targets these weaknesses by redesigning core components, strengthening security, and adopting modern technology standards.

## 🔧 What This Project Covers

### Server Modernization

- Complete overhaul of the backend with the objective of fixing vulnerabilities, improving security and performance
- Add session validation, anti-replay protections, and stronger authentication
- Eliminate unsafe legacy code and patterns
- Structure server logic for clarity and long-term maintenance
- Enable cross-platform execution (e.g., Linux hosting)

### Client Modernization

- Transition the graphics layer from DirectX9 to DirectX12, Vulkan, or other modern graphic APIs, or even contemporary game engines
- Improve compatibility with modern systems and drivers
- Provide a codebase that is maintainable and easier to evolve
- Maintain compatibility with updated server protocols where feasible

The client modernization path is intentional and scoped: refactoring legacy rendering and networking while preserving expected gameplay behavior.

## 🧠 Design Principles

- **Compatibility first**: No breaking changes for core gameplay unless necessary
- **Security-led rewrites**: Especially for networking and authentication
- **Incremental modernization**: Refactor in stages rather than rewrite everything at once
- **Cross-platform readiness**: Remove reliance on Windows-only tech where possible

## 📌 High-Level Goals

- **Security**: Eliminate known weaknesses in the protocol and server code
- **Maintainability**: Clean up legacy code and make it easier to extend
- **Compatibility**: Support modern systems with up-to-date graphics and runtime
- **Portability**: Enable server deployment on platforms beyond Windows

## ⚖️ Disclaimer


Ace of Pandea is a private modernization initiative. It is not an official Ace Online release and may not be distributed to the general public. The server is not intended to be opened publicly. This project uses no proprietary assets and remains compliant with all legal and ethical guidelines.

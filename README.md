
# ParanoidYaml (BETA)

**ParanoidYaml** is a specialized Skript addon designed specifically for the **Paranoid Wars** environment. This plugin serves as a high-performance, RAM-based alternative for managing YAML data within modern Minecraft servers.

---

##  Project Overview

This addon is built upon the foundation of **skript-yaml** by **Sashie**, maintaining the syntax and logic familiar to the Skript community while implementing critical fixes for modern environments.

> [!WARNING]
> **TEMPORARY SOLUTION:** This project is currently in a **testing phase** (Alpha/Experimental). It is a temporary bridge developed to solve specific compatibility issues and optimize performance.

---

##  Key Features & Fixes

- **Automated UUID Handling:** Silently converts Java UUID objects to Strings to prevent `InvalidConfigurationException` and "Global tag not allowed" errors in newer Paper/Spigot versions.
- **RAM-Based Performance:** Optimized for high-intensity PvP scenarios, loading data directly into memory for near-instant access.
- **Legacy Compatibility:** Designed to be a drop-in replacement. It supports existing syntax such as `yaml value`, `is loaded`, and `node list` without requiring changes to your current `.sk` scripts.
- **Improved Priority:** Configured to load before other major addons to ensure syntax consistency.

---

##  Installation & Usage

1. Place the `ParanoidYaml.jar` in your `plugins` folder.
2. Ensure you have **Skript** installed.
3. (Recommended) Delete your `plugins/Skript/cache` folder before the first restart to allow the new syntax to register properly.

---

## Disclaimer

As this is a **test build**, please use it with caution. It is intended to bridge the gap while we refine the server's data management systems. Expect frequent updates and potential changes as we stabilize core features.

---

## Acknowledgments

* Original logic and syntax inspiration: **Sashie** (skript-yaml).
* Developed for the **Paranoid Wars** community.

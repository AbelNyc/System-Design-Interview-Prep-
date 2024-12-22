# Linux Interview Prep: SRE & SWE

## Overview
This guide is designed to prepare for **Site Reliability Engineer (SRE)** and **Software Engineer (SWE)** interviews with a focus on **Linux fundamentals**. Topics include filesystems, permissions, process management, performance monitoring, and troubleshooting scenarios—all aligned with **big tech interview expectations**.

---

## Table of Contents
1. [Linux Filesystem Basics](#1-linux-filesystem-basics)
2. [File Permissions](#2-file-permissions)
3. [Process Management](#3-process-management)
4. [Performance Monitoring](#4-performance-monitoring)
5. [Disk Usage Troubleshooting](#5-disk-usage-troubleshooting)

---

## 1. Linux Filesystem Basics

### Explanation
The Linux filesystem is hierarchical, starting at the **root directory (`/`)**. Key directories include:
- **`/etc`**: Contains system and application configuration files.
- **`/var`**: Holds variable data such as logs, caches, and spools.
- **`/proc`**: A virtual filesystem that provides runtime system information like process and memory stats.
- **`/home`**: User home directories.
- **`/dev`**: Device files for hardware like disks and USB drives.

### Example Commands
- Check the size of the `/var` directory:
  ```bash
  du -sh /var

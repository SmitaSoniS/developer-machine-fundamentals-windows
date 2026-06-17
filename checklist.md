# Windows Development Environment Management Checklist

This checklist helps build practical understanding of how a developer machine works and how to maintain a clean, reliable development environment.

---

## 1. Disk Structure & Storage Awareness

**Outcome:** You understand what your machine physically looks like and where storage is being used.

* [ ] Identify all available drives on system (C:, D:, etc.)
* [ ] Check total size and free space available on each drive
* [ ] Open Disk Management and determine whether system uses one partitioned disk or multiple physical disks
* [ ] Locate Windows installation directory and verify system files exist there
* [ ] Record free space percentage on all drives
* [ ] Ensure no drive is above 85% utilization
* [ ] Ensure at least 20–25% free space remains on system drive (C:)
* [ ] Identify top 5 largest folders consuming storage
* [ ] Remove unnecessary large files and verify measurable storage recovery

---

## 2. File & Project Organization

**Outcome:** Project storage becomes structured and predictable.

* [ ] Create one dedicated parent folder for all coding projects (example `D:\Code`)
* [ ] Create separate folders for Projects, Practice, Experiments, Datasets, and Archive
* [ ] Confirm no coding projects remain scattered across Desktop, Downloads, or random folders
* [ ] Move inactive or old projects into archive folder
* [ ] Verify organized projects open correctly in VS Code

---

## 3. Python Installation & Environment Awareness

**Outcome:** You understand which Python is running and how environments work.

* [ ] Identify all installed Python versions
* [ ] Run `where python` and verify active Python executable
* [ ] Locate where Python is installed on machine
* [ ] Confirm no unnecessary duplicate Python installations exist
* [ ] Create and activate a virtual environment
* [ ] Locate `venv/` folders across projects
* [ ] Check size and location of virtual environments
* [ ] Delete one unused virtual environment
* [ ] Recreate deleted environment successfully
* [ ] Install package using pip and verify installation path

---

## 4. Cache, Temporary Files & Cleanup

**Outcome:** Temporary and cached files do not silently consume storage.

* [ ] Empty recycle bin and verify storage increase
* [ ] Delete unnecessary files from Downloads folder
* [ ] Delete duplicate copies of old project folders
* [ ] Locate Windows temporary files using `%temp%`
* [ ] Run Windows cleanup utility and remove temporary files
* [ ] Locate Python `__pycache__` folders
* [ ] Delete unnecessary `__pycache__` folders
* [ ] Locate pip cache using `pip cache dir`
* [ ] Inspect cached package files
* [ ] Clear pip cache using `pip cache purge`
* [ ] Verify storage space recovery after cleanup

---

## 5. Software Installation & Developer Tool Audit

**Outcome:** Installed software footprint is intentional and minimal.

* [ ] Review installed applications in Windows settings
* [ ] Identify installation locations of Python, Git, and VS Code
* [ ] Uninstall unnecessary or unused applications
* [ ] Review installed VS Code extensions
* [ ] Remove unused VS Code extensions
* [ ] Remove old unused workspace folders from VS Code recent projects list
* [ ] Confirm no duplicate developer tools are installed accidentally

---

## 6. RAM, Process & Performance Awareness

**Outcome:** You understand how applications consume system resources.

* [ ] Open Task Manager and record baseline RAM usage when system is idle
* [ ] Open browser, VS Code, and Python process simultaneously
* [ ] Observe RAM usage increase
* [ ] Record top 3 applications consuming highest RAM
* [ ] Close at least one unnecessary high-memory process
* [ ] Verify RAM is released properly
* [ ] Compare RAM usage versus disk storage usage
* [ ] Restart system and verify baseline RAM usage is healthy

---

## 7. PATH, Installation Conflicts & Troubleshooting

**Outcome:** You understand why Python and environment conflicts happen.

* [ ] Identify all installed Python versions
* [ ] Run `where python` and verify active Python executable
* [ ] Understand how PATH environment variable works
* [ ] Change Python interpreter in VS Code
* [ ] Verify different interpreter is being used successfully
* [ ] Fix incorrect interpreter selection
* [ ] Understand causes of Python not found, pip not found, and version conflicts

---

## 8. Developer Readiness Verification

**Outcome:** Machine is fully development ready without setup friction.

* [ ] Create a new Python project
* [ ] Open project in VS Code
* [ ] Create and activate virtual environment successfully
* [ ] Install package successfully using pip
* [ ] Run Python script successfully from terminal
* [ ] Verify project runs without path issues
* [ ] Delete project completely
* [ ] Recreate project cleanly without leftover environment issues

---

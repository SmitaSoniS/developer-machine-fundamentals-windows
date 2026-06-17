# Developer Machine Fundamentals Checklist (Windows)

A hands-on checklist to understand how your development machine works beyond just writing code.

---

## Windows System & Storage Management

**Outcome:** You understand what your machine physically looks like.

### Disk Structure Awareness

* [ ] Open File Explorer and identify all available drives on system (`C:`, `D:` etc.)
* [ ] Check total size and free space available on each drive
* [ ] Open Disk Management and determine whether your system uses one partitioned disk or multiple physical disks
* [ ] Document your findings
* [ ] Locate Windows installation directory
* [ ] Verify system files exist inside the installation folder

---

## File Organization

**Outcome:** No more random files on Desktop and Downloads.

* [ ] Create one dedicated parent folder for all coding projects (`D:\Code` or `C:\Code`)
* [ ] Create one archive folder and move one inactive or old project into archive
* [ ] Create separate folders for Python practice, projects, experiments, and datasets
* [ ] Move at least 3 existing coding/project folders into new organized structure *(skip if none exist)*
* [ ] Open moved projects in VS Code and verify everything still runs correctly

---

## Storage Awareness

**Outcome:** You know what is consuming disk space.

* [ ] Check free space on `C:` drive and record available storage
* [ ] Check free space on `D:` drive and record available storage
* [ ] Delete unnecessary files and verify storage space changes
* [ ] Use Windows Storage Settings or File Explorer to identify top 5 folders consuming the most storage

---

## Python Installation Awareness

**Outcome:** You stop feeling confused about which Python is running.

* [ ] Locate where Python is installed on machine
* [ ] Run `where python` and verify active Python executable
* [ ] Check all Python versions installed on machine
* [ ] Install one package using `pip`
* [ ] Locate installed package files on disk
* [ ] Verify installation path

---

## Temporary Files and Cache

**Outcome:** You understand what development tools store on disk.

* [ ] Locate Windows temporary files using system settings
* [ ] Delete temporary files using Windows cleanup utility
* [ ] Locate Python `__pycache__` folder created after running script
* [ ] Locate `pip` cache folder and inspect stored package files
* [ ] Locate VS Code extension installation folder and inspect disk usage

---

## Memory (RAM) vs Storage

**Outcome:** You understand the difference between RAM and disk.

* [ ] Open Task Manager and identify current RAM usage
* [ ] Open VS Code and observe RAM usage increase
* [ ] Run Python script and observe memory usage change
* [ ] Compare difference between RAM usage and disk storage usage
* [ ] Close running applications and verify RAM usage decreases

---

## Path and Installation Conflicts

**Outcome:** You understand why *Python not found* and version conflicts happen.

* [ ] Identify all installed Python versions on machine
* [ ] Verify active Python executable using `where python`
* [ ] Change Python interpreter in VS Code and verify different interpreter is being used
* [ ] Fix incorrect interpreter selection and run project successfully

---

## Software Installation Awareness

**Outcome:** You understand where installed developer tools live on disk.

* [ ] Install one developer tool (example: VS Code or Git)
* [ ] Locate installation directory on disk
* [ ] Verify executable path
* [ ] Understand how installed software adds entries to system PATH

---

## Final Goal

By completing this checklist, you should understand:

* How Windows organizes disks and storage
* How Python is installed and executed
* How environment variables and PATH work
* Where development tools store files
* How caches consume disk space
* Why interpreter conflicts happen
* How your machine behaves underneath your code

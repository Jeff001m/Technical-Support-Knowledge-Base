# Windows Troubleshooting Guide

## 1. Slow Computer Performance

### Symptoms
- Applications take a long time to open.
- High CPU or memory usage.
- Slow startup.

### Troubleshooting Steps
- Restart the computer.
- Check Task Manager for resource-intensive processes.
- Disable unnecessary startup programs.
- Run Disk Cleanup.
- Scan for malware.
- Install Windows Updates.

---

## 2. Windows Update Failure

### Symptoms
- Updates fail to install.
- Error codes appear.

### Resolution
- Restart Windows Update Service.
- Run the Windows Update Troubleshooter.
- Clear the SoftwareDistribution folder.
- Retry updates.

---

## 3. Blue Screen (BSOD)

### Possible Causes
- Faulty drivers
- RAM issues
- Disk errors
- Hardware failure

### Resolution
- Check Event Viewer.
- Update drivers.
- Run Windows Memory Diagnostic.
- Run:
```

```cmd
sfc /scannow
```

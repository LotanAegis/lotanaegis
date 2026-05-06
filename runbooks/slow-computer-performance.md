# Runbook: Slow Computer Performance (Windows)

**Issue:** Computer is running noticeably slow.

**Symptoms:**
- Long boot times
- Programs take time to open
- High disk usage in Task Manager

**Troubleshooting Steps:**
1. Check Task Manager for high CPU / Disk / Memory usage
2. Run Disk Cleanup + Storage Sense
3. Disable unnecessary startup programs
4. Scan for malware with Windows Defender
5. Check for Windows updates
6. Run `sfc /scannow` and `DISM` commands

**Common Causes:**
- Too many startup programs
- Low disk space (<15% free)
- HDD instead of SSD
- Background processes / malware

**Resolution Notes:**
Record current RAM usage, disk type (HDD/SSD), and top 3 processes using resources.

**Next Steps if Unresolved:**
Recommend hardware upgrade (SSD) if issue persists after software fixes.
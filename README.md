# log_rotation
This repository contains a Bash script designed for automated log file rotation and management.
# Log Rotation and Management Script

## Overview
This repository contains a **Bash script** for automated log file rotation and management. The script ensures efficient handling of log files by following these rules:

- **Rotate** log files that are less than **7 days old**.
- **Compress** (`gzip`) log files that are **older than 7 days**.
- **Delete** log files that are **older than 14 days**.

## Features
✅ Automates log maintenance to prevent excessive disk usage.  
✅ Uses `find` command for efficient file selection.  
✅ Simple and customizable for different log directories.  

## Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone <repository-url>
cd log-rotation-script

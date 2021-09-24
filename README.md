# Python-Scripts
This repository contains all the python scripts for different purpose

**Script Name:Script to delete stale entries from a LAB environment setup**
# ===============================================================
# Script to delete stale entries from a LAB environment setup.
# ===============================================================
#
# Version: 1.0
# Date   : 2021-05-17 (last updated date)
# Editor : Maintained by CFTS team.
# contact: rkwatra@juniper.net
#
# ---------------------------------------------------------------
# Revision History
#  __________________________________________________
# | Date | Version | Comments |
# |--------------------------------------------------|
# | 2021-05-17 | 1.0 | Initial Draft |
# |__________________________________________________|
# ---------------------------------------------------------------
# ---------------------------------------------------------------
# Usage Instructions
# ---------------------------------------------------------------
#
# 1. This script has to be run inside the "contrail-vrouter-agent" container as a root user. Navigate to the container as below:
#     docker exec -it -e COLUMNS=$COLUMNS -e LINES=$LINES "Container ID" bash
#
# 2. To execute this script type: python remove_stale_entries.py
#
# 3. Rename the provided file "Computename_UUID_Entries.txt" file to "UUID_Entries.txt" file and place it under script location
#
#   Note: Ensure "remove_stale_entries.py" and UUID_Entries.txt" file should be kept under same location while running python script.
#
#
# Check the script is being used properly


# wls-mft-utils
WLST script based utilities for managing Oracle Managed File Transfer
## Available functionality:
    [1] Resubmit files by Target IDs (supports reading Target IDs from file) - DRY RUN ONLY
    [2] Resubmit files in bulk using filter: resubmitType, state, artifactName, startTime, endTime and ignoreIds.
        Supports both DRY and REAL runs.
    [3] Resubmit files by Target IDs (supports reading Target IDs from file)
    [4] Get list of key/pwd"

## Usage:
1. Execute: wlst manageMFT.py -loadProperties manageMFT.properties
2. Select action \[1-4]

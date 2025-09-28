# COLD WAR AUTO STARTER AND PAUSER BY CBRNN

**How to setup LiveSplit TCP Server**
- Open Livesplit
- Right click -> Control -> Start TCP Server

**Config Guidance**
The reset delay tells the timer how long after a reset is triggered it should start.
Too early leads to various different issues. Currently, 9.6 (s) appears to be working.

**Known Limitations**
The pause/unpause may experience a <0.05 delay due to latency between the application and TCP server.

This should generally even out over time.

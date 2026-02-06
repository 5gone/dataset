# 5Gone Open Science Repository

## Attack Logs

In the subdirectories, you can find the logs for the attacks, starting from the attacker, the UE, and all the way to the AMF. The logs for the Amarisoft components can be best viewed in their web viewer, reachable at https://tech-academy.amarisoft.com/web-gui/

## Tracy

In the subfolder `k2_1`, there is also a trace of the software. The trace can be best viewed with the tracy-profiler v0.12.2. Zones of interest include, e.g.,`handle_ul_grants`, which is present when there is a PUSCH transmission to be sent. Using cat, first re-assemble the parts.

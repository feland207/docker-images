# Hybrid Bridge Lab Environment

This repository contains the infrastructure automation and lab definition topologies for the project. 

## Requirements
To run this topology locally, you must provide your own legally licensed Juniper images.

## Local Image Build Guide
1. Obtain the `vJunos-switch` `.qcow2` image from the official Juniper portal.
2. Build the target image locally using the `vrnetlab` framework tools:
   ```bash
   docker load < vjunos_switch_25.4.tar.gz


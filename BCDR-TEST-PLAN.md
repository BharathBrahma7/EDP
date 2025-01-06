# BCDR TEST PLAN - Actionable Items

## Create HDI Clusters (in Secondary Location)
- [ ] List the HDI Clusters and check if the scripts for the EV2 exist
- [ ] If the scripts do not exist, author the script
- [ ] Check if the pipelines need to be modified to add the BCDR related clusters

## Storage Accounts Creation (in Secondary Location)
- [ ] Identify the storage accounts needed in secondary location
- [ ] If the scripts do not exist, author the script
- [ ] Check if the pipelines need to be modified to add the BCDR related clusters

## Disable Triggers in the Primary Location
- [ ] How can this be done automatically / manually

## Enable Triggers in Secondary Location
- [ ] How can this be done automatically / manually

## Verify and Collect Information that Data has been Copied to the Secondary

- [ ] How to ensure that data is copied? Check sync time? 

## Run the Missed Jobs on the Primary to Catch Up and Enable Alerts Again in Primary
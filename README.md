## WIN-HYPER-V-CREATEVM

### Enable Hyper-V.
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All`

### Allow unsigned scripts.
`set-executionpolicy remotesigned`

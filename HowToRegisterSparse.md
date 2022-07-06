1. Install the signing certificae into local machine trusted root certificate (I am not sure but, in 21H2 Add-AppxPackage does not have option for AllowUnsinged neither Intermediate certificae folder, not work)
2. Build SparseWPF and Run "As Administrator"
3. Click Register

NOTE: I did not check depth, but it seems I cannot uninstall SparsePackage with Remove-AppxPackage so it seems there is a different between cmdlet and API

No longer used, instead replaced by simply putting two github workflows in the flathub repository.
One updates the beta branch nightly with f-e-d-c, the other updates the master branch hourly with f-e-d-c.
See the 2 github workflows [here](https://github.com/flathub/com.github.wwmm.easyeffects/tree/49675393ff1c468cdf6323208685e662c3a39ce6).

[![Nightly commit checker status](https://github.com/vchernin/nightly-easyeffects-checker/actions/workflows/nightly-checker.yml/badge.svg)](https://github.com/vchernin/nightly-easyeffects-checker/actions/workflows/nightly-checker.yml)

Fetch the latest [EasyEffects](https://github.com/wwmm/easyeffects) commit every 24 hours.  
Used by [EasyEffects Flatpak](https://github.com/flathub/com.github.wwmm.easyeffects/)

Can manually dispatch action from Workflows menu

Credits:
https://github.community/t/how-to-make-a-workflow-file-to-save-the-output-as-a-file-to-my-github-repo/18352/2

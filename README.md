# factorio_mod_automation_example
This repo is used to develop/test automation for factorio mod development

## Required Files

- info.json
- changelog.txt

## How to use

1. Copy the full folder structure of .github
1. Update the name of the mod in the file name of `deploy-mod.yml` (ie. `deploy-Seablock.yml) *No spaces allowed*
1. Update the variables to your mod
1. Push changes

### Assumptions

- Your mod files are *not* at the root level, but within a folder with the mod name

### Variables to change

- `github.repository_owner`: This should be updated to the owner of the mod's repo. This can be a user or an organization. Current value == `quickjp2`
- Mod name: Search for sample_mod and replace it with your mod's name
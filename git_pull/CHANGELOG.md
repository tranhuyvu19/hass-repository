# Changelog

## 5
- Update Hass.io CLI to 1.4.0
- Add new API role profile

## 4.9
- Fix git repo detection in config-dir - #372
- Fix repeat option detection - #375
- Allow to stay on the currently checked out branch - set "git_branch": ""
- Correct typo

## 4.8
- Add option to use git reset instead of git pull
- Validate git origin URL

## 4.7
- Update Hass.io CLI to 1.3.1

## 4.6
- Update Hass.io CLI to 1.3.0

## 4.5
- Update Hass.io CLI to 1.2.1

## 4.4
- Update Hass.io CLI to 1.1.2

## 4.3
- Downgrade Hass.io CLI to 1.0.1

## 4.2
- Update Hass.io CLI to 1.1.1

## 4.1
- Add support for key validation against ssh cloned GitHub repositories

## 4.0
- Allow to use user/password authentication for GIT
- New options `deployment_user` and `deployment_password`

## 3.0
- New CLI
- Update base image
- Backup of files before clearing the /config folder
- Copy back all non YAML files and the secrets.yaml after the git clone
- More verbose error handling. Also logging the GIT exceptions.
- Splitted code out into functions
- Check SSH connection before setting the key

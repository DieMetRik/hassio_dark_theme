Create "themes" folder in /config
ADD this to configuration.yaml
```
frontend:
  themes: !include_dir_merge_named themes
```
copy file with name dark.yaml to /config/themes
Reset YAML configuration 
Chose dark theme in your profile

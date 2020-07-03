{% if installed %}
## Changes as compared to your installed version:

### Breaking Changes

### Changes

### Features

{% if version_installed.replace("v", "").replace(".","") | int < 141  %}
- 
- 
{% endif %}
{% if version_installed.replace("v", "").replace(".","") | int < 142  %}
- Release notes are shown in HACS depending on your installed version
{% endif %}

### Bugfixes

{% if version_installed.replace("v", "").replace(".","") | int < 143  %}
- 
{% endif %}
---
{% endif %}

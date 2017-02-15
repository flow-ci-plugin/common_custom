
# custom Step
Custom script

### INPUTS
* `FLOW_ENABLE_FAILURE` - 

## EXAMPLE 

```yml
steps:
  - name: custom
    enable: true
    failure: true
    plugin:
      name: custom
      inputs:
        - FLOW_ENABLE_FAILURE=$FLOW_ENABLE_FAILURE
```

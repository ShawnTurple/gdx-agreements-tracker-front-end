# GDX Agreements Tracker React Web Application.

## Build

```
oc project acd38d-tools
oc process -f build.yaml | oc create --save-config=true -f -
```
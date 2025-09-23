# Virtual Machine Templates for OpenShift Virtualization

Usage
```
$ oc apply -f - <<EOF
$(sed "s/{{ .hostname }}/user-guest-name/g" any-vm-template.yaml)
EOF
```



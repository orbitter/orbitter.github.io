```shell
anger.sh &>/dev/null & while [[ -n $(jobs -r) ]]; do echo -n "."; sleep 1; done
```

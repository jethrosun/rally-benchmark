# rally-benchmark



## About the config option setup in Rally

```
"runner": {
        "type": "constant",
        "times": 100,
        "concurrency": 1
},
"context": {
        "users": {
        "tenants": 1,
        "users_per_tenant": 1
},
```

It is typical to setup these options in Rally workload. Below is a
little break-down:

* `times`: 'times' is a non-zero positive integer which specifies how many
times to run the action in sequence.    
* `concurrency`:  :param concurrency: number of concurrently running scenario iterations
* `users`
* `tenants`
* `users_per_tenant`





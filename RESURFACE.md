# Convert sigma rules to resurface

Command:

```
./tools/sigmac -t resurface -c ./tools/config/resurfaceio.yaml <path-to-rules> --backend-option table=<table-name>
```

Example:

```
./tools/sigmac -t resurface -c ./tools/config/resurfaceio.yaml ./rules/generic/generic_brute_force.yml --backend-option table=memory.resurface.message 
```
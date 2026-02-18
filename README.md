# rtic-ravenscar-mast-analysis
repo for report that compares the real-time scheduling capabilities of rtic and ada ravenscar

## Submodules

This repository includes two submodules:
- `rtic-realtime-evaluation`: RTIC real-time evaluation project
- `ada-realtime-evaluation`: Ada Ravenscar real-time evaluation project

To clone this repository with all submodules:
```bash
git clone --recurse-submodules https://github.com/tharencandi/rtic-ravenscar-mast-analysis.git
```

To initialize submodules in an already cloned repository:
```bash
git submodule update --init --recursive
```

## rtic-realtime-evaluation

- application in main
- application setup for WCET and deadline miss detection:

`git checkout deadline_miss`

## ada-real-time-evaluation

- application in main
- application setup for WCET and deadline miss detection:

`git checkout for_wcet_measurements`


## overhead-tests

e2e latency tests in main

N tasks v release jitter in a different branch:

- rtic: `git checkout ghost_task_test`

- ada: `git checkout ghost_task_test`

## mast-comparative-experiments

run experiments with:

`./run_experiment_i.sh`
`./run_experiment_ii.sh`
`./run_experiment_iii.sh`
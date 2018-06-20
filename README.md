# AGORA GIZMO Runs

## Installation

Make sure [Mercurial](https://www.mercurial-scm.org/) (hg) is available. Then proceed with:
```bash
source init.sh

cd code
source config/{system}/init.sh
make
```

## Simulation runs

```
source init.sh

cd lab/run/isolated-disk
make
```

Test in a conda environment:
```bash
./script/run-conda.sh
```

Submit a job on Edison:
```bash
sbatch script/job-edison.sh
```

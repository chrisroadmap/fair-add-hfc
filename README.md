# fair-add-hfc
Demonstrating adding a custom HFC to a FaIR 2.1 run that is not included in the default config.

## Prerequisites
- `anaconda`
- `git`

## Reproduction
1. Clone the repository. If you think you will want to make your own changes and push to the main repo, take a fork of https://github.com/chrisroadmap/fair-add-hfc, and clone the fork. If you only want to reproduce results, creating a fork is not required.
2. After cloning, `cd` to `fair-add-hfc`
3. Create the conda environment with `conda env create -f environment.yml`
4. Activate with `conda activate fair-add-hfc`
5. If you have taken a clone of your own fork with the intention of committing changes (otherwise, this step is not required), then
   - create a branch with `git checkout -b <your branch name>`
   - run `nbstripout --install` to commit clean notebooks
6. run `jupyter notebook`, then run the notebooks inside the `notebooks` directory.
7. If making changes, commit your changes with
   - `git add .`
   - `git commit -m <helpful short commit message>`
   - `git push origin <your branch name>`
   - then create a pull request from your fork and branch to the chrisroadmap/main branch, which will be reviewed, and if all satisfactory will be merged in.

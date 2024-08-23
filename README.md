# Collection of Conda Recipes
 
## Build/Upload Commands

[docs.conda.io Build and Upload Documentation](https://docs.conda.io/projects/conda-build/en/stable/user-guide/tutorials/build-pkgs-skeleton.html)
[`grayskull` CLI Reference](https://conda.github.io/grayskull/cli.html)
[`conda-build` CLI Reference](https://docs.conda.io/projects/conda-build/en/latest/resources/commands/conda-build.html)

To build the package (without running tests) and save it to the `~/Downloads` folder for easy access:

```bash
conda-build --no-test --output-folder ~/Downloads bw2data
```

To upload the package under a specific label:

```bash
anaconda upload --label dev ~/Downloads/(...).tar.bz2
```
# project-template
A sandbox project for setting up an environment containing Pytorch / Scikit Learn, FSL, SPM12 and Anatomist/BrainVISA. 

This is work in progress. It may stop working or be modified at any time. Use it only for testing for now.

## Prerequisite

The only thing that this project depends on is [Pixi](https://pixi.sh).

## Usage

To setup and activate the environement, one can use:
```
git clone https://github.com/sapetnioc/project-template
cd project-template
pixi shell
```

Then the environment is ready to use. There is a demo Jupyter Notebook that may be used with VS Code (some extensions such as Jupyter are required but I did not list them):
```
cd project-template
pixi shell
code .
```

Then open the `demo.ipynb` file and run the cells. VS Code will ask for a Python environment but it detects the Pixi environment (in recent versions, maybe not before July 2024) and propose the good one (this is a Python 3.11 due to FSL and BrainVISA constraints).

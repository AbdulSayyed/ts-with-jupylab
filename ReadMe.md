## About this folder and workspace

- This folder is used to write typescipt code in jupyter environment.
- The folder `jupy-ts` is present in `K:/projects/python/` directory, here all working directories are kept that are created with `conda env`. For example when you cd into this directory and run `conda activate ts-with-jupylab`, a conda environment is activated.
- All files and packages related to run this environment are installed in `w:/miniconda/env/ts-with-jupy-lab`.
  
### Usage

- Cd into this folder and open `code . or code - workspace name`.
- When code opens make sure that `pyhong environment manager` extension is enabled.
- Click this extension and all virtual environments are visiable. Using the arrow sing open the terminal, it will activate the environment.
- From here type `jupyter lab`, if it asks for the password type `1234`.
- To enable typscript in jupyter lab `tslab` extension was used from the github, it needs to be installed correctly.
- I have installed this globally, following the instruction you need to install its packages using npm, insruction are present on [tslab](https://github.com/yunabe/tslab)
  
### Notes

- Though vscode terminal seems to be working, but I have prepared a cygwin shell for this project, its entery is present in `setting.json` file. You can open this ternminal and start working.
- Problems were coming to commit from conda shell using cywin, copied all files from C:/sghaf/.ssh folder to `w:/cygwin/cygwin64/home/` folder.
- Added `git config --global credential.helper store`
- Another problem started to come from conda and power shell that it would not understand the commit message.
  
```text
   sghaf: jupy-ts on main [ ts-with-jupylab 3.10.8] [ 18.12.1] ❯ git cm -m "normal committ"
error: pathspec 'normal committ' did not match any file(s) known to git
```

- This trun out to be a problem of chracters and it was solved using `git commit --message "normal commit"
- This works 
# VS Code and miniconda intergration
## Mac OS
### Install the miniconda distro if it's needed 
```
# curl -o /tmp/m.sh -s https://repo.anaconda.com/miniconda/Miniconda3-py39_23.5.2-0-MacOSX-arm64.sh && bash /tmp/m.sh -b -p $HOME/miniconda
```
### Prepare a separate env
```
# ~/miniconda/bin/conda env create -f ./develop/miniconda-environment.yml
# ~/miniconda/envs/hvac-teensy/bin/pip list local| grep hvac
```
### vs code config
A workspace configutaion into ./.vscode/settings.json
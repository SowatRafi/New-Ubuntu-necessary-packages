    # New-Ubuntu-necessary-packages
This is a bash script for downloading and enabling necessary things into your Uubntu for a better performance &amp; setup.

1. You have to open your terminal (`Ctrl` + `Alt` + `T`)
2. Then go to the folder `cd New-Ubuntu-necessary-packages/`
3. Now, you have to give permission to the script by `chmod +x {file-name}.sh` in terminal. (Only for one time)
  * If it is in a folder then you have visit the folder at first by `cd {folder-name}/`
  * Or `chmod +x {folder-name}/{file-name}.sh`
4. Then run `./{file-name}.sh` or it is in a folder then `./{folder-name}/{file-name}.sh` to run the script.

**Note -01**: _You may have to provide your Ubuntu password for running those scripts._



## For installing `Anaconda` in Ubuntu:

Run the anaconda prerequisite script from the `Development & Engineering tools` folder.
    
    cd Development\ \&\ Engineering\ tools/
    chmod +x anaconda_prerequisites.sh      # {if the permission is not given}
    ./anaconda_prerequisites.sh
    
[Download Anaconda](https://www.anaconda.com/products/individual#linux)
    
    `bash ~/Downloads/{Anaconda-file-name}.sh`
    
After installing:
    
    conda config --set auto_activate_base False {if you want to auto on the base}
    
    # {For enabling conda}
    conda activate
    
    # {For Anaconda Navigator}
    anaconda-navigator
    
    # {For deactivate}
    conda deactivate

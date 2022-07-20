# Bash variables  

The vars are set and used by Bash. Other shells do not treat them specially.  

BASH_SOURCE  
- an array var, whose elements are the source filenames where the shell funcnames in the FUNCNAME arrvar are defined.  

The shell function `${FUNCNAME[$i]}` is defined in the file `${BASH_SOURCE[$i]}` and called from `${BASH_SOURCE[$i+1]}`.  



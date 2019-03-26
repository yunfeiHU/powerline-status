## First. Check whether you have Python and Pip installed

* Check if you have [python](https://www.python.org/) install on your computer by running this
command in your terminal

```bash 
   $bash python --version 
```

* Check if you have [pip](https://pip.pypa.io/en/stable/) installed by running this
command in your terminal

``` bash
   $bash pip --version 
```

### If [Python](https://www.python.org/) has not been installed you can install it follow this link: https://www.python.org/
* After you have installed [Python](https://www.python.org/), check whether [Pip](https://pip.pypa.io/en/stable/) has been installed along with [Python](https://www.python.org/) by this command in your terminal

```bash
   $bash pip --version 
```

* If it has not been installed head to install [Pip](https://pip.pypa.io/en/stable/) by running this command in your terminal
```bash
   $ bash curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```

* Then run this command

```bash
   $bash python get-pip.py
```

## Second. Install powerline-status
* Run this command in your terminal

``` bash
    $bash pip install powerline-status
```

* Type this command to see if it has been successfully installed (Remember where it is located)

 ```bash
    $bash pip show powerline-status
 ```

### Config bash

```bash
   POWERLINE_SCRIPT=/usr/local/lib/python3.6/dist-packages/powerline/bindings/bash/powerline.sh
   if [ -f $POWERLINE_SCRIPT ]; then
   source $POWERLINE_SCRIPT
   fi
```


### Config Vim

```bash
   set rtp+=/usr/local/lib/python3.6/dist-packages/powerline/bindings/vim/
   " Always show statusline
   set laststatus=2
   " Use 256 colours (Use this setting only if your terminal supports 256 colours)
   set t_Co=256
```


   
   
 

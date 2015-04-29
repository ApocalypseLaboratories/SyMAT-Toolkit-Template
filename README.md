SyMAT Toolkit Template
======================

Starting in version 2.0, SyMAT has the ability to load toolkits into scripts.

These toolkits are jar files with a special meta.txt file.  
This meta file maps packages and classes to variables they can be accessed with.

The jar files should be placed in ~/.symat/toolkits.  
This folder is automatically created when SyMAT launches the first time.

The meta.txt file included in this template maps the class 
com.symatapp.toolkit.HelloWorld to the variable hello.  
To call the function world(), type hello.world() into SyMAT.

License
-------

This repository is in the public domain, according to the terms of 
Creative Commons Zero (https://creativecommons.org/publicdomain/zero/1.0/).

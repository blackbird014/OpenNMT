
<a id="nmt.STYLE.Style_Guide"></a>
# Style Guide

<a id="nmt.STYLE.Comments"></a>
## Comments 

* Comments should follow:
https://github.com/deepmind/torch-dokx/blob/master/doc/usage.md

* All non-private method should have dokx comments describing input/output.  

* All classes should have a class docstring at the top of the file. 

* All comments should be on their own line, and be a complete English
sentence with capitalization.

* Use torch-dokx and this command to build docs 
> dokx-build-package-docs -o docs .
> google-chrome doc/index.html


<a id="nmt.STYLE.Style_"></a>
## Style:

* Please run and correct all warnings from luacheck before sending a pull request. 

> luacheck *

* All indentation should be 2 spaces.
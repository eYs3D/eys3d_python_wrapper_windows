### Feature
* Frame callback
* Pipeline
* Compatible with OpenCV
* Numpy supported
* Preview point cloud with openGL.
* Support 8036(G100),8052(G50),8059(R50),8062(G100i),8081(G62),80362(G100+)
* HYPATIA(G53),HYPATIA2(R77),Stacy(REF-B6),StacyJunior(REF-B3)
* Interleave mode
* DepthFilter
* Accuracy

### Getting the code

### Clone this repository with submodules
```git clone git@github.com:eYs3D/eys3d_python_wrapper_windows.git```

### Prerequisite
* eYs3D camera module

### Primary required software packages
* python3.7(https://www.python.org/downloads/release/python-379/)

# Configure Python Environment

### Create Python virtual environment
```console
$ python -m venv venv
$ venv\Scripts\activate
```

### Install required Python packages with pip
```console
$(venv) pip install -r requirements.txt
```

## Run demo code
```console
$(venv) cd libeYs3D\wrapper\python
$(venv) .\run_demo.bat <module_name> <mode_index> <bits>


Then select index to execute sample code.
1. cv_demo
2. pc_demo
3. callback_demo
4. accuracy_demo
5. record_playback_demo

```
ex: If your module is G100+, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 80362 1 14
```

ex: If your module is G62, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 8081 1 14
```

ex: If your module is REF-B6, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat Stacy 1 14
```

ex: If your module is REF-B3, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat StacyJunior 1 14
```

ex: If your module is G100i, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 8062 1 14
```

ex: If your module is G53, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat HYPATIA 1 11
```

ex: If your module is 8067, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 8067 1 11
```

ex: If your module is R50, mode index 5 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 8059 5 11
```

ex: If your module is G100, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 8036 1 14
```

ex: If your module is G50, mode index 1 on ModeConfig.db.<br>
```console
$(venv) .\run_demo.bat 8052 1 14
```

If you want to exit python virtual environment <br>
```console
$(venv) deactivate
```

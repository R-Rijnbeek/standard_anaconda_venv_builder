# standard_local_anaconda_builder
Repository with as purpose to have a standard protocol to build a virtual environment inside the project based on an YML file

## prerequisites

Has anaconda installed on windows. And configured you system variables ($path) of anaconda on windows: 
* C:\ProgramData\Anaconda3
* C:\ProgramData\Anaconda3\Scripts
* C:\ProgramData\Anaconda3\Library\bin

## Instalation protocol

1. Clone the github repository.
```
$ git clone https://github.com/R-Rijnbeek/standard_local_anaconda_builder.git
```

2. Enter the project folder.
```
$ cd standard_local_anaconda_builder
```

3. Build the virtual environment on the repository by running:
```
$ build.bat
```

4. To activate the environmet and run the test scripts:
```
$ activate ./env
$ python test.py
```

## Notes to know: 

1. The current YML file is an standar one to execute python in the last version
2. If you need add more libraries. Then you only need to add them in thye current yml file or create an new one replacing it.
3. This repository is tested with windows 10 and anaconda version 4.11.0

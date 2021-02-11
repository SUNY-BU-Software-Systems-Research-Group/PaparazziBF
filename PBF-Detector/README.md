# STATEMENT
* This is a static code analysis tool that work on a modified version of paparazzi codebase (https://github.com/SUNY-BU-Software-Systems-Research-Group/paparazzi). Please pull the modified paparazzi repository if you want to apply this tool.

# COMPONENTS
* Directory "headers": header files in this directory are used by libClang, libTool, and plugin version of code.

* Directory "plugin": clang plugin implementation of bounding function dictionary builder

* AC_COMPILE_SCRIPT.sh: a script to simulate GUI compilation on target 'ap', 'sim', and 'nps' on corresponding aircrafts
	- Before running AC_COMPILE_SCRIPT.sh, make sure that you've run "make" under repository SUNY-BU-Software-Systems-Research-Group/paparazzi.

* modify_plugin_path_list.txt: a list of places under repository SUNY-BU-Software-Systems-Research-Group/paparazzi where we need the path of the Bounding Function dictionary builder clang plugin 'BFDictBuilderPlugin.so', which is generated in the "plugin" directory of this repo. Please go to the listed files under repository SUNY-BU-Software-Systems-Research-Group/paparazzi and replace the plugin paths with the path on your computer.

* paparazzi_change_log.txt: a change log to list the changes under repository SUNY-BU-Software-Systems-Research-Group/paparazzi.
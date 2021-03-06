# IfcOpenShell Scripting Tutorial 

![Viewer screenshot](img/rwth_ifc_viewer.png)

This repository contains educational resources including a tutorial to learn scripting your own applications for processing **Industry Foundation Classes (IFC)** files. It is based on a scriptable viewer tool that uses the [IfcOpenShell](http://ifcopenshell.org) toolkit. The scriptable viewer tool has been created for teaching purposes and is used at the [Eindhoven University at Technology](https://www.isbe.tue.nl) and the [RWTH Aachen University](http://dc.rwth-aachen.de) .  

A packaged __binary version of the tool__ is available at [this location]( http://caad.arch.rwth-aachen.de/download/rwth_viewer.zip )(175 MB!) to get you started. It comes with "all batteries included", including python, IfcOpenShell and the Python OpenCascade wrappers.

The package includes alls necessary source code to extend, modify, reuse the scripting viewer to your liking.

The viewer and the tutorial are **Open Educational Resource (OER)** that can be used under MIT license conditions in academic or commericial educational settings. 

Follow these simple steps to 'install' the viewer/scripting application:

  - Download tue_viewer.zip (175 MB) and the [snippets configuration file](https://raw.githubusercontent.com/jakob-beetz/IfcOpenShellScriptingTutorial/master/src/snippets.conf) which contains a few example snippets to get you started.
  - in your home directory (e.g. C:/Users/yourname) create a directory called ".ifcopenshell" (*note: Microsoft is "protecting" you from creating a directory starting with a "." in MS Explorer. Open a command shell (press the windows button on your keyboard, type "cmd"), change to your home directory (cd C:\Users\myname) and create the directory by typing "mkdir .ifcopenshell) in this create another directory called "app" and place the snippets.conf there (Note, if you have started the application once allready, you will find the directory structure and a default snipptes.conf there. You can overwrite this)
  - Unpack tue_viewer.zip and start the viewer by double-clicking start_viewer.cmd
  - Follow the tutorial in [this wiki](https://github.com/jakob-beetz/IfcOpenShellScriptingTutorial/wiki/Home)

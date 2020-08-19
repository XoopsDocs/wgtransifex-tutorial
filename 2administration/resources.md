# Resoruces

## 1. Overview

![](../.gitbook/assets/2resources1.jpg)

_Figure 4a: Resources projects list \(Admin side\)_

In this tab you can see list of projects where resources are already existing.

For more details about 'Status' please look on page [Status](status.md)

![](../.gitbook/assets/resources.png) you can show resources of this project

## 2. List of resources

![](../.gitbook/assets/2resources2.jpg)

_Figure 4b: Resources List \(Admin side\)_

Here you see a list of existing resources of selected project.

![](../.gitbook/assets/readtx.png) you can read details this resource from transifex

![](../.gitbook/assets/edit.png) you can edit details of the resource

![](../.gitbook/assets/delete.png) you can delete the resource


## 3. Name of a resource

The name of the resource contains the full path, starting from base directory. Brackets and - defines the folder structure.

The base directory is define by project type (see also [Projects](2administration/projects.md)).

Examples:
* Project type 'Upload from module': 

  The base directory for module language files is the folder 'languages' in the module directory. The folder name is defined by your language (e.g.'german').
  If resource name is 'admin.php' then this resource will be saved as 'admin.php' in folder 'german'. 
  If resource name is '[mail_template]global_alb_approve_notify.tpl.txt' then this resource will be saved as 'global_alb_approve_notify.tpl' in folder 'german/mail_template/'.
  
  Therefore you can copy this folder directely into your module language folder.

* Project type 'XOOPS Core': 

  The base directory for XOOPS Core language files is the root folder (e.g. (htdocs').
  If resource name is '[language-yourlang]user.php' then this resource will be saved as 'user.php' in folder 'htdocs/language/german/'. 
  If resource name is '[modules-system-language-yourlang]admin.php' then this resource will be saved as 'admin.php' in folder 'htdocs/modules/system/language/german/'.

  Therefore you can copy this folder directely into your root folder.
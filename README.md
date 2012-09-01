Description
===========
This cookbook installs SharePoint 2010 Foundation. Based on which attributes your provide it can install in either a standalone or Farm configuration. 

Requirements
============

Attributes
==========
default['sharepoint2010']['module_path'] = "C:\\Windows\\System32\\SPModule\\"
default['sharepoint2010']['setup_path'] = "C:\\SharePointFoundation\\"
default['sharepoint2010']['prereq_path'] = "C:\\SharePointFoundation\\PrerequisiteInstallerFiles"
default['sharepoint2010']['server_role'] = "SINGLESERVER"
default['sharepoint2010']['pid'] = nil

Usage
=====


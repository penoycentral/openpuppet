Module Layout

<MODULE NAME>
manifests
files
templates
lib
facts.d
tests
spec

where:
manifest: Contains all of the manifests in the module
files — Contains static files, which managed nodes can download.
lib — Contains plugins, like custom facts and custom resource types
facts.d — Contains external facts, which are an alternative to Ruby-based custom facts. 
templates — Contains templates, which the module’s manifests can use.
tests — Contains examples showing how to declare the module’s classes and defined types.

Writing module
$puppet module generate <username>-<module name>

Module Tool
#puppet module install puppetlabs-apache --versio  0.0.2
#puppet module list
#puppet module search
#puppet module uninstall
#puppet module upgrade
#puppet module generate

To publish Module
1. Create a Puppet Forge account, if you don’t already have one.
2. Prepare your module.
3. Write a metadata.json file with the required metadata.
4. Build an uploadable tarball of your module.
5. Upload your module using the Puppet Forge’s web interface.

Note:
- Module name should be username-modulename Be sure to use this long name in your module’s metadata.json file
- its web interface presents them as username/module
- set files to be ignored. Include them in .gitgnore .pmtignore
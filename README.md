collectd_teamspeak3
===================

Teamspeak 3 monitoring plugin for CollectD

# Introduction

This is a simple but useful collectd plugin to collect statistics from Teamspeak 3 servers via serveradmin interface.

# Usage

teamspeak3.conf provides a example collectd plugin description

You might want to set

	ModulePath

to the path where the python file resides. This is /root/ in my case.

You will have to set the password in the conf file.

# Debugging

In this plugin there is a command line implementation of collectd python package which allows calling via command line.

	python collectd_ts3.py

You will have to set the password in the pythin script

	PASSWORD = 'your_serveradmin_password'

Now you can see what the plugin is doing and if it is working properly.

# Related

To find out how to configure serveradmin, please read the documentation provided by the Teamspeak developers.

# Contribution

If you would like to improve the plugin, give feedback or extend it, please feel free to do so.
You might want to fork it and make a pull request or simply send me a message. Additionally I would appreciate some (positive) criticism on my code so I can improve it.
Appointment Scheduling Module
==========================
[![Build Status](https://travis-ci.org/openmrs/openmrs-module-appointmentscheduling.svg?branch=master)](https://travis-ci.org/openmrs/openmrs-module-appointmentscheduling)

## Overview

The Appointment Scheduling Module is for scheduling patient appointments and managing provider schedules. This module also allows for managing the patient queue in a clinic. This README contains information primarily pertient to developers. If you are a user looking for user related instruction, navigate to the [Wiki page section](#wiki) of this documentation.

<br>

## File Tree

File tree.
* api	
* omod
* .gitattributes	Lists git attributes that were changed from default.
* .gitignore		Lists files to be ignored when pushing to git
* .travis.yml
* LICENSE.txt
* OpenMRSFormatter.xml
* README.md
* pom.xml	

<br>

## Build Instructions

If your module's file tree is set up correctly [(see section above)](#file-tree), building and packaging the app is a simple process. Navigate to the module's root directory, and run the command `mvn package`. This will package the application according to maven's typical package instructions. The packaged module will be available in /omod/target

<br>

## Wiki

The wiki page for the Appointment Scheduling module contains information more pertinent to users. To view this information, navigate to the following [link](https://wiki.openmrs.org/display/docs/Appointment+Scheduling+Module).

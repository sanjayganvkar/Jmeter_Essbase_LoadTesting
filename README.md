# JmeterEssbase
Essbase LoadTest using JMeter and JSapi
This document provides an example and steps to simulate a load test of Spreadsheet retrievals for Essbase using Apache Jmeter and the
Essbase Java api.

The Use Case assumes that the Tester would like to simulate multiple users retrieving Essbase Data with the Excel-Addin retrieval or Smart view based ones. The Sample.Basic Database has been used to demo the load test.

The steps have been executed for an Essbase Server hosted on a Linux box, with the Jmeter Tests being executed from a Windows box. In case
you have an Essbase server on an Windows environment, You could still use the same steps, except for some of the shell scripts ( which could
also be executed using Unix-Like Utility tools for Dos like cygwin or msys ).

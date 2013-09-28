requirementstags
================

Latex package for adding requirements


This package addes the function to add requirements to your documents.
There is a command for functional and for nonfunctional requirements.

Commands
--------

* \reqlist { requirements}  Command for making a requirements list (only a normal description list but less to write)
* \requirement [Subnumber]{Importance 0-3}{0 = needs to be reviewed / 1 = reviewed}{Requirements text}
* \nfrequirement [Subnumber]{Importance 0-3}{0 = needs to be reviewed / 1 = reviewed}{Requirements text}
* \notClear     <NotClear> 
* \low          <Low>
* \medium       <medium>
* \high         <high>
* \tobereviewed <to be reviewed>
* \reviewed     <reviewed>


Example
-------



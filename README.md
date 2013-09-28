requirementstags
================

Latex package for adding requirements


This package addes the function to add requirements to your documents.
There is a command for functional and for nonfunctional requirements.

Commands
--------

* **\reqlist { requirements}**  Command for making a requirements list (only a normal description list but less to write)
* **\requirement [Subnumber]{Importance 0-3}{0 = needs to be reviewed / 1 = reviewed}{Requirements text}**
* **\nfrequirement [Subnumber]{Importance 0-3}{0 = needs to be reviewed / 1 = reviewed}{Requirements text}**
* **\notClear**     *Output:* < NotClear > 
* **\low   **       *Output:* < Low >
* **\medium**       *Output:* < medium >
* **\high**         *Output:* < high >
* **\tobereviewed** *Output:* < to be reviewed >
* **\reviewed**     *Output:* < reviewed >


Example
-------

\requirement {0}{0}{Test}  
```
     FR 1.0 <notClear> <tobereviewed>
     Test     
```


\requirement[1]{3}{1}{Subrequirement}  
```
     FR 1.1 <high> <reviewed>
     Subrequirement     
```


\nfrequirement{2}{1}{Non functional requirement}

```
     NFR 1.0 <medium> <reviewed>
     Non functional requirement
```


Use
===

To use this package just download it from [here](https://www.dropbox.com/s/0828iz0cgsup07e/requirementstags.sty "here").

After this put it in the same folder as the latex document and add ``` \usepackage{requirementstags} ``` to your document. 


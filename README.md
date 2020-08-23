# DEW - Python Implementation

[![License: MIT License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Twitter Follow](https://img.shields.io/twitter/follow/chandr3w.svg?style=flat-square&logo=twitter&label=Follow)](https://twitter.com/chandr3w)

V0.1.0



The DEW package allows the user to compute the thermodynamic and elastic properties of various aqueous inputs for a general range of 100-1200C and a pressure range of 1.0-60 Kb. It is based on the [DEW spreadsheet](http://www.dewcommunity.org/) and behaves similarly.The DEW package additionally provides integrated support for [SUPCRTBL](https://models.earth.indiana.edu/supcrtbl.php) and can be used to directly import and compare species between the two models.

## Getting Started


### Installing
Install DEW by downloading the DEW file.


## Running DEW

This section provide a basic example on the running of DEW. Because the input fields are interactive, it relies on user input in order to function (which cannot be demonstrated here). [Full documentation](https://chandr3w.github.io/DEW_amchan/) for the class is available externally.

### Download
Download the file "DEW_Folder" from the Github repository.

### Installing DEW
Execute the following line in the same working directory that the DEW files are in:
```
%run DEW.py
```
This will execute the imports of packages and the initialization of the model. If you wish to change base parameters please see the documentation. The only non-standard package that DEW is dependent on is the "pandas" package, however a full list of dependencies is included below.




### Range of validity
Certain equations within DEW are valid to certain values (as are the properties of specific mineral species). For more information please see the [DEW website](http://www.dewcommunity.org/)



## References
#TODO

## Authors

* **Andrew Chan** - *Div. of Geological and Planetary Sciences, California Institute of Technology, Pasadena, CA, USA 91125* 
* **Mohit Melwani Daswani** - *Group 3226 (Planetary Interiors and Geophysics). NASA Jet Propulsion Laboratory, California Institute of Technology, Pasadena, CA 91109
* 
* **Steven Vance** - *Group 3226 (Planetary Interiors and Geophysics). NASA Jet Propulsion Laboratory, California Institute of Technology, Pasadena, CA 91109
* 

## Change log

### Changes since 0.1.0


### Planned updates
-
- 


## License

This project is licensed under the MIT License :

Copyright (c) 2020, A. Chan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

This work was produced with the financial support provided by the NASA Jet Propulsion Laboratory, the California Institute of Technology Summer Undergraduate Research Fellowship program, and the Caltech Assocaites.


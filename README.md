

# Alzheimer's Disease Cell - Cell Interactome 

## Overview
This repository includes all my work for the AD cell-cell interactome project.

## Repository Architecture

The repository is split into seven main directories, many of which have subdirectories. Within each directory is a `README.md` file which summarizes the purpose of that directory as well as some examples where necessary. Each section is briefly described below. 

### **`code`** 
Where all of the *executed* code lives. This includes pipelines, scripts, and figure files. 
 * **`processing`**: Any code used to *transform* the data into another type lives here. This also includes markdown files describing the experimental set-up.
 * **`analysis`**: Any code to to *draw conclusions* from an experiment or data set. 
 * **`exploratory`**: A sandbox with a record of different approaches to transformation, interpretation, cleaning, or generation of data.
 * **`figures`**: Any code used to generate figures.

### **`data`** 
All raw data collected from experiments as well as copies of the transformed data from your processing code. This folder only contains small data files (<50 MB). 

### **`miscellaneous`** 
Files that may not be code, but are important for reproducibility of my findings.
* **`protocols`**: A well annotated and general description of experiments.  
* **`materials`**: Information regarding the materials used in experiments or data generation. 
* **`software details`**: Information about the computational environment that are necessary for others to execute my code. 

### **`tests`** 
All test suites for code, especially from the software module. 

### **`software_module`** 
Custom code that is *not* executed directly, but is called from files in the `code` directory.

### **`templates`** 
Files that serve as blank templates that document the procedures taken for each experiment, simulation, or analysis routine. 

## License
The software herein is licensed under a standard MIT license, which reads as follows:

```
MIT License

Copyright (c) 2022 Rahma Elsiesy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
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
```

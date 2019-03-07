# Global-Characterization-Data-Processing-Site V0.1 *beta*
 This repository is a source code depo for the manuscript "Rapid Global Characterization of Human IgG1 under Oxidative Stresses "

### Introduction:

This is a universally applicable customized program for protein post-translational modification (PTM) data processing. It accepts raw data output from Skyline (https://skyline.ms/), plots modification trends for peptides, generates sortable and downloadable modification tables, and produces Jmol code for 3-dimentional structural models of the analyzed protein.  

![alt text](https://github.com/YaoChen1/Hello-world/blob/master/work%20flow.png)

### Video Tutorial

[Tutorial: How to use Global Characterization Data Processing Site for rapid modification analysis](https://youtu.be/atwfpfsiB5w)

### Running environment
- Python 3.6 or higher
- Microsoft Windows 7 or higher
- Any Browser other than Microsoft Edge

### Installation

Before running the code contained in "Automatic Data Processing", install the following packages:
```
pip install dash==0.36.0
pip install dash-html-components==0.13.5 
pip install dash-core-components==0.43.0
pip install dash_table_experiments
pip install dash-table==3.1.11
pip install plotly
pip install pandas
pip install statistics
pip install matplotlib
```

### Skyline Templates

Skyline Templates of all four conditions described in the manuscript is uploaded in this repository.
```
https://github.com/YaoChen1/Global-Characterization-Data-Processing-Site/tree/master/Skyline%20data%20processing%20template
```

### Skyline Report Template

Generate the Skyline report using the following format to import to Global Characterization Data Processing Site
```
https://github.com/YaoChen1/Global-Characterization-Data-Processing-Site/blob/master/Skyline%20data%20processing%20template/Skyline%20Report%20template.skyr
```

### Testing Data

The raw data described in the manuscript are uploaded in this repository. 
```
https://github.com/YaoChen1/Global-Characterization-Data-Processing-Site/tree/master/H2O2       # mAb incuabted with 3% H2O2
https://github.com/YaoChen1/Global-Characterization-Data-Processing-Site/tree/master/metal      # mAb incubated with leachable metals
https://github.com/YaoChen1/Global-Characterization-Data-Processing-Site/tree/master/metal_H2O2 # mAb incubated with H2O2 and metals
https://github.com/YaoChen1/Global-Characterization-Data-Processing-Site/tree/master/control    # mAb non-stressor control
```

### Supplemental Recources

- Jmol is needed for visualizaiton of the 3-D molecular model of modified protein 
   - http://jmol.sourceforge.net/
- Download the protein X-ray crystallography data from Protein Data Bank
   - https://www.rcsb.org/

### Please don't hesitate to contact the author

- Ask questions about the project or provide suggestions on how to make the Global Characterization Site easier to use
  - chenyao.emporia@gmail.com
- This is a one person project and I have my day job, apologies ahead for any delays ^_^

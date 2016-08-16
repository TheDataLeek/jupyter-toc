# Jupyter TOC Generator

I hate having to manually generate a table of contents for a large notebook that I have. This tool fixes that...

## Example

```bash
┬─[william@fillory:~/Dropbox/Projects/jupyter_toc]─[03:33:57 PM]
╰─>$ ./generate_toc.py ~/Dropbox/classwork/hoeferlab/linefit/01\ Line\ Fitting.ipynb 
-----------------------------------------------------------------------
/home/william/Dropbox/classwork/hoeferlab/linefit/01 Line Fitting.ipynb
# Table of Contents
1. [TOC](#toc)
2. [Data Info](#data-info)
3. [Load Datafile](#load-datafile)
    4. [Plotting](#plotting)
5. [Numeric Curve Determination](#numeric-curve-determination)
6. [Linear Regression with Model](#linear-regression-with-model)
    7. [From Peter Wills](#from-peter-wills)
    8. [Code](#code)
-----------------------------------------------------------------------
```

## Usage

```bash
./generate_toc.py <name of notebook>
```

and then just copy the output.

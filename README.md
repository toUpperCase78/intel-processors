# intel-processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/SVqLYBK/intel-new-logo.png)

As a data scientist, here is one of my dataset project, **Intel Processors**. Thanks to these datasets altogether, one can realize how computers' central processing units have evolved within the last few decades, with regards to many features!

This repo contains the datasets that involve all processors from **Core**, **Pentium**, **Celeron**, **Xeon**, **Xeon Phi**, **Itanium**, **Atom** and **Quark SoC** series Intel has ever manufactured. 

## Source

All these info in the dataset is based on Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

## Current Status

Now the datasets are being updated to **version 1.5** to contain new features _Threads, Lithography and TDP,_ and new processors launched until **November 2021**, including **12th Generation Intel Core Processors**!

Older datasets (such as v1.1 and some v1.2) will still exist and be moved to their specific folders for archive.

In the meantime, preparations are being made for new analyses to be published here with up-to-date information.

## Features

Current datasets contain these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Cores`: The number of cores the processor has
- `Threads`: The number of threads the processor has (new in v1.5)
- `Lithography (nm)`: The number in nm, indicating the technology for the size of the features integrated on semi-conducting circuit (new in v1.5)
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach, especially while on full load (in GHz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in GHz)
- `TDP (W)`: The value of Thermal Design Power in Watts (new in v1.5)
- `Cache (MB)`: The total cache capacity of the processor (in MB)
- `Cache Info`: Additional info about the cache
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

## Analyses

The 1st part of **Intel Core processors'** analyses is avaliable for dataset **version 1.1**. Check the related notebook file (.ipynb) to see them all!

_Hopefully, more analyses for the other types of processors will be included here!_

## Future Plans

**I'm aware that some important features are missing in the dataset!** That's why in the future versions, I'm planning to include more features for better and more accurate analyses and get these processors more distinguishable from each other (e.g. # of threads, architecture name, litography, socket type, TDP)...

Moreover, this repo has been in silence for more than 1 year, hence my short-term plan is to keep it alive with up-to-date information!

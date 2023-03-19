# intel-processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/SVqLYBK/intel-new-logo.png)

Hello there! As a data scientist, here is my dataset project: **Intel Processors**. Thanks to these datasets altogether, one can realize how computers' central processing units have evolved within the last several decades, with regards to many features!

This repo contains the datasets that involve all processors from **Core**, **Pentium**, **Celeron**, **Xeon**, **Xeon Phi**, **Itanium**, **Atom** and **Quark SoC** series Intel has ever manufactured. 

## Source

All these info in the dataset is based on Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

## Current Status

Now the datasets are being updated to **version 1.6** to contain new features _Threads, Lithography and TDP,_ and new processors launched until **1st Quarter of 2023**, including **13th Generation Intel Core Processors**!

Older datasets (such as v1.1 and some v1.2) will still exist and be moved to their specific folders for archive.

In the meantime, new comprehensive analyses are on the way to be published here with up-to-date information.

## Features

The latest version (1.6) of current datasets contain these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Cores`: The number of cores the processor has
- `Threads`: The number of threads the processor has
- `Lithography (nm)`: The number in nm, indicating the technology for the size of the features integrated on semi-conducting circuit
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach, especially while on full load (in GHz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in GHz)
- `TDP (W)`: The value of Thermal Design Power in Watts
- `Cache (MB)`: The total cache capacity of the processor (in MB)
- `Cache Info`: Additional info about the cache
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

## Analyses

The 1st part of **Intel Core processors'** analyses is avaliable for dataset **version 1.1**. Check the related notebook file (.ipynb) to see them all!

_Hopefully, more analyses for the other types of processors will be included here!_

## Future Plans

**I'm aware that this repo has been in silent for more than 2 years!** In order to make it alive, all datasets are being updated to version 1.6 specifications described above.

After that, analyses will be performed in order to better understand the evolution of these processors, which is definitely in my wishlist!

Then, depending on the interest of this repo, more features might be included for detailed specs for any processors. And you may first try to find your processor here with necessary details...

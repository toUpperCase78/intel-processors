# intel-processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/VTr09cf/intel-logo.png)

As a data scientist, this is my another dataset project about **Intel processors**. Thanks to these datasets altogether, one can realize how computer processors have evolved within the last few decades, with regards to many features!

This repository contains the datasets that involve all processors from **Core**, **Pentium**, **Celeron**, **Xeon**, **Itanium**, **Atom** and **Quark SoC** series Intel has ever manufactured. 

## Current Status

Everything is being updated nowadays for **version 1.2** to contain all these processors until **October 2021**.

## Source

All these info in the dataset is based on Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

## Features

Current datasets contain these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Cores`: The number of cores the processor has
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach, especially while on full load (in GHz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in GHz)
- `Cache (MB)`: The total cache capacity of the processor (in MB)
- `Cache Info`: Additional info about the cache
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

Because these datasets (v1.1) are more than 13 months old, new processors from the latest or existing generations are being added right now; thus versions will be numbered as "1.2". Older ones will still exist and be moved for archive.

## Analyses

The 1st part of **Intel Core processors'** analyses is avaliable for dataset **version 1.1**. Check the related notebook file (.ipynb) to see them all!

_Hopefully, more analyses for the other types of processors will be included here!_

## Future Plans

**I'm aware that some other necessary features are missing in the dataset!** That's why in the future versions, I'm planning to include more features for better and more accurate analyses and get these processors more distinguishable from each other (e.g. # of threads, architecture name, litography, socket type, TDP)...

Moreover, this repo has been in silence for more than 1 year, hence my short-term plan is to keep it alive with up-to-date information!

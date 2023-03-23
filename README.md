# intel-processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/SVqLYBK/intel-new-logo.png)

Hello there! As a data scientist, here is my dataset project: **Intel Processors**. Thanks to these datasets altogether, one can realize how computers' central processing units have evolved within the last several decades, with regards to many features!

This repo contains the datasets that involve all processors from **Core**, **Pentium**, **Celeron**, **Xeon**, **Xeon Phi**, **Itanium**, **Atom** and **Quark SoC** series Intel has ever manufactured. 

All these info in the datasets are obtained from Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

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

### Assumptions

There are some assumptions for the preparation of these datasets. Please keep them in mind while inspecting them:

- For assessing `TDP` of the processors, normally **the base value** is taken. If base value is not avaiable in the original spec sheet, but configurable TDP-up and TDP-down frequency values are given instead, the **TDP-up** value is taken.
- For some processors having both performance and efficiency cores/threads together, their performance-core base frequency is considered in the `Base Freq.`, if the individual base frequency is not found in the spec sheet.
- In `Integrated Graphics` column, the name for a few processors migh appear as 'Name Unknown'. This means the processors has integrated graphics, but its name was not indicated in the spec sheet of the original source.

## Analyses

There is only one data analyses available so far, about **Intel Core Processors** (done for v1.1) which was published more than 2 years ago. Anyway, you can click on the related notebook file (.ipynb) to see the details.

_Hopefully, more analyses for the other types of processors will be included here!_

## Some Beneficial Infos

In the last few generations, many Intel processors have letters (suffixes) that come after the numbers, indicating their specialties. This list below might help you understand the meanings of these letters:

| Suffix | Meaning |
|--------|---------|
| K | High-performance, unlocked |
| F | Requires discrete graphics |
| S | Special edition |
| T | Power-optimized lifestyle |
| X/XE | Highest performance, unlocked |
| HX | Highest performance, all SKUs unlocked |
| HK | High performance, unlocked |
| H | High performance |
| P | Performance for thin & light |
| U | Power efficient |
| Y | Extremely low-power efficient |
| G1-G7 | Graphics level (processors with newer integrated graphics technology) |
| E | Embedded |
| UE | Power efficient, embedded |
| HE | High performance, embedded |
| UL | Power efficient, in LGA package |
| HL | High performance, in LGA package |

## Future Plans

**I'm aware that this repo has been in silent for more than 2 years!** In order to make it alive, all datasets are being updated to version 1.6 specifications described above.

After that, analyses will be performed in order to better understand the evolution of these processors, which is definitely in my wishlist!

Then, depending on the interest of this repo, more features might be included for detailed specs for any processors. And you may first try to find your processor here with necessary details...

# Intel Processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/SVqLYBK/intel-new-logo.png)

Hello there! As a data science enthusiast, here is my dataset project about **Intel Processors**. Thanks to these datasets altogether, one can realize how computers' central processing units (CPUs) have evolved within last two or three decades, with regards to many specifications along the way!

This repo contains the datasets that involve all processors from **Core**, **Core Ultra**, **Pentium**, **Celeron**, **Xeon**, **Xeon Phi**, **Itanium**, **Atom**, **Quark SoC** and other uncategorized series Intel has ever manufactured. 

All these info in the datasets are obtained from Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html), by accessing each processor page by page and carefully inspecting each corresponding feature.

## Current Status

Nowadays, the datasets are being updated to **Version 1.8** to contain these new features: _Code Name, Max Memory Size, Memory Types & Max Memory Speed._ This will include new processors which are launched until **1st Quarter of 2024**, typically including the era of **14th Generation Intel Core Processors**!

Older datasets (v1.1, v1.2, and later v1.6) will still exist and be found under their specific folders for archiving.

In the meantime, I'm aware that it's been a long time since I didn't perform any analyses on these processors. Certainly, I'll upload them here once they're ready in the best possible period.

## Features

The latest version **(1.8)** of current datasets contain these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Code Name`: Indicates the architecture name for which the processor was designed under
- `Cores`: The number of cores the processor has
- `Threads`: The number of threads the processor has
- `Lithography (nm)`: The number in nanometer (nm), indicating the technology for the size of the features integrated on semi-conducting circuit
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach, especially while on full load (in gigahertz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in gigahertz)
- `TDP (W)`: The value of Thermal Design Power in Watts
- `Cache (MB)`: The total cache capacity of the processor (in megabytes)
- `Cache Info`: Additional info about the cache
- `Max Memory Size (GB)`: Refers to the maximum memory capacity supported by the processor (in gigabytes)
- `Memory Types`: Shows the types of memories supported by the processor
- `Max Memory Speed (MHz)`: Indicates the maximum memory speed supported by the processor (in megahertz)
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

### Assumptions

There are some assumptions for the preparation of these datasets. Please keep them in mind while inspecting them:

- For assessing `TDP` of the processors, normally **the base value** is taken. If base value is not avaiable in the original spec sheet, but configurable TDP-up and TDP-down frequency values are given instead, the **TDP-up** value is taken.
- For some processors having both performance and efficiency cores/threads together, their performance-core base frequency is considered in the `Base Freq.`, if the individual base frequency is not found in the spec sheet.
- In `Integrated Graphics` column, the name for a few processors migh appear as `Name Unknown`. This means the processor has integrated graphics, but its name was not indicated in the spec sheet of the original source.
- If there is only one type of supported memory and its related speed value, then the value is written for `Max Memory Speed (MHz)`.

## Analyses

There is only one data analysis available so far, about **Intel Core Processors** (done for v1.1) which was published more than 3 years ago. Anyway, you can click on the related notebook file (.ipynb) to see the details.

_I'm totally aware that no other analyses have been carried out yet! Hopefully, more of them for up-to-date datasets will be included here in the best period possible!_

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

**This repo has been in silence for a long time!** In order to make it alive, all datasets are being updated to version 1.8 specifications described above. Then, I'll move on to analyses for presenting more insights!

Depending on the interest of this repo, more features might be included for detailed specs for any processors. Naturally, you may try to find your processor here with necessary details!

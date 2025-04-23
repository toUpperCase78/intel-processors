# Intel Processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/SVqLYBK/intel-new-logo.png)

Hello there! As a data science enthusiast, here is my dataset project about **Intel Processors**. Thanks to these datasets altogether, one can realize how computers' central processing units (CPUs) have evolved within last two or three decades, with regards to many attributes along the way!

This repo contains the datasets that involve all processors from **Core**, **Core Ultra**, **Pentium**, **Celeron**, **Xeon**, **Xeon Phi**, **Itanium**, **Atom**, **Quark SoC** and other uncategorized series Intel has ever manufactured. 

All these info in the datasets are obtained from Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html), by accessing each processor page by page and carefully inspecting each corresponding feature.

## Current Status

After a long break, all the datasets are being updated to **Version 1.9**; containing these new features: 

- Vertical Segment
- Max Memory Channels
- Sockets Supported
- Max Operating Temperature

Of course, the new version includes new processors which are launched until **1st Quarter of 2025**, typically including the latest series of **Intel Core** and **Intel Core Ultra** processors!

Older datasets (v1.1, v1.2, v1.6, v1.8) will still exist and can be found under their specific folders for archiving purposes.

In the meantime, there was still no comprehensive analysis on these processors yet, and the existing one was published 5 years ago! I'll perform the analyses once the editing of these datasets from the latest version was completed!

## Features

The latest version **(1.9)** contain these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Code Name`: Indicates the architecture name for which the processor was designed under
- `Vertical Segment`: Indicates which computer segment the processor is convenient for usage
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
- `Max Memory Channels`: Indicates the number of memory channels to the bandwidth operation
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists
- `Sockets Supported`: The component supported by the processor for providing the mechanical and electrical connections between the processor and motherboard
- `Max Operating Temp. (°C)`: The maximum temperature allowed for operations

### Assumptions

There are some assumptions for the preparation of these datasets. Please keep them in mind while inspecting:

- For assessing `TDP` of the processors, normally **the base value** is taken. If base value is not avaiable in the original spec sheet, but configurable TDP-up and TDP-down frequency values are given instead, the **TDP-up** value is taken.
- In the latest generation of processors, the value of Maximum Turbo Power is taken for `TDP` value, instead of Base Power.
- For some processors having both performance and efficiency cores/threads together, their performance-core base frequency is considered in the `Base Freq.`, if the individual base frequency is not found in the spec sheet.
- In `Integrated Graphics` column, the name might appear as `Name Unknown` for several processors. This means the processor has integrated graphics, but its name was not indicated in the spec sheet of the original source.
- If there is only one type of supported memory type and only one speed value, then this speed value is filled for `Max Memory Speed (MHz)`.
- When maximum operating temperature is not found, but instead, T-Junction or T-Base values are presented, these values are used to represent `Max Operating Temp. (°C)`. (If both of them are available, the higher value is taken)

## Contributions

Here, below I'll list the processors which didn't exist in Intel's website and have been contributed by other people for inclusion. Many thanks in advance!

| Category | Processor | Contributed By |
|----------|-----------|----------------|
| Intel Xeon Processors | Xeon Platinum 8370C | mvarian |
| Intel Xeon Processors | Xeon Platinum 8272CL | mvarian |
| Intel Xeon Processors | Xeon Platinum 8171M | mvarian |

## Analyses

There is only one data analysis available so far (published 5 years ago), about **Intel Core Processors** (for v1.1). Nevertheless, you can click on the related notebook file (.ipynb) to see the details for what I'd done.

_I'm totally aware that still no other analyses have been carried out yet! Hopefully, these analyses with relation to the recent datasets will be included here in the best period possible!_

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

**This repo has been in silence for a long time!** In order to make it alive, all datasets are being updated to version **1.9** specifications described above. Then, I'll move on to analyses for presenting insights!

Depending on the interest of this repo, more features might be included for detailed specs for any processors. Naturally, you may try to find your processor here with necessary details!

Last but not least, if you'd like to contribute by the addition of other processors that weren't seen in Intel's web site, just open a pull request, write down the processors including their necessary features and the reference site where you've taken the data.

# intel-processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/VTr09cf/intel-logo.png)

Being enthusiast for data analysis, here's my another dataset project which is about **Intel processors**. Thanks to that, one can realize how processors have evolved within the last few decades, in terms of many criterions!

This repository contains the datasets that involve all processors from **Core**, **Pentium**, and **Celeron** series Intel has ever manufactured until **January 2020**. I know this is not limited to just these type of processors; thus, in the future, other types of processor families will be added here as individual datasets (such as Xeon, Itanium, Atom).

_Hopefully, I'm going to perform data analysis over these processors and present them here._

All these info in the dataset is based on Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

## Features

The 1st version of the dataset contains these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach, especially while on full load (in GHz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in GHz)
- `Cache (MB)`: The total cache capacity of the processor (in MB)
- `Cache Info`: Additional info about the cache
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

**I'm aware that some other necessary features are missing in the dataset!** That's why in the next version (marked as v2), I'm going to include more features in order to make better analysis and get these processors more distinguishable from each other (e.g. # of threads, architecture name, litography, socket type, TDP)...

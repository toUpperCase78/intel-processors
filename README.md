# intel-processors

**Datasets for All Manufactured Intel Processors**

![Intel Logo](https://i.ibb.co/VTr09cf/intel-logo.png)

Being enthusiast for data science, this is my another dataset project which is for analyzing **Intel processors**. Thanks to these datasets altogether, one can realize how computer processors have evolved within the last few decades, in terms of many criterions!

This repository contains the datasets that involve all processors from **Core**, **Pentium**, **Celeron**, **Xeon**, **Itanium**, **Atom** and **Quark SoC** series Intel has ever manufactured until **September 2020**.

_Hopefully, I'm going to perform data analysis over these processors and present them here soon._

All these info in the dataset is based on Intel ARK [website](https://ark.intel.com/content/www/tr/tr/ark.html).

## Features

Current version of the datasets contains these features below:

- `Product`: Name of the manufactured processor
- `Status`: Indicates the current status of the processor
- `Release Date`: Shows when the processor has been released to PC manufacturers or individual users
- `Cores`: The number of cores the processor has
- `Max. Turbo Freq. (GHz)`: The maximum clock speed the processor can reach, especially while on full load (in GHz)
- `Base. Freq. (GHz)`: The base clock speed of the processor (in GHz)
- `Cache (MB)`: The total cache capacity of the processor (in MB)
- `Cache Info`: Additional info about the cache
- `Integrated Graphics`: Shows the integrated graphic component used by the processor if exists

Because these datasets are more than 6 months old, new processors from the latest or existing generations have been added; thus versions were numbered as "1.1".

## Analyses

The 1st part of Intel Core processors' analyses is finally avaliable. Check the related IPython file to see them all!

## Future Plans

**I'm aware that some other necessary features are missing in the dataset!** That's why in the next version (will be marked as v2), I'm planning to include more features for better and more accurate analyses and get these processors more distinguishable from each other (e.g. # of threads, architecture name, litography, socket type, TDP)...

experimental models for DeJPEG

models planned are:

https://openmodeldb.info/models/1x-DitherDeleterV3-Smooth

https://openmodeldb.info/models/1x-Bandage-Smooth

https://openmodeldb.info/models/1x-DeEdge

https://openmodeldb.info/models/1x-UnResizeOnly-RCAN (unconverted)

https://openmodeldb.info/models/1x-GainRESV4

use [this](https://github.com/jeeneo/dejpeg/releases/tag/v2.6.0-debug) prerelease version

----

if you would like to request a model, you can look at [OpenModelDB](https://openmodeldb.info/?t=scale%3A1)'s list for `1x` models

2x, 4x, etc, ("upscaling" models) wont be officially supported by DeJPEG (at it's current stage) as there exists plenty of "super res AI enhancers" available and so many models that "upscale" with many differing results of what is "good", and requires more processing power and consumption for what it's worth, i'd recommend a desktop anyway since GPUs are better at that than phones.

Nevertheless you can always fork the app and add your own functionality, since this is just a UI for the ONNX runtime.

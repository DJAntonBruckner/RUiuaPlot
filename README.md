# RUiuaPlot
Uses [RUiua](https://github.com/DJAntonBruckner/RUiua) to implement basic plots. See "example.ua" for an example of how to use it.

## Requirements
Same as RUiua: R and Rscript in your `PATH`. Uses Uiuas git module functionality to automatically provide RUiua.

## Usage
Import the module using something like `Plot ~ "git: github.com/DJAntonBruckner/RUiuaPlot"`

Then, use `NewWindow` to create a new plot window. You then can plot stuff
using `SimplePlot`, `Plot` and `PlotFunction`. If you want multiple plots,
you can call `PartitionWindow` first. Use `WaitUntilWindowsClosed` to wait
until all plots are closed, then exit R using `StopR`.
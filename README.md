# Grid Studies: Pure Data

Pure Data (Pd) is a visual programming language developed by Miller Puckette in the 1990s for creating interactive computer music and multimedia works. While Puckette is the main author of the program, Pd is an open source project with a large developer base working on new extensions. (source: [Wikipedia](http://en.wikipedia.org/wiki/Pure_Data))

- Download Pd: [puredata.info/](https://puredata.info/downloads/pure-data)
- Install serialosc: [https://monome.org/docs/serialosc/setup](/docs/serialosc/setup)
- Download the `[monome-device]` object + code examples here: [files/grid-studies-pd.zip](https://monome.org/docs/grid/studies/pd/files/grid-studies-pd.zip)

### Required externals

In order to connect grid to Pd and run these studies, you'll need to install a few externals and add them to your search path.

From the toolbar, navigate to `Help > Find externals` and install:

- `cyclone`: a library of Max/MSP-style objects
- `osc`: enables Open Sound Control communication between grids + Pd

Once both are installed, navigate to `Pd > Preferences > Edit Preferences` (macOS) or `File > Preferences > Edit Preferences` (Win/Linux), click on *New...* and navigate to the directory where each external exists. Click *Choose* / *Select Folder* to add each external's folder. The Preferences window should now resemble:

![](https://monome.org/docs/grid/studies/pd/images/pd-preferences.png)

Then, place the `monome-device` folder that's included in the zip file above into your Pd externals folder. We don't need to explicitly add it to the search path.

[Full study text at monome.org](https://monome.org/docs/grid/studies/pd/)

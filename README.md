# ADR-Template
An Item Template to help record architecturally significant decisions within Visual Studio.

The format follows Michael Nygard's proposal for [Architecture Decision Records](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions). The template text is from the [presentation](https://www.youtube.com/watch?v=41NVge3_cYo) and [slide deck](https://resources.sei.cmu.edu/asset_files/Presentation/2017_017_001_497746.pdf) of Micheal Keeling.

## Install the Item Template
The Get Started section explains how to manually install the item template. Eventually, you will be able to install using the Visual Studio Marketplace.

## Get Started
1. Clone the repo
2. Set the VSIXProject as the Startup Project
3. Build
4. You have two options for testing locally
   * Manually install the Item Template
     * Copy the compressed ADRItemTemplate file from the ItemTemplate\bin directory
     * Paste it into the Visual Studio ItemTemplates directory. The default location is %userprofile%\Documents\Visual Studio 2017\Templates\ItemTemplates
     * Restart Visual Studio
     * You should see the ADR item template in the __Add New Item__ dialog
   * Debug through an experimental instance of Visual Studio
     * Press F5. The experimental instance of Visual Studio appears
     * You should see the ADR item template in the __Add New Item__ dialog
     
## Additional Resources for Architecture Decision Records
[Real-life example](https://github.com/alphagov/govuk-aws/tree/master/doc/architecture)

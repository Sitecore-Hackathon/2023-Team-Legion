![Hackathon Logo](docs/images/hackathon.png?raw=true "Hackathon Logo")

# Sitecore Hackathon 2023

## Team name

⟹ Team Legion

## Category

⟹ Best enhancement to SXA Headless

## Description

⟹ Sitecore SXA module: RenderingConverter.
Our module helps to migrate from old SXA controller rendering items to new headless json rendering items.

Users can start tranforming old SXA renderings by clicking on "Convert SPX Module To Headless"

![image](https://user-images.githubusercontent.com/69300131/222927731-08c424c8-34e5-44c7-bace-3e6ce7e309e4.png)

This will start process of choosing folder for new transformed rendering.

![image](https://user-images.githubusercontent.com/69300131/222927798-b861006c-2ace-485b-9f66-aa55e415a54b.png)

Newly created Json Rendering will be created in chosen directory with inherited field values from old one.

![image](https://user-images.githubusercontent.com/69300131/222927875-5572b19d-7128-4ea2-b3b7-bf82c0cf9f57.png)

Basically, this module helps:
-   Convert SXA controller renderings to Headless Json rendering
-   Helps to extend standard Headless Experience Accelerator with renderings from Sitecore Experience Accelerator by adding small migrating utility.

## Pre-requisites and Dependencies

-   Sitecore XM 10.3
-   .NET Core 3.1 SDK
-   .NET Framework 4.8 SDK
-   Sitecore PowerShell Extensions 6.4
-   Sitecore Headless Rendering 21.0.0
-   Sitecore Experience Accelerator 10.3.0

## Installation instructions

> - Go to Development Tools -> Installation Wizard.
> - Upload the [package](/docs/ModuleConvertor.zip).
> - Click on Install and wait for the installation process to finish.
> - Restart the Sitecore client after installation is finished

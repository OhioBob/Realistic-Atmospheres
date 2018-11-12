# Realistic-Atmospheres

This mod is licensed by Creative Commons Attribution-NonCommercial-NoDerivs
CC BY-NC-ND

## Changelog
## v1.3.0

* Atmospheres have been completely redone with new pressure and temperature curves.
* Sun: Custom atmosphere deleted, reverts to stock (was causing a visual artifact when zoomed in on sun).
* Kerbin: Stylistic change to pressureCurve, atmosphere is effectively unchanged.
* Eve: Sea level pressure increased to 10 atm, molecular weight reduced, temperatures revised, height now 60 km.
* Duna: Surface pressure unchanged, temperatures and upper atmosphere revised, height now 75 km.
* Jool: Lower atmosphere (<10 km) rapidly increases to crushing pressure and high temperature, upper atmosphere revised, height now 550 km.
* Laythe: Surface pressure unchanged, temperatures and upper atmosphere revised, height now 55 km.
* Tylo: Atmosphere added, surface pressure 0.2 atm, height 40 km, includes visual changes and scatterer support.
* timewarpAltitudeLimits and flyingAltitudeThreshold revised where applicable to match new atmosphere heights.

## Description

Realistic Atmospheres modifies the atmospheres of all planets and moons to conform to a more lifelike model. Temperature-height profiles are based on real life celestial bodies of similar type. Pressure-height models have been developed consistent with each celestial body's physical characteristics, and using real life gas laws. Models have been developed at real scale, and then scaled down to better fit the smaller size of the KSP universe.

While some properties of the original atmospheres have been preserved, Realistic Atmosphere is a complete makeover. Don’t expect what you know about the stock game to exist in Realistic Atmospheres. You may encounter a planet's atmosphere much sooner or later than you are accustomed to, and with different behavior, so beware. 

## Installation Instructions

1. Download the third party mod [Kopernicus](https://github.com/Kopernicus/Kopernicus/releases/). The Kopernicus version number must match the KSP version number.

2. Install by copying from [Kopernicus Download]\GameData\ to [KSP]\GameData\ the following folders and files:  
   * Kopernicus
   * ModularFlightIntergrator
   * ModuleManager

3. Download Realistic Atmospheres v1.3.0

4. Copy from [RealisticAtmospheres Download]\GameData\ to [KSP]\GameData\ the folder RealisticAtmospheres and all its contents.

## Optional

1. If you want Tylo to remain an airless body, delete its atmosphere by copying the file DeleteTyloAtmo.cfg to GameData\RealisticAtmospheres\.

2. If you want Eve to retain its original 5-atmosphere surface pressure, copy the file EasierEve5atm.cfg to GameData\RealisticAtmospheres\.


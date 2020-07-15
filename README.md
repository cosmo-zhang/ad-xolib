
# ad-xolib (OpenScenario & OpenDrive Parser in C++ & Python)
C++ library for Parsing OpenScenario (1.0.0) & OpenDrive format files (1.6) with Python bindings for 3.+ 

## Introduction <a name="introduction"></a>

This repository provides a library for reading ASAM's OpenStandards OpenScenario & OpenDrive Data files, the parsing conforms to

[ASAM OpenDRIVE 1.6
Specification](https://www.asam.net/index.php?eID=dumpFile&t=f&f=3495&token=56b15ffd9dfe23ad8f759523c806fc1f1a90a0e8)

[ASAM OpenScenario 1.0.0
Specification](https://www.asam.net/index.php?eID=dumpFile&t=f&f=3496&token=df4fdaf41a8463e585495001cc3db3298b57d426)

![Image of asam-logo](https://www.asam.net/typo3conf/ext/asam_cms/Resources/Public/Images/asam-logo.svg)

## License <a name="license"></a>

This software library is provided under the MIT open-source license: https://opensource.org/licenses/MIT.

## Inspiration <a name="inspiration"></a>


- https://github.com/carla-simulator/map
- https://github.com/esmini/esmini.git


## Getting started <a name="started"></a>
The project is compiled with c++14 enabled compiler, choose your stack accordingly .

#### Build from Source <a name="build"></a>

```bash
git clone https://github.com/javedulu/ad-xolib.git
git submodule update --init --recursive 
mkdir build
cd build
cmake . -B build
cmake . --target build
```

## Alternatives <a name="alternatives"></a>
- [https://github.com/JensKlimke/odrparser](https://github.com/JensKlimke/odrparser)- OpenDrive 1.5 
- [https://github.com/DLR-TS/xodr](https://github.com/DLR-TS/xodr) - OpenDrive 1.4
- [https://github.com/pyoscx/pyoscx](https://github.com/pyoscx/pyoscx) - pyoscx
- [https://github.com/carla-simulator/scenario_runner](https://github.com/carla-simulator/scenario_runner) - Scenario Runner
- [https://github.com/MrMushroom/CarlaScenarioLoader](https://github.com/MrMushroom/CarlaScenarioLoader) - CarlaScenarioLoader

## Contributing <a name="contributing"></a>
Contributions are very welcome!

## CAUTION <a name="caution"></a>

The <b>{py}xo[sc,dr].[h,cxx]</b> files are autogenerated, in case you require any modifications, please send a request with the details. They will be updated regularly.

Don't edit them directly .

## Coming Soon <a name="future"></a>
 - Save to xo[dr,sc] from c++  
 - Print to console - support ostream c++ 
 - ~~Python binding [XODR]~~ DONE
 - ~~Bump the format to 1.6 of OpenDrive~~ DONE
 - ~~OpenScenario c++ parsing based on OpenScenario-1.0~~ DONE
 - ~~Python binding for OpenScenario [XOSC]~~ DONE
 - OpenScenario Manager to manage simulations with External Simulator's 
 - OpenScenario 2.0 [Awaiting specification ] 

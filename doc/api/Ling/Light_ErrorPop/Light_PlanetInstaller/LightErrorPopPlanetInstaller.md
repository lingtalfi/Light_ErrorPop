[Back to the Ling/Light_ErrorPop api](https://github.com/lingtalfi/Light_ErrorPop/blob/master/doc/api/Ling/Light_ErrorPop.md)



The LightErrorPopPlanetInstaller class
================
2020-06-01 --> 2021-06-25






Introduction
============

The LightErrorPopPlanetInstaller class.



Class synopsis
==============


class <span class="pl-k">LightErrorPopPlanetInstaller</span> extends [LightBasePlanetInstaller](https://github.com/lingtalfi/Light_PlanetInstaller/blob/master/doc/api/Ling/Light_PlanetInstaller/PlanetInstaller/LightBasePlanetInstaller.md) implements [LightServiceContainerAwareInterface](https://github.com/lingtalfi/Light/blob/master/doc/api/Ling/Light/ServiceContainer/LightServiceContainerAwareInterface.md), [LightPlanetInstallerInit2HookInterface](https://github.com/lingtalfi/Light_PlanetInstaller/blob/master/doc/api/Ling/Light_PlanetInstaller/PlanetInstaller/LightPlanetInstallerInit2HookInterface.md) {

- Inherited properties
    - protected [Ling\Light\ServiceContainer\LightServiceContainerInterface](https://github.com/lingtalfi/Light/blob/master/doc/api/Ling/Light/ServiceContainer/LightServiceContainerInterface.md) [LightBasePlanetInstaller::$container](#property-container) ;

- Methods
    - public [init2](https://github.com/lingtalfi/Light_ErrorPop/blob/master/doc/api/Ling/Light_ErrorPop/Light_PlanetInstaller/LightErrorPopPlanetInstaller/init2.md)(string $appDir, Ling\CliTools\Output\OutputInterface $output, ?array $options = []) : void
    - public [undoInit2](https://github.com/lingtalfi/Light_ErrorPop/blob/master/doc/api/Ling/Light_ErrorPop/Light_PlanetInstaller/LightErrorPopPlanetInstaller/undoInit2.md)(string $appDir, Ling\CliTools\Output\OutputInterface $output, ?array $options = []) : void

- Inherited methods
    - public LightBasePlanetInstaller::__construct() : void
    - public LightBasePlanetInstaller::setContainer([Ling\Light\ServiceContainer\LightServiceContainerInterface](https://github.com/lingtalfi/Light/blob/master/doc/api/Ling/Light/ServiceContainer/LightServiceContainerInterface.md) $container) : void

}






Methods
==============

- [LightErrorPopPlanetInstaller::init2](https://github.com/lingtalfi/Light_ErrorPop/blob/master/doc/api/Ling/Light_ErrorPop/Light_PlanetInstaller/LightErrorPopPlanetInstaller/init2.md) &ndash; Executes the init 2 phase of the install command.
- [LightErrorPopPlanetInstaller::undoInit2](https://github.com/lingtalfi/Light_ErrorPop/blob/master/doc/api/Ling/Light_ErrorPop/Light_PlanetInstaller/LightErrorPopPlanetInstaller/undoInit2.md) &ndash; Undoes the init 2 phase.
- LightBasePlanetInstaller::__construct &ndash; Builds the LightBasePlanetInstaller instance.
- LightBasePlanetInstaller::setContainer &ndash; Sets the light service container interface.





Location
=============
Ling\Light_ErrorPop\Light_PlanetInstaller\LightErrorPopPlanetInstaller<br>
See the source code of [Ling\Light_ErrorPop\Light_PlanetInstaller\LightErrorPopPlanetInstaller](https://github.com/lingtalfi/Light_ErrorPop/blob/master/Light_PlanetInstaller/LightErrorPopPlanetInstaller.php)



SeeAlso
==============
Next class: [LightErrorPopService](https://github.com/lingtalfi/Light_ErrorPop/blob/master/doc/api/Ling/Light_ErrorPop/Service/LightErrorPopService.md)<br>

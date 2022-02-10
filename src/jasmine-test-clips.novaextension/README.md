# Jasmine Test Framework Clips for Nova

A collection of code snippets for the [Jasmine test framework](https://jasmine.github.io) to be used in Panic Inc.'s [Nova](https://nova.app) text editor. Trigger keywords based on [vscode-jasmine](https://github.com/xabikos/vscode-jasmine) and [sublime-jasmine](https://github.com/NicoSantangelo/sublime-jasmine).

## Installation

Open Extensions -> Extension Library in Nova (shift + cmd + 2) and search for "Kevin Longmuir Jasmine Test Framework Clips"

## Supported Languages

* Javascript
* Typescript

## Snippets

### Specs
| Trigger      | Content |
| -------:     | ------- |
| `desc→`      | describe block |
| `xdesc→`     | xdescribe block |
| `fdesc→`     | fdescribe block |
| `it→`        | it block |
| `xit→`       | xit block |
| `fit→`       | fit block |
| `ae→`        | after each block |
| `aa→`        | after all block |
| `be→`        | before each block |
| `ba→`        | before all block |


### Expectations
| Trigger  | Content |
| -------: | ------- |
| `exp→`   | expect |
| `tb→`    | expect().toBe |
| `tbct→`  | expect().toBeCloseTo |
| `tbd→`   | expect().toBeDefined |
| `tbf→`   | expect().toBeFalsy |
| `tbgt→`  | expect().toBeGreaterThan |
| `tblt→`  | expect().toBeLessThan |
| `tbn→`   | expect().toBeNull |
| `tbt→`   | expect().toBeTruthy |
| `tbu→`   | expect().toBeUndefined |
| `tbi→`   | expect().toBeInstanceOf |
| `tc→`    | expect().toContain |
| `te→`    | expect().toEqual |
| `thbc→`  | expect().toHaveBeenCalled |
| `thbcow→`| expect().toHaveBeenCalledOnceWith |
| `thbcw→` | expect().toHaveBeenCalledWith |
| `thbct→` | expect().toHaveBeenCalledTimes |
| `tm→`    | expect().toMatch |
| `tt→`    | expect().toThrow |
| `tte→`   | expect().toThrowError |
| `nb→`    | expect().not.toBe |
| `nct→`   | expect().not.toBeCloseTo |
| `nd→`    | expect().not.toBeDefined |
| `nf→`    | expect().not.toBeFalsy |
| `ngt→`   | expect().not.toBeGreaterThan |
| `nlt→`   | expect().not.toBeLessThan |
| `nn→`    | expect().not.toBeNull |
| `nt→`    | expect().not.toBeTruthy |
| `nu→`    | expect().not.toBeUndefined |
| `nc→`    | expect().not.toContain |
| `ne→`    | expect().not.toEqual |
| `nm→`    | expect().not.toMatch |
| `ntt→`   | expect().not.toThrow |
| `any→`   | jasmine.any |
| `oc→`    | jasmine.objectContaining |

### Spies
| Trigger  | Content |
| -------: | ------- |
|`so→`     | spyOn |
|`sct→`    | spyOn.and.callThrough |
|`scf→`    | spyOn.and.callFake |
|`spg→`    | spyOnProperty($obj,'$property', 'get') |
|`sps→`    | spyOnProperty($obj,'$property', 'set') |
|`srv→`    | spyOn.and.returnValue |
|`ss→`     | spyOn.and.stub |
|`ste→`    | spyOn.and.throwError |
|`cs→`     | createSpy |
|`cso→`    | createSpyObj |

### Clock Events
| Trigger  | Content |
| -------: | ------- |
|`ci→`     | jasmine.clock.install() |
|`cui→`    | jasmine.clock.uninstall() |
|`cmd→`    | jasmine.clock.mockDate |
|`ct→`    | jasmine.clock.tick |

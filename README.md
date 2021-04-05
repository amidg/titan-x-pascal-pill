# titan-x-pascal-pill
First gen GDDR5X card, Nvidia Titan X Pascal, cannot be improved by using an infamous ETH largement pill: https://github.com/Virosa/ETHlargementPill

Goal of this project is to bring GDDR5X improved timing support to my favourite Nvidia GPU that I sometimes use for mining to support myself as a university student. 
Supported on:
- Windows
- Linux (Work-In-Progress)

## How to use?
1. Run your miner (I use Phoenix Miner 5.5c with Nvidia drivers 461.72)
2. Run Titan X Pascal pill via CMD with Admin rights:
```
titan-x-pascal-pill.exe --revA #
```
Where # is your GPU #. 

## What is working?
Default settings with no overclock. Minor overclock up to 250 MHz on VRAM works and give +- 1-2 MH/s while using this VRAM timing fix pill. 
Maximum achieved hashrate with standard setting (+0 on core, +0 on VRAM, 100% PL) is 43 MH/s. 

## Known bugs:
* Due to the lack of the initial source code, this VRAM timing fix uses timings from the GTX1080 that is also the 1st gen GDDR5X GPU. 
* If started before miner -> entire system crash with BSOD (Blue Screen of Death). Full cold restart is required.
* No overclocking headroom compare to the original pill + GTX1080ti. 

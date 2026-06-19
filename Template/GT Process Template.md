## Common Processing

The standard rule is:
> 2x **InputA** + 250mB **FluidInputA** --[**Machine**, EU/t, Duration]--> 4x **OutputA** + 2x **OutputB**

For example:
> 1x **Iron dust** + 3B **Chlorine** --[**Chemical Reactor**, 30 EU/t, 10s]--> 1B **Iron 3 Chloride**,

this processing can also write as:
> 1x **Fe dust** + 3B **Cl** --[**Chemical Reactor**, 30 EU/t, 10s]--> 1B **FeCl3**

if input/output ingredient has two fluid state, please use suffix to declare it:
> 2x **Fe dust** + 3B **O**(g) --[**Roaster**, 120 EU/t, 2s10t]--> 5x **Fe2O3 dust**

where *g* means gas, *l* means liquid (we not use *s* for solid, because we already declare it with amount prefix).

## Processing with Additional Data

### Temperature
> 1x **Fe dust** --[**Electric Blast Furnace**, 30 EU/t, 10s, 1200K]--> 1x **Fe ingot**

### Cleanroom Condition
> 1x **Fe dust** + 3B **Cl** --[**Chemical Reactor**, 30 EU/t, 10s, Cleanroom]--> 1B **FeCl3**
> 2x **Fe dust** + 3B **O**(g) --[**Roaster**, 120 EU/t, 2s10t, Sterile Cleanroom]--> 5x **Fe2O3 dust**

### Assembly Line Research
> 1x **Fe dust** --[**Assembly Line**, 7860 EU/t, 1min30s15t, **Scanner**(1x **Fe dust**, 480 EU/t, 1min)]--> 1x **Fe ingot**
> 1x **Fe dust** --[**Assembly Line**, 7860 EU/t, 1min30s15t, **Research Station**(1x **Fe dust**, 480 EU/t, 6 CWU/t)]--> 1x **Fe ingot**
# qMRI colormaps

```@example 1
using QMRIColors
using CairoMakie
```

## Lipari

This colormap is used for :
- T1

```@example 1
cmap = relaxationColorMap("T1")
cgrad(cmap)
```

## Navia

This colormap is used for :
- T2
- T2*
- T1rho
- T1ρ

```@example 1
cmap = relaxationColorMap("T2")
cgrad(cmap)
```

## Reverse lipari

This colormap is used for :
- R1

```@example 1
cmap = relaxationColorMap("R1")
cgrad(cmap)
```


## Reverse navia

This colormap is used for :
- R2
- R2*
- R1rho
- R1ρ
- 
```@example 1
cmap = relaxationColorMap("R2")
cgrad(cmap)
```
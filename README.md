# shipping-calculator

Packaging carton and freight calculator.

Files:
- `运费计算器.html`: current stable stage-final version

Highlights in this version:
- airplane result panel length/width uses `B13/C13`
- airplane inquiry copy text uses `B13/C13`
- smart packing logic keeps existing base formulas and 3D preview logic intact
- shipping modes are `Sea/Air Freight (/6000)` and `Express (/5000)`
- full Chinese/English toggle
- enhanced no-solution diagnostics for single-carton constraint failures

Latest updates:
- smart-calculation limits now compare carton `length/width/height` one-to-one instead of using sorted edge comparison
- candidate search bounds now also follow `maxL / maxW / maxH` separately
- latest detailed record: `更新日志.md`

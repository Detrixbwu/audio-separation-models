# SCNet

Sparse Compression Network for Music Source Separation (paper by Chinese research team). Reproduced and improved by MVSep.

**Variants**  
- SCNet (small)  
- SCNet Large  
- SCNet XL (+ fullness tweaks)

## SDR Metrics

| Variant                   | Multisong Vocals | Multisong Instr. | Synth Vocals | Synth Instr. | MDX23 Vocals |
|---------------------------|------------------|------------------|--------------|--------------|--------------|
| SCNet                     | 10.25            | 16.56            | 12.27        | 11.97        | —            |
| SCNet Large               | 10.74            | 17.05            | 12.89        | 12.59        | —            |
| **SCNet XL**              | 10.96            | 17.27            | 13.08        | 12.78        | —            |
| SCNet XL (high fullness)  | 10.92            | 17.23            | —            | —            | —            |
| SCNet XL (very high fullness) | 10.40       | 16.60            | —            | —            | —            |

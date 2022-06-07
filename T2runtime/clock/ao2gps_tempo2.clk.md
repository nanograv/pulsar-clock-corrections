
## Arecibo (TEMPO2)

Arecibo clock corrections to GPS (TEMPO2 version)

The early clock corrections for Arecibo predate GPS and are
actually referenced directly to NIST. This clock correction file
separates these out so their corrections can be handled using a
different clock chain. Unfortunately it does not include
clock corrections for the last months of operation of Arecibo.

This file is pulled from the TEMPO2 repository and may not be fully up-to-date.

|     |     |
|:--- |:--- |
| File | `T2runtime/clock/ao2gps_tempo2.clk` |
| Authority | temporary |
| URL in repository | <https://raw.githubusercontent.com/nanograv/pulsar-clock-corrections/main/T2runtime/clock/ao2gps_tempo2.clk> |
| Original download URL | <https://bitbucket.org/psrsoft/tempo2/raw/HEAD/T2runtime/clock/ao2gps.clk> |
| Format | tempo2 |
| Bogus last correction | False |
| Clock file start | 1996-03-13 MJD 50155.0 |
| Clock file end | 2019-12-18 MJD 58835.0 |
| Update interval (days) | inf |
| Last update attempt | 2022-05-26 |
| Last update result | Unchanged |

Log entries from the last few update attempts:
```
2022-05-26 08:30:05.733 - Unchanged
2022-05-26 08:35:04.319 - Unchanged
```
[Full log](https://raw.githubusercontent.com/nanograv/pulsar-clock-corrections/main/log/T2runtime/clock/ao2gps_tempo2.clk.log)


All clock corrections:

![plot of all clock corrections](ao2gps_tempo2.clk.png "All corrections")

Recent clock corrections:

![plot of recent clock corrections](ao2gps_tempo2.clk.short.png "Recent corrections")

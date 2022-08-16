---
aliases: []
---
#privacy #vr
***

## VR Tracking

It is possible to track an user across virtual reality sessions by watching for some attributes. In turn, it's also possible to skew these identification methods by various means.

### Means of identification in virtual reality

| Name                  | Description                | Method of anonymization                         |
| --------------------- | -------------------------- | ----------------------------------------------- |
| Height                | `y_max = height * x`       | 1. Add an offset to y 2. Add a coefficient to y |
| Wingspan              |                            |                                                 |
| Room size             |                            |                                                 |
| Handedness            |                            |                                                 |
| Longer arm            |                            |                                                 |
| Geolocation           |                            | Randomly delay packets by 1ms                   |
| Reaction time         | (also correlated with age) |                                                 |
| Tracking refresh rate |                            |                                                 |
| VR Device             |                            |                                                 |
| Voice | See [[public/Extracting sensitive information from voice]] |

### Références

- [Going Incognito in the Metaverse](https://arxiv.org/pdf/2208.05604.pdf)
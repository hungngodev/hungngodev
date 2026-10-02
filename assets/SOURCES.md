# Asset provenance

## Keyboard-lab banner

The four `keyboard-lab-*.svg` files are original vector illustrations created for this profile. The nine-key macropad is a design motif, not a photograph or a depiction of completed hardware. Light and dark artwork share the same geometry; animated variants use one three-second SVG signal transition and then hold the final position. Static variants have no animation elements and are selected for reduced-motion visitors.

## Skill icons

The artwork in [skills-light.svg](skills-light.svg) and [skills-dark.svg](skills-dark.svg) comes from [tandpfun/skill-icons](https://github.com/tandpfun/skill-icons) at the pinned upstream commit [7f7e691e71aec64e8354bf697835e009d1ad80f8](https://github.com/tandpfun/skill-icons/tree/7f7e691e71aec64e8354bf697835e009d1ad80f8). It is distributed under the MIT License; the exact upstream notice is included in [skill-icons-LICENSE.txt](skill-icons-LICENSE.txt).

| Display name | Light source | Dark source |
| --- | --- | --- |
| Python | [Python-Light.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Python-Light.svg) | [Python-Dark.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Python-Dark.svg) |
| TypeScript | [TypeScript.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/TypeScript.svg) | [TypeScript.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/TypeScript.svg) |
| Go | [GoLang.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/GoLang.svg) | [GoLang.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/GoLang.svg) |
| C++ | [CPP.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/CPP.svg) | [CPP.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/CPP.svg) |
| PostgreSQL | [PostgreSQL-Light.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/PostgreSQL-Light.svg) | [PostgreSQL-Dark.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/PostgreSQL-Dark.svg) |
| Redis | [Redis-Light.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Redis-Light.svg) | [Redis-Dark.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Redis-Dark.svg) |
| Docker | [Docker.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Docker.svg) | [Docker.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Docker.svg) |
| Kubernetes | [Kubernetes.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Kubernetes.svg) | [Kubernetes.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Kubernetes.svg) |
| AWS | [AWS-Light.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/AWS-Light.svg) | [AWS-Dark.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/AWS-Dark.svg) |
| Google Cloud | [GCP-Light.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/GCP-Light.svg) | [GCP-Dark.svg](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/GCP-Dark.svg) |

### Local transformations

- Arranged ten icons in two rows of five, in the order shown above.
- Kept the official artwork, colors, and existing light/dark variants. Icons without variants use the same official source in both bundles.
- Used a 272 × 104 SVG canvas, with 44 × 44 icon viewports, 12 px gaps, and 2 px outer padding. Original 256 × 256 viewBoxes scale proportionally into those viewports.
- Namespaced every upstream SVG ID and its local fragment reference per theme and icon to prevent collisions between gradients and clipping paths.
- Added an SVG title and description naming all ten tools for accessibility.
- Embedded all paths and definitions directly, with no external image, font, script, or stylesheet dependency.

The files are checked-in static assets. Viewing them does not call skillicons.dev or require a token, workflow, or third-party service.

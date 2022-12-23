---
layout: post
title:  "Explorer Open Source EDA"
tags: EDA
---

I'm planning to write a series of blogs to explore open source EDA tools. This is the first blog & the front matter.

## TOC

PLACEHOLDER

## What's EDA

> Electronic design automation (EDA) is a category of software tools for designing electronic systems such as integrated circuits and printed circuit boards.  
> The tools work together in a design flow that chip designers use to design and analyze entire semiconductor chips. Since a modern semiconductor chip can have billions of components, EDA tools are essential for their design.  
> (from [Wikipedia:EDA](https://en.wikipedia.org/wiki/Electronic_design_automation))

Chip designing is complex and consists of different kinds of tasks: simulation, synthesis, physical implementation, formal verification, sign-off, etc. These individual tools are assemblied to a _design flow_.

![openlane flow](/assets/openlane_flow_v1.png)
Openlane Flow (from [OpenLane][openlane-flow] website)

[openlane-flow]: https://openlane.readthedocs.io/en/latest/flow_overview.html

## Open source EDA

Open source EDA is not a new thing. We have [Verilator][verilator] for functional simulation, we have [Yosys][yosys] for logic synthesis, we have [qflow][qflow] to complete thw whole RTL-to-GDS flow, but they are never a major player.

They were not widely used. They have only a small community. They have limited developers and maintainers. They are well maintained, but extremely lacking of development resources. They could be used to finish basic tasks, but they lack important features, and are never comparable to commercial tools.

Luckily, the situation is getting better. Existing projects like Yosys or Verilator are having a larger community. New projects are emerging (OpenROAD, [CIRCT][circt], etc).

TODO

[verilator]: https://github.com/verilator/verilator
[yosys]: https://github.com/YosysHQ/yosys
[qflow]: https://github.com/RTimothyEdwards/qflow
[openroad]: https://github.com/The-OpenROAD-Project/OpenROAD
[circt]: https://github.com/llvm/circt

## What will be covered in this series

Yosys, Openroad, magic, Verilator, ...

{% include comment.html %}

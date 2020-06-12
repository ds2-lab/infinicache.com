---
layout: default
title: Home
nav_order: 1
description: "Welcome to InfiniCache project site"
permalink: /
---

# InfiniCache
{: .fs-9 }

<!-- Welcome to InfiniCache porject site.
{: .fs-6 .fw-300 }
 -->
InfiniCache is a **cost-effective** memory cache that is built atop **ephemeral serverless functions**
{: .fs-6 .fw-300 }

[&nbsp;PAPER&nbsp;](https://www.usenix.org/system/files/fast20-wang_ao.pdf){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } 
[&nbsp;TALK&nbsp;](https://www.youtube.com/watch?v=3_NmYAh5zek&t){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 } 
[&nbsp;CODE&nbsp;](https://github.com/mason-leap-lab/infinicache){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
[&nbsp;SLIDE&nbsp;](https://www.usenix.org/sites/default/files/conference/protected-files/fast20_slides_wang-ao.pdf){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
[POSTER](docs/fast20-infinicache_poster.pdf){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## What is InfiniCache
{: .fs-6.5 }

A first-of-its-kind in-memory object caching system that is completely built and deployed atop ephemeral serverless functions. INFINICACHE exploits and orchestrates serverless functions’ memory resources to enable elastic payper-use caching. INFINICACHE’s design combines erasure coding, intelligent billed duration control, and an efficient data backup mechanism to maximize data availability and cost effectiveness while balancing the risk of losing cached state and performance.

---
## Feature
{: .fs-6.5 }

- The very first in-memory object caching system powered by ephemeral and “stateless” cloud functions.
- Leverage several intelligent techniques to maxmize data availability, such as erasure coding periodic warm-up abd periodic delta-sync techniques.
- InfiniCache achieves performance comparable to ElastiCache (600GB cache capacity) for large objects and improves the cost effectiveness of cloud IMOCs by 31 – 96x.

---
### Contact
Please feel free to reach out us if you have any questions about *InfiniCache*.

### Contributing

Please feel free to hack on InfiniCache! We're happy to accept contributions.

#### **Thank you to the contributors of InfiniCache!**

<!-- <ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
 -->
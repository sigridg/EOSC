---
title: Services
layout: default
---

# Services

[← Back to main document](index.md)

## Service charing

### Sharing a Service That Is not Part of a Thematic Node

The following diagram illustrates how a service developed by UiO (University of Oslo) that is not part of a thematic node can be shared through the Norwegian EOSC node to both national and international recipients:

<div class="mermaid">
graph TD
    A[UiO has a service<br/>that is relevant to<br/>share] --> B[EOSC national<br/>node]
    B --> C[Norwegian University receives]
    B --> D[Swedish EOSC node]
    B --> E[Dutch EOSC node]
    D --> F[Swedish University receives]
    E --> G[Dutch University receives]
</div>

### Sharing a Service That Is Part of a Thematic Node

When a service is already part of a thematic node (like Elixir), it can be shared directly through that node:
<div class="mermaid">
graph TD
    A[UiO has a service<br/>that is relevant to<br/>share] --> B[Elixir thematic<br/>node]
    C[EOSC national<br/>node]
    B --> D[Norwegian University receives]
    B --> E[Swedish University receives]
    B --> F[Dutch University receives]
    
    style B fill:#fed,stroke:#333
</div>

In this scenario, the EOSC national node is not involved in the service distribution, as the thematic node (Elixir) handles the coordination directly.
> 
> **Discussion:** See [Issue x](link)

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true, theme: 'dark' });
</script>
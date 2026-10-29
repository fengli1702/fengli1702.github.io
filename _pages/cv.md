---
title: Curriculum Vitae
permalink: /cv/
---

[Download CV (PDF)]({{ '/files/Daifeng_Li_CV.pdf' | relative_url }}){: .btn .btn--primary }

## Education

{% include education-list.html %}

## Publications

{% include publication-list.html %}

## Research & Industry Experience

- **Research Intern, Alibaba Qwen Team**, March 2026–Present. LLM-based CUDA kernel generation and GPU operator optimization; participated in Qwen3.7-Max training and evaluation, including KernelBench evaluation.
- **Core Contributor, Ave (formerly ARGUS)**, 2025–2026. Agentic GPU optimization guided by data-flow invariants; FlashAttention kernels on AMD GPUs, MoE and attention operators for vLLM/SGLang, benchmark execution, and ablation analysis.
- **Research Assistant**, Relaxed System Lab, HKUST. Started Summer 2025. Compiler–system co-design and IR-level GPU kernel optimizations.
- **CPU Design**, Fall 2024. Four-issue out-of-order Loongson core on FPGA; National Third Prize at NSCSCC.

## Teaching Experience

{% include teaching-list.html %}

## Honors & Awards

<ul class="awards-list">
{% for award in site.data.awards %}
  <li><strong>{{ award.name }}</strong>{% if award.organization %}, {{ award.organization }}{% endif %} <span class="entry-date">{{ award.years }}</span></li>
{% endfor %}
</ul>

## Skills

**Languages:** C, C++, Python, Verilog, Chisel, x86 Assembly, CUDA.

**Frameworks & Tools:** PyTorch, Triton, TileLang, Git, GDB, LaTeX, Linux.

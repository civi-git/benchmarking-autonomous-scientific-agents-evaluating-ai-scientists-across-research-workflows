# The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search

**Authors:** Yutaro Yamada, Robert Tjarko Lange, Cong Lu, Shengran Hu, Chris Lu, Jakob Foerster, Jeff Clune, David Ha  
**Journal:** arXiv preprint  
**Year:** 2025  
**DOI:** https://doi.org/10.48550/arXiv.2504.08066  
**URL:** https://arxiv.org/abs/2504.08066

## CS197 Analysis Framework

### Problem
What problem is being solved? Why does it matter?
- AI's growing role in scientific discovery lacks end-to-end automation capability
- Previous systems (v1) relied on human-authored code templates, limiting generalizability
- Need for AI systems that can produce peer-review-accepted scientific papers
- Challenge of creating truly autonomous scientific discovery that navigates peer review process

### Prior Assumptions
What assumption did prior research make? Why was it inadequate?
- **Assumption**: AI-generated research requires human-provided code templates and structure
- **Assumption**: AI cannot generalize across diverse machine learning domains without pre-built frameworks
- **Assumption**: Peer review acceptance is beyond current AI capabilities
- **Inadequacy**: Template dependency limits autonomy and domain generalization

### Insight
What novel idea breaks from that assumption?
- **Core Insight**: Progressive agentic tree-search methodology managed by dedicated experiment manager agent can eliminate reliance on human templates
- **Key Innovation**: Vision-Language Model (VLM) feedback loop for iterative refinement of content and aesthetics
- **Breakthrough**: First AI system to produce peer-review-accepted workshop paper entirely autonomously

### Technical Overview
How was the insight implemented?
- **Agentic Tree Search**: Novel progressive methodology for experiment exploration
- **Experiment Manager Agent**: Dedicated agent for orchestrating research workflow
- **VLM Integration**: Vision-Language Model feedback for figure refinement
- **Template-Free Operation**: Eliminates reliance on human-authored code templates
- **Multi-Domain Generalization**: Works across diverse machine learning domains
- **Iterative Refinement**: Continuous improvement of content and presentation quality

### Proof/Evaluation
How was the insight validated?
- **Peer Review Success**: One manuscript exceeded average human acceptance threshold
- **Multiple Submissions**: Three fully autonomous manuscripts submitted to ICLR workshop
- **Quality Assessment**: Papers approach human-level research quality
- **Comparison with v1**: Demonstrated improvements over predecessor system
- **Domain Diversity**: Effective across multiple machine learning areas

### Impact
What are the implications? How will it change the field?
- **Historic Achievement**: First fully AI-generated paper to pass peer review
- **Research Autonomy**: Proves AI can conduct all aspects of scientific research
- **Quality Standards**: Meets academic publication standards autonomously  
- **Scalability**: Enables rapid exploration of research directions
- **Future Vision**: Points toward fully autonomous scientific discovery systems

## Key Assumptions Identified
1. **Template Dependency**: AI research systems need human-provided structure
2. **Domain Specificity**: AI cannot generalize research capabilities across fields
3. **Peer Review Barrier**: AI-generated research cannot meet publication standards

## Potential Bit Flip
**Bit**: "AI-generated scientific research requires human templates and cannot pass peer review"  
**Flip**: "AI agents can autonomously conduct research from hypothesis to peer-reviewed publication without human scaffolding"  
**Impact**: Establishes AI as capable of independent scientific contribution at publication level

## Citation
Yamada, Y., Lange, R. T., Lu, C., Hu, S., Lu, C., Foerster, J., Clune, J., & Ha, D. (2025). The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search. arXiv preprint arXiv:2504.08066.
# MLR-Bench: Evaluating AI Agents on Open-Ended Machine Learning Research

**Authors:** Hui Chen, Miao Xiong, Yujie Lu, Wei Han, Ailin Deng, Yufei He, Jiaying Wu, Yibo Li, Yue Liu, Bryan Hooi  
**Journal:** arXiv preprint  
**Year:** 2025  
**DOI:** https://doi.org/10.48550/arXiv.2505.19955  
**URL:** https://arxiv.org/abs/2505.19955

## CS197 Analysis Framework

### Problem
What problem is being solved? Why does it matter?
- AI agents show growing potential for scientific discovery but lack comprehensive evaluation frameworks
- Need for systematic assessment of AI agents on open-ended machine learning research
- Challenge of evaluating research quality across different stages (ideation, experimentation, writing)
- Gap between agent capabilities and reliable scientific output

### Prior Assumptions
What assumption did prior research make? Why was it inadequate?
- **Assumption**: AI agents can reliably conduct experimental validation in research
- **Assumption**: Coding agents produce valid experimental results
- **Assumption**: Research evaluation can focus primarily on final paper quality
- **Inadequacy**: Current evaluation misses critical reliability issues in experimental validation

### Insight
What novel idea breaks from that assumption?
- **Core Insight**: AI agents require comprehensive evaluation across all research stages, with particular attention to experimental reliability
- **Key Innovation**: MLR-Judge automated evaluation framework combining LLM-based reviewers with designed rubrics
- **Critical Finding**: Coding agents frequently produce fabricated or invalidated experimental results

### Technical Overview
How was the insight implemented?
- **MLR-Bench**: 201 research tasks from NeurIPS, ICLR, ICML workshops
- **MLR-Judge**: Automated evaluation combining LLM reviewers with review rubrics
- **MLR-Agent**: Modular agent scaffold for complete research tasks
- **Four-Stage Assessment**: Idea generation, proposal formulation, experimentation, paper writing
- **Quality Metrics**: Research quality assessment across distinct stages

### Proof/Evaluation
How was the insight validated?
- Evaluated six frontier LLMs and advanced coding agent
- Found 80% fabrication rate in experimental results from coding agents
- Demonstrated effectiveness through human evaluation validation
- Comprehensive assessment across 201 diverse ML research tasks

### Impact
What are the implications? How will it change the field?
- **Reliability Crisis**: Reveals major barriers to scientific reliability in AI agents
- **Evaluation Framework**: Provides systematic assessment methodology for research agents
- **Research Priorities**: Highlights need for improved experimental validation in AI systems
- **Trust and Verification**: Emphasizes importance of result validation in AI-generated research

## Key Assumptions Identified
1. **Experimental Reliability**: AI coding agents produce valid experimental results
2. **End-to-End Evaluation**: Final paper quality sufficiently captures research capability
3. **Scientific Integrity**: AI agents maintain scientific rigor throughout research process

## Potential Bit Flip
**Bit**: "AI agents can be trusted to conduct reliable experimental validation in scientific research"  
**Flip**: "AI research agents require systematic verification mechanisms due to high rates of experimental fabrication"  
**Impact**: Necessitates development of verification systems for AI-generated scientific results

## Citation
Chen, H., Xiong, M., Lu, Y., Han, W., Deng, A., He, Y., Wu, J., Li, Y., Liu, Y., & Hooi, B. (2025). MLR-Bench: Evaluating AI Agents on Open-Ended Machine Learning Research. arXiv preprint arXiv:2505.19955.
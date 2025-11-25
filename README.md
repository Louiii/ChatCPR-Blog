[![DOI](https://zenodo.org/badge/1103480579.svg)](https://doi.org/10.5281/zenodo.17715681)

# Interactive Supplement

This repository contains the interactive HTML supplement for:

**CPR Blog: LLM-agent common-pool resource simulation**

## How to view the interactive HTML

To launch a local server (recommended for full interactivity):

```bash
python3 -m http.server 8000 --directory .
# then open http://localhost:8000/index.html
```

Opening `index.html` directly in your browser may work for static content,
but some interactive elements (iframes, JS modules, etc.) require a local server.


## Citation 

If you use this interactive blog or simulation in research, please cite:

Louis Robinson (2025). *Emergent Deception and Governance in Common-Pool Resource Multi-Agent Simulations*. Zenodo. https://doi.org/10.5281/zenodo.17715681


```bibtex
@misc{robinson2025cpr,
  author       = {Robinson, Louis},
  title        = {Emergent Deception and Governance in Common-Pool Resource Multi-Agent Simulations},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17715681},
  url          = {https://doi.org/10.5281/zenodo.17715681}
}
```
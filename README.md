# Finite Photon Packets and the Double Slit: Overlap, Not Self-Interference

**Contact**  
For correspondence regarding this work:  
📧 [toddjoelmondragon@gmail.com](mailto:toddjoelmondragon@gmail.com)  
(For research correspondence — please use responsibly.)

[![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17166728.svg)](https://doi.org/10.5281/zenodo.17166728)  
[![ORCID](https://img.shields.io/badge/ORCID-0009--0004--7868--3021-A6CE39.svg)](https://orcid.org/0009-0004-7868-3021)  
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

> **TL;DR**  
> A photon packet always passes through one slit.  
> Fringes require overlap of **two coherent streams**, not self-interference.

---

## Abstract
We re-examine the double-slit experiment. Standard quantum interpretations assert that a photon laterally spreads across both slits and interferes with itself. We show this is unnecessary. Photons are finite packets (\(\ell = c \, \tau_{\text{emit}} \, \kappa\)) that traverse one slit only. A single slit produces only angular spread; interference fringes emerge only when two coherent packet streams overlap at the detector with relative phase shifts spanning 0 to \(\pi\). This explanation is consistent with high-speed single-photon build-up experiments and extends the finite packet ontology established in *Finite Photon Packets and the Bell Threshold: Overlap, Not Superposition*.

---

## Key claims
- **Finite packets:** photons are spatiotemporal packets of length \(\ell = c \, \tau_{\text{emit}} \, \kappa\).  
- **Single slit:** packets are deflected by EM boundary conditions at knife edges → angular spread only, no fringes.  
- **Two slits:** overlapping coherent streams with path differences → relative phases → fringes.  
- **Decoherence:** which-path detection removes one stream → no fringes.  
- **Delayed choice:** trajectory fixed once slit is passed → no retrocausality.  

---

<h2 id="contents">Repository contents</h2>
<pre><code>
Mondragon-2025-Finite-Photon-Packets-Double-Slit.pdf  # Camera-ready manuscript (as on arXiv/RG/Academia) -> CC BY 4.0  
/LICENSE-CC-BY-4.0          # full CC BY 4.0 text (for PDF/text/images you own)
/LICENSE-MIT                # MIT text (for code)
/NOTICE                     # maps directories -> licenses
//latex/ ...                # LaTeX files -> CC BY 4.0
/paper/ ...                 # manuscript, figures -> CC BY 4.0
/code/  ...                 # scripts, notebooks  -> MIT
</code></pre>

<hr>

<h2 id="bench-tests">Falsifiable bench tests</h2>
<ul>
  <li><strong>Bell vs. packet length:</strong> Fix geometry and analyzers; swap sources to vary &ell;:
    (i) unseeded Q-switched (short &ell;), (ii) injection-seeded (longer &ell;),
    (iii) single-frequency CW (very long &ell;).
    Evaluate with <strong>CH/CH&ndash;Eberhard</strong>, include no-clicks, forbid post-selection.
    <em>Prediction:</em> violations only for L &lesssim; &ell;.</li>
  <li><strong>HOM ruler:</strong> Two identical packets on 50/50 BS.
    Dip/visibility vs delay follows V(&Delta;L).</li>
  <li><strong>Gate-depth cliff:</strong> Mach&ndash;Zehnder with Pockels phase gate;
    fidelity collapses when &Sigma;&Delta;T &approx; &tau;<sub>emit</sub>; shifts with &ell;.</li>
</ul>

<p><em>Safeguards:</em> pre-register trials; publish full time tags; fixed coincidence windows; spacelike-separated RNGs/settings.</p>

<hr>

<h2 id="cite">Cite</h2>
<p>See <a href="./CITATION.cff">CITATION.cff</a> for auto-generated BibTeX via GitHub&rsquo;s &ldquo;Cite this repository&rdquo; button.</p>

<p><strong>Preprint (preferred)</strong></p>
<pre><code class="language-bibtex">@article{Mondragon2025FinitePackets,
  title    = {Finite Photon Packets and the Double Slit: Overlap,Not Self-Interference},
  author   = {Mondragon, Todd Joel},
  journal  = {Zenodo (Preprint)},
  year     = {2025},
  month    = {8},
  version  = {1.0.0},
  orcid    = {https://orcid.org/0009-0004-7868-3021},
  doi      = {10.5281/zenodo.17166728},
  url      = {https://doi.org/10.5281/zenodo.17166728}
}
</code></pre>

<hr>

<h2 id="links">Links</h2>
<ul>
  <li><strong>arXiv:</strong> <a href="https://arxiv.org/abs/ARXIV_ID">https://arxiv.org/abs/ARXIV_ID</a></li>
  <li><strong>DOI (Zenodo):</strong> <a href="https://doi.org/10.5281/zenodo.17166728">https://doi.org/10.5281/zenodo.17166728</a></li>
  <li><strong>ORCID:</strong> <a href="https://orcid.org/0009-0004-7868-3021">https://orcid.org/0009-0004-7868-3021</a></li>
  <li><strong>Repository:</strong> <a href="https://github.com/ToddJoelMondragon/Finite-Photon-Packets-and-the-Double-Slit">https://github.com/ToddJoelMondragon/Finite-Photon-Packets-and-the-Double-Slit</a></li>
</ul>

<hr>

## Licensing

**PDF/Text (paper):**  
*Finite Photon Packets, Overlap Criterion, and the Bell Threshold* © 2025 Todd Joel Mondragon is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
See [`LICENSE-CC-BY-4.0`](./LICENSE-CC-BY-4.0) or <https://creativecommons.org/licenses/by/4.0/>.

**Code:**  
Released under the **MIT License**. See [`LICENSE-MIT`](./LICENSE-MIT).

> Unless otherwise noted: `/paper/**` and `/latex/**` are CC BY 4.0, `/code/**` is MIT. Third-party content keeps its original license.
<hr>

<h2 id="ack">Acknowledgments</h2>
<p>
  The author used digital tools (ChatGPT, Claude, ScholarAI, Wolfram) for editorial feedback,
  citation management, and consistency checks.
  All conceptual work, theoretical modeling, and scientific interpretation are the author’s original contributions.
</p>

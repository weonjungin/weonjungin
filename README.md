<h1 align="center">Hi, I'm Jiweon </h1>
<p align="center">Undergraduate Student · Audio-Driven Lip-Sync Video Generation</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Computer%20Vision-4B8BBE?style=flat-square" />
</p>

---

### 🔬 About

I'm an undergraduate student in the Department of Data Science, and worked as an undergraduate researcher at a Computer Vision Lab (Nov 2025 – Jun 2026), focusing on **audio-driven talking-head generation** — specifically improving lip-sync accuracy in generative video models. My work focuses on moving beyond whole-face synchronization toward **lip-region-specific** training objectives by combining a face-level reconstruction loss with a custom lip-level contrastive sync loss.

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[ADLip2](https://github.com/weonjungin/ADLip2)**
Lip-focused generative model for audio-driven lip-sync, built on MuseTalk's latent-space framework. Combines LatentSync (face-level) loss with a custom lip-level contrastive loss (SyncNetTemporal) to directly target the lip region.

</td>
<td width="50%" valign="top">

**[lip-sync-score](https://github.com/weonjungin/lip-sync-score)**
Custom SyncNetTemporal (SyncLT) module trained on GRID/HDTF for lip-sync synchronization scoring — the evaluation backbone used in ADLip2.

</td>
</tr>
</table>

### 🛠️ Tech Stack

`PyTorch` · `MuseTalk` · `Whisper` · `GFPGAN` · `DDP / Multi-GPU Training`


<p align="center">
  <img src="image/logo.png" width="700" alt="AutoResearchClaw Logo">
</p>

<h2 align="center"><b>Mag-chat ng Ideya. Makakuha ng Paper. Ganap na Autonomous.</b></h2>

<p align="center">
  <b><i><font size="5">Mag-chat lamang sa <a href="#openclaw-integration">OpenClaw</a>: "Research X" → tapos na.</font></i></b>
</p>

<p align="center">
  <img src="image/framework.png" width="100%" alt="AutoResearchClaw Framework">
</p>


<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License"></a>
  <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.11%2B-3776AB?logo=python&logoColor=white" alt="Python 3.11+"></a>
  <a href="#testing"><img src="https://img.shields.io/badge/Tests-1284%20passed-brightgreen?logo=pytest&logoColor=white" alt="1284 Tests Passed"></a>
  <a href="https://github.com/aiming-lab/AutoResearchClaw"><img src="https://img.shields.io/badge/GitHub-AutoResearchClaw-181717?logo=github" alt="GitHub"></a>
  <a href="#openclaw-integration"><img src="https://img.shields.io/badge/OpenClaw-Compatible-ff4444?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6IiBmaWxsPSJ3aGl0ZSIvPjwvc3ZnPg==" alt="OpenClaw Compatible"></a>
  <a href="https://discord.gg/u4ksqW5P"><img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?logo=discord&logoColor=white" alt="Discord"></a>
</p>

<p align="center">
  <a href="docs/README_CN.md">🇨🇳 中文</a> ·
  <a href="docs/README_JA.md">🇯🇵 日本語</a> ·
  <a href="docs/README_KO.md">🇰🇷 한국어</a> ·
  <a href="docs/README_FR.md">🇫🇷 Français</a> ·
  <a href="docs/README_DE.md">🇩🇪 Deutsch</a> ·
  <a href="docs/README_ES.md">🇪🇸 Español</a> ·
  <a href="docs/README_PT.md">🇧🇷 Português</a> ·
  <a href="docs/README_RU.md">🇷🇺 Русский</a> ·
  <a href="docs/README_AR.md">🇸🇦 العربية</a>
</p>

<p align="center">
  <a href="docs/integration-guide.md">📖 Gabay sa Integrasyon</a> · <a href="https://discord.gg/u4ksqW5P">💬 Komunidad sa Discord</a>
</p>

---

> **🧪 Naghahanap kami ng mga tester!** Subukan ang pipeline gamit ang iyong sariling ideya sa pananaliksik — mula sa anumang larangan — at [sabihin sa amin ang iyong mga naiisip](docs/TESTER_GUIDE.md). Ang iyong feedback ay direktang humuhubog sa susunod na bersyon. **[→ Gabay sa Pagsubok](docs/TESTER_GUIDE.md)** | **[→ 中文测试指南](docs/TESTER_GUIDE_CN.md)**

---

## 🔥 Mga Balita
- **[03/17/2026]** [v0.3.0](https://github.com/aiming-lab/AutoResearchClaw/releases/tag/v0.3.0) — **MetaClaw Integration** — Sinusuportahan na ngayon ng AutoResearchClaw ang [MetaClaw](https://github.com/aiming-lab/MetaClaw) cross-run learning: mga pagpalya ng pipeline → mga natutunan → mga reusable na kasanayan, na ini-inject sa lahat ng 23 yugto. **+18.3%** na katatagan sa mga kontroladong eksperimento. Opt-in (`metaclaw_bridge.enabled: true`), ganap na backward-compatible. Tingnan ang [Gabay sa Integrasyon](#-metaclaw-integration).
- **[03/16/2026]** [v0.2.0](https://github.com/aiming-lab/AutoResearchClaw/releases/tag/v0.2.0) — Tatlong multi-agent subsystem (CodeAgent, BenchmarkAgent, FigureAgent), pinatibay na Docker sandbox na may network-policy-aware na pagpapatakbo, 4-round na audit ng kalidad ng papel (pagtuklas ng AI-slop, 7-dim na pagmamarka ng review, NeurIPS checklist), at 15+ na pag-aayos ng bug mula sa mga production run.
- **[03/15/2026]** [v0.1.0](https://github.com/aiming-lab/AutoResearchClaw/releases/tag/v0.1.0) — Inilalabas namin ang AutoResearchClaw: isang ganap na autonomous na 23-yugto na pipeline ng pananaliksik na ginagawang conference-ready na papel ang isang ideya sa pananaliksik. Walang kinakailangang pakikialam ng tao.

---

## ⚡ Isang Utos. Isang Papel.

```bash
pip install -e . && researchclaw run --topic "Your research idea here" --auto-approve
```

---

## 🤔 Ano Ito?

**Isipin mo ito. Isusulat ito ng AutoResearchClaw.**

Maglagay ng paksa sa pananaliksik — makakuha ng buong akademikong papel na may tunay na literatura mula sa OpenAlex, Semantic Scholar at arXiv, hardware-aware na sandbox na eksperimento (GPU/MPS/CPU na awtomatikong natutukoy), istatistikal na pagsusuri, multi-agent na peer review, at conference-ready na LaTeX na nakatutok sa NeurIPS/ICML/ICLR. Walang bantay. Walang copy-paste. Walang mga gawa-gawang sanggunian.

<table>
<tr><td>📄</td><td><code>paper_draft.md</code></td><td>Buong akademikong papel (Panimula, Kaugnay na Gawa, Pamamaraan, Mga Eksperimento, Mga Resulta, Konklusyon)</td></tr>
<tr><td>📐</td><td><code>paper.tex</code></td><td>Conference-ready na LaTeX (mga template ng NeurIPS / ICLR / ICML)</td></tr>
<tr><td>📚</td><td><code>references.bib</code></td><td>Tunay na mga sangguniang BibTeX mula sa OpenAlex, Semantic Scholar at arXiv — awtomatikong pinuputol upang tumugma sa mga inline na pagsipi</td></tr>
<tr><td>🔍</td><td><code>verification_report.json</code></td><td>4-layer na integridad ng pagsipi + beripikasyon ng kaugnayan (arXiv, CrossRef, DataCite, LLM)</td></tr>
<tr><td>🧪</td><td><code>experiment runs/</code></td><td>Nabuong code + mga resulta ng sandbox + mga nakabalangkas na sukatan sa JSON</td></tr>
<tr><td>📊</td><td><code>charts/</code></td><td>Mga awtomatikong nabuong tsart ng paghahambing ng kondisyon na may mga error bar at confidence interval</td></tr>
<tr><td>📝</td><td><code>reviews.md</code></td><td>Multi-agent na peer review na may mga pagsusuri sa pagkakatugma ng pamamaraan at ebidensya</td></tr>
<tr><td>🧬</td><td><code>evolution/</code></td><td>Mga natutunan na kinukuha mula sa bawat run</td></tr>
<tr><td>📦</td><td><code>deliverables/</code></td><td>Lahat ng panghuling output sa isang folder — handa nang i-compile para sa Overleaf</td></tr>
</table>

Ang pipeline ay tumatakbo **nang walang pakikialam ng tao mula simula hanggang katapusan**. Kapag nabigo ang mga eksperimento, nagpapagaling ito nang kusa. Kapag hindi napatunayan ang mga hypothesis, nagbabago ito ng direksyon. Kapag peke ang mga sanggunian, tinatanggal nito ang mga ito.

---

## 🚀 Mabilis na Pagsisimula

```bash
# 1. I-clone at i-install
git clone https://github.com/aiming-lab/AutoResearchClaw.git
cd AutoResearchClaw
python3 -m venv .venv && source .venv/bin/activate
pip install -e .

# 2. I-configure
cp config.researchclaw.example.yaml config.arc.yaml
# I-edit ang config.arc.yaml — itakda ang iyong LLM API endpoint at key

# 3. Patakbuhin
export OPENAI_API_KEY="sk-..."
researchclaw run --config config.arc.yaml --topic "Your research idea" --auto-approve
```

Output → `artifacts/rc-YYYYMMDD-HHMMSS-<hash>/deliverables/` — compile-ready na LaTeX, BibTeX, code ng eksperimento, mga tsart.

<details>
<summary>📝 Pinakamababang kinakailangang config</summary>

```yaml
project:
  name: "my-research"

research:
  topic: "Your research topic here"

llm:
  base_url: "https://api.openai.com/v1"
  api_key_env: "OPENAI_API_KEY"
  primary_model: "gpt-4o"
  fallback_models: ["gpt-4o-mini"]

experiment:
  mode: "sandbox"
  sandbox:
    python_path: ".venv/bin/python"
```

</details>

---

## 🧠 Ano ang Nagpapaiba Rito

| Kakayahan | Paano Ito Gumagana |
|-----------|----------------|
| **🔄 PIVOT / REFINE Loop** | Ang Yugto 15 ay awtomatikong nagpapasya: PROCEED, REFINE (ayusin ang mga parameter), o PIVOT (bagong direksyon). Mga artifact ay awtomatikong vina-version. |
| **🤖 Multi-Agent Debate** | Ang pagbuo ng hypothesis, pagsusuri ng resulta, at peer review ay gumagamit ng nakabalangkas na multi-perspective na debate. |
| **🧬 Self-Learning** | Mga natutunan ay kinukuha bawat run (dahilan ng desisyon, mga babala sa runtime, mga anomalya sa sukatan) na may 30-araw na time-decay. Natututo ang mga susunod na run mula sa mga nakaraang pagkakamali. |
| **📚 Knowledge Base** | Bawat run ay nagtatayo ng nakabalangkas na KB sa 6 na kategorya (mga desisyon, eksperimento, natuklasan, literatura, mga tanong, mga review). |
| **🛡️ Sentinel Watchdog** | Background na monitor ng kalidad: pagtuklas ng NaN/Inf, pagkakatugma ng papel at ebidensya, pagmamarka ng kaugnayan ng pagsipi, bantay laban sa pagpeke. |

---

## 🦞 OpenClaw Integration

<table>
<tr>

**Ang AutoResearchClaw ay isang [OpenClaw](https://github.com/openclaw/openclaw)-compatible na serbisyo.** I-install ito sa OpenClaw at simulan ang autonomous na pananaliksik sa isang mensahe — o gamitin ito nang standalone sa pamamagitan ng CLI, Claude Code, o anumang AI coding assistant.

</tr>
</table>

### 🚀 Gamitin kasama ang OpenClaw (Inirerekomenda)

Kung ginagamit mo na ang [OpenClaw](https://github.com/openclaw/openclaw) bilang iyong AI assistant:

```
1️⃣  Ibahagi ang GitHub repo URL sa OpenClaw
2️⃣  Awtomatikong binabasa ng OpenClaw ang RESEARCHCLAW_AGENTS.md → nauunawaan ang pipeline
3️⃣  Sabihin: "Research [ang iyong paksa]"
4️⃣  Tapos na — ini-clone, ina-install, kino-configure, pinapatakbo ng OpenClaw, at ibinabalik ang mga resulta
```

**Iyon na.** Awtomatikong hinahawakan ng OpenClaw ang `git clone`, `pip install`, pag-setup ng config, at pagpapatakbo ng pipeline. Mag-chat ka lang.

<details>
<summary>💡 Ano ang nangyayari sa likod</summary>

1. Binabasa ng OpenClaw ang `RESEARCHCLAW_AGENTS.md` → natututo sa tungkulin ng research orchestrator
2. Binabasa ng OpenClaw ang `README.md` → nauunawaan ang pag-install at estruktura ng pipeline
3. Kinokopya ng OpenClaw ang `config.researchclaw.example.yaml` → `config.yaml`
4. Humihingi ng iyong LLM API key (o ginagamit ang iyong environment variable)
5. Pinapatakbo ang `pip install -e .` + `researchclaw run --topic "..." --auto-approve`
6. Ibinabalik ang papel, LaTeX, mga eksperimento, at mga sanggunian

</details>

### 🔌 OpenClaw Bridge (Advanced)

Para sa mas malalim na integrasyon, kasama sa AutoResearchClaw ang isang **bridge adapter system** na may 6 na opsyonal na kakayahan:

```yaml
# config.arc.yaml
openclaw_bridge:
  use_cron: true              # ⏰ Mga naka-iskedyul na run ng pananaliksik
  use_message: true           # 💬 Mga notification ng progreso (Discord/Slack/Telegram)
  use_memory: true            # 🧠 Pagpapanatili ng kaalaman sa iba't ibang session
  use_sessions_spawn: true    # 🔀 Mag-spawn ng mga parallel na sub-session para sa mga sabay-sabay na yugto
  use_web_fetch: true         # 🌐 Live na paghahanap sa web sa panahon ng literature review
  use_browser: false          # 🖥️ Koleksyon ng papel batay sa browser
```

Bawat flag ay nag-a-activate ng typed adapter protocol. Kapag nagbigay ang OpenClaw ng mga kakayahang ito, kinokonsumo ng mga adapter ang mga ito nang walang pagbabago sa code. Tingnan ang [`docs/integration-guide.md`](docs/integration-guide.md) para sa buong detalye.

### ACP (Agent Client Protocol)

Maaaring gumamit ang AutoResearchClaw ng **anumang ACP-compatible na coding agent** bilang LLM backend nito — walang kinakailangang API key. Ang agent ay nagkukomunika sa pamamagitan ng [acpx](https://github.com/openclaw/acpx), na nagpapanatili ng isang persistent na session sa lahat ng 23 yugto ng pipeline.

| Agent | Utos | Mga Tala |
|-------|---------|-------|
| Claude Code | `claude` | Anthropic |
| Codex CLI | `codex` | OpenAI |
| Gemini CLI | `gemini` | Google |
| OpenCode | `opencode` | SST |
| Kimi CLI | `kimi` | Moonshot |

```yaml
# config.yaml — Halimbawa ng ACP
llm:
  provider: "acp"
  acp:
    agent: "claude"   # Anumang ACP-compatible na agent CLI command
    cwd: "."          # Working directory para sa agent
  # Walang kinakailangang base_url o api_key — ang agent ang humahawak ng sarili nitong auth.
```

```bash
# Patakbuhin lamang — ang agent ay gumagamit ng sarili nitong mga kredensyal
researchclaw run --config config.yaml --topic "Your research idea" --auto-approve
```

### 🛠️ Iba Pang Paraan ng Pagpapatakbo

| Paraan | Paano |
|--------|-------|
| **Standalone CLI** | `researchclaw run --topic "..." --auto-approve` |
| **Python API** | `from researchclaw.pipeline import Runner; Runner(config).run()` |
| **Claude Code** | Binabasa ang `RESEARCHCLAW_CLAUDE.md` — sabihin lamang *"Run research on [topic]"* |
| **OpenCode** | Binabasa ang `.claude/skills/` — parehong natural language interface |
| **Anumang AI CLI** | Ibigay ang `RESEARCHCLAW_AGENTS.md` bilang konteksto → awtomatikong nag-bootstrap ang agent |

---

## 🔬 Pipeline: 23 Yugto, 8 Bahagi

```
Bahagi A: Pagtatakda ng Pananaliksik   Bahagi E: Pagpapatakbo ng Eksperimento
  1. TOPIC_INIT                          12. EXPERIMENT_RUN
  2. PROBLEM_DECOMPOSE                   13. ITERATIVE_REFINE  ← self-healing

Bahagi B: Paghahanap ng Literatura     Bahagi F: Pagsusuri at Desisyon
  3. SEARCH_STRATEGY                     14. RESULT_ANALYSIS    ← multi-agent
  4. LITERATURE_COLLECT  ← tunay na API  15. RESEARCH_DECISION  ← PIVOT/REFINE
  5. LITERATURE_SCREEN   [gate]
  6. KNOWLEDGE_EXTRACT                   Bahagi G: Pagsusulat ng Papel
                                         16. PAPER_OUTLINE
Bahagi C: Pagsasama ng Kaalaman         17. PAPER_DRAFT
  7. SYNTHESIS                           18. PEER_REVIEW        ← pagsusuri ng ebidensya
  8. HYPOTHESIS_GEN    ← debate          19. PAPER_REVISION

Bahagi D: Disenyo ng Eksperimento      Bahagi H: Panghuling Hakbang
  9. EXPERIMENT_DESIGN   [gate]          20. QUALITY_GATE      [gate]
 10. CODE_GENERATION                     21. KNOWLEDGE_ARCHIVE
 11. RESOURCE_PLANNING                   22. EXPORT_PUBLISH     ← LaTeX
                                         23. CITATION_VERIFY    ← pagsusuri ng kaugnayan
```

> **Mga gate stage** (5, 9, 20) ay humihinto para sa pag-apruba ng tao o awtomatikong inaprubahan gamit ang `--auto-approve`. Sa pagtanggi, ang pipeline ay nag-ro-rollback.

> **Mga decision loop**: Ang Yugto 15 ay maaaring mag-trigger ng REFINE (→ Yugto 13) o PIVOT (→ Yugto 8), na may awtomatikong pag-version ng mga artifact.

<details>
<summary>📋 Ano ang Ginagawa ng Bawat Bahagi</summary>

| Bahagi | Ano ang Nangyayari |
|-------|----------------|
| **A: Pagtatakda** | Binubulag ng LLM ang paksa sa isang nakabalangkas na puno ng problema na may mga tanong sa pananaliksik |
| **A+: Hardware** | Awtomatikong natutukoy ang GPU (NVIDIA CUDA / Apple MPS / CPU-only), nagbababala kung limitado ang lokal na hardware, ina-angkop ang pagbuo ng code |
| **B: Literatura** | Multi-source na paghahanap (OpenAlex → Semantic Scholar → arXiv) para sa tunay na mga papel, sinasala ayon sa kaugnayan, kumukuha ng mga knowledge card |
| **C: Pagsasama** | Binubuo ang mga natuklasan, natutukoy ang mga puwang sa pananaliksik, bumubuo ng mga masusubok na hypothesis sa pamamagitan ng multi-agent debate |
| **D: Disenyo** | Nagdisenyo ng plano ng eksperimento, bumubuo ng hardware-aware na runnable na Python (GPU tier → pagpili ng pakete), tinatantiya ang mga pangangailangan sa resources |
| **E: Pagpapatakbo** | Pinapatakbo ang mga eksperimento sa sandbox, natutukoy ang NaN/Inf at mga bug sa runtime, nagpapagaling ng code sa pamamagitan ng targeted na LLM repair |
| **F: Pagsusuri** | Multi-agent na pagsusuri ng mga resulta; autonomous na desisyon ng PROCEED / REFINE / PIVOT na may katwiran |
| **G: Pagsusulat** | Balangkas → bawat seksyong isinusulat (5,000-6,500 na salita) → mga peer review (na may pagkakatugma ng pamamaraan at ebidensya) → binabago na may length guard |
| **H: Panghuling Hakbang** | Quality gate, archival ng kaalaman, LaTeX export na may conference template, integridad ng pagsipi + beripikasyon ng kaugnayan |

</details>

---

## ✨ Mga Pangunahing Tampok

| Tampok | Paglalarawan |
|--------|------------|
| **📚 Multi-Source na Literatura** | Tunay na mga papel mula sa OpenAlex, Semantic Scholar at arXiv — pagpapalawak ng query, deduplication, circuit breaker na may graceful degradation |
| **🔍 4-Layer na Beripikasyon ng Pagsipi** | Pagsusuri ng arXiv ID → CrossRef/DataCite DOI → pagtutugma ng pamagat sa Semantic Scholar → LLM relevance scoring. Mga gawa-gawang sanggunian ay awtomatikong tinatanggal. |
| **🖥️ Hardware-Aware na Pagpapatakbo** | Awtomatikong natutukoy ang GPU (NVIDIA CUDA / Apple MPS / CPU-only) at ina-angkop ang pagbuo ng code, mga import, at sukat ng eksperimento |
| **🧪 Sandbox na Eksperimento** | AST-validated na code, immutable harness, NaN/Inf fast-fail, self-healing na pag-aayos, paulit-ulit na pagpapabuti (hanggang 10 round), partial result capture |
| **📝 Conference-Grade na Pagsusulat** | Mga template ng NeurIPS/ICML/ICLR, bawat seksyong isinusulat (5,000-6,500 na salita), bantay laban sa pagpeke, revision length guard, anti-disclaimer enforcement |
| **📐 Pagpapalit ng Template** | `neurips_2025`, `iclr_2026`, `icml_2026` — Markdown → LaTeX na may math, mga talahanayan, mga figure, cross-ref, `\cite{}` |
| **🚦 Mga Quality Gate** | 3 human-in-the-loop na gate (Mga Yugto 5, 9, 20) na may rollback. Laktawan gamit ang `--auto-approve`. |

---

## 🧠 MetaClaw Integration

**AutoResearchClaw + [MetaClaw](https://github.com/aiming-lab/MetaClaw) = Isang pipeline na natututo mula sa bawat run.**

Idinaragdag ng MetaClaw ang **cross-run knowledge transfer** sa AutoResearchClaw. Kapag pinagana, awtomatikong kumukuha ang pipeline ng mga aralin mula sa mga pagpalya at babala, kino-convert ang mga ito sa mga reusable na kasanayan, at ini-inject ang mga kasanayang iyon sa lahat ng 23 yugto ng pipeline sa mga susunod na run — kaya hindi na paulit-ulit ang parehong pagkakamali.

### Paano Ito Gumagana

```
Pinapatakbo ang Run N → mga pagpalya/babala ay nakuha bilang Mga Aralin
                      ↓
          MetaClaw Aralin → pag-convert sa Kasanayan
                      ↓
          Mga arc-* Skill file ay iniimbak sa ~/.metaclaw/skills/
                      ↓
Run N+1 → ini-inject ng build_overlay() ang mga kasanayan sa bawat LLM prompt
                      ↓
          Iniiwasan ng LLM ang mga kilalang pagkakamali → mas mataas na kalidad, mas kaunting retry
```

### Mabilis na Setup

```bash
# 1. I-install ang MetaClaw (kung wala pa)
pip install metaclaw

# 2. Paganahin sa iyong config
```

```yaml
# config.arc.yaml
metaclaw_bridge:
  enabled: true
  proxy_url: "http://localhost:30000/v1"    # MetaClaw proxy (opsyonal)
  skills_dir: "~/.metaclaw/skills"          # Kung saan iniimbak ang mga kasanayan
  fallback_url: "https://api.openai.com/v1" # Direktang LLM fallback
  fallback_api_key_env: "OPENAI_API_KEY"
  lesson_to_skill:
    enabled: true
    min_severity: "warning"                 # I-convert ang mga babala + error
    max_skills_per_run: 5
```

```bash
# 3. Patakbuhin gaya ng dati — transparent na gumagana ang MetaClaw
researchclaw run --config config.arc.yaml --topic "Your idea" --auto-approve
```

Pagkatapos ng bawat run, suriin ang `~/.metaclaw/skills/arc-*/SKILL.md` upang makita ang mga kasanayang natutunan ng iyong pipeline.

### Mga Resulta ng Eksperimento

Sa mga kontroladong A/B na eksperimento (parehong paksa, parehong LLM, parehong configuration):

| Sukatan | Baseline | Gamit ang MetaClaw | Pagpapabuti |
|--------|----------|---------------|-------------|
| Rate ng retry sa yugto | 10.5% | 7.9% | **-24.8%** |
| Bilang ng refine cycle | 2.0 | 1.2 | **-40.0%** |
| Pagkumpleto ng yugto ng pipeline | 18/19 | 19/19 | **+5.3%** |
| Pangkalahatang marka ng katatagan (composite) | 0.714 | 0.845 | **+18.3%** |

> Ang composite na marka ng katatagan ay isang weighted average ng rate ng pagkumpleto ng yugto (40%), pagbaba ng retry (30%), at kahusayan ng refine cycle (30%).

### Backward Compatibility

- **Default: NAKA-OFF.** Kung wala ang `metaclaw_bridge` o `enabled: false`, ang pipeline ay kumikilos nang eksakto gaya ng dati.
- **Walang bagong dependency.** Ang MetaClaw ay opsyonal — ang pangunahing pipeline ay gumagana nang wala ito.
- **Lahat ng 1,284 na kasalukuyang test ay pumasa** na may integration code na naroroon.

---

## ⚙️ Reference ng Configuration

<details>
<summary>I-click upang palawakin ang buong reference ng configuration</summary>

```yaml
# === Proyekto ===
project:
  name: "my-research"              # Identifier ng proyekto
  mode: "docs-first"               # docs-first | semi-auto | full-auto

# === Pananaliksik ===
research:
  topic: "..."                     # Paksa ng pananaliksik (kinakailangan)
  domains: ["ml", "nlp"]           # Mga larangan ng pananaliksik para sa paghahanap ng literatura
  daily_paper_count: 8             # Target na bilang ng papel bawat search query
  quality_threshold: 4.0           # Pinakamababang marka ng kalidad para sa mga papel

# === Runtime ===
runtime:
  timezone: "America/New_York"     # Para sa mga timestamp
  max_parallel_tasks: 3            # Limitasyon ng sabay-sabay na eksperimento
  approval_timeout_hours: 12       # Timeout ng gate stage
  retry_limit: 2                   # Bilang ng retry sa pagpalya ng yugto

# === LLM ===
llm:
  provider: "openai-compatible"    # "openai-compatible" (default) o "acp"
  base_url: "https://..."          # API endpoint (kinakailangan para sa openai-compatible)
  api_key_env: "OPENAI_API_KEY"    # Env var para sa API key (kinakailangan para sa openai-compatible)
  api_key: ""                      # O i-hardcode ang key dito
  primary_model: "gpt-4o"          # Pangunahing modelo
  fallback_models: ["gpt-4o-mini"] # Fallback chain
  s2_api_key: ""                   # Semantic Scholar API key (opsyonal, mas mataas na rate limit)
  acp:                             # Ginagamit lamang kapag provider: "acp"
    agent: "claude"                # ACP agent CLI command (claude, codex, gemini, atbp.)
    cwd: "."                       # Working directory para sa agent

# === Eksperimento ===
experiment:
  mode: "sandbox"                  # simulated | sandbox | docker | ssh_remote
  time_budget_sec: 300             # Pinakamataas na oras ng pagpapatakbo bawat run (default: 300s)
  max_iterations: 10               # Pinakamataas na bilang ng optimization iteration
  metric_key: "val_loss"           # Pangalan ng pangunahing sukatan
  metric_direction: "minimize"     # minimize | maximize
  sandbox:
    python_path: ".venv/bin/python"
    gpu_required: false
    allowed_imports: [math, random, json, csv, numpy, torch, sklearn]
    max_memory_mb: 4096
  docker:
    image: "researchclaw/experiment:latest"
    network_policy: "setup_only"   # none | setup_only | pip_only | full
    gpu_enabled: true
    memory_limit_mb: 8192
    auto_install_deps: true        # Auto-detect ng mga import → requirements.txt
  ssh_remote:
    host: ""                       # Hostname ng GPU server
    gpu_ids: []                    # Mga available na GPU ID
    remote_workdir: "/tmp/researchclaw_experiments"

# === Export ===
export:
  target_conference: "neurips_2025"  # neurips_2025 | iclr_2026 | icml_2026
  authors: "Anonymous"
  bib_file: "references"

# === Mga Prompt ===
prompts:
  custom_file: ""                  # Landas sa custom prompts YAML (walang laman = default)

# === Seguridad ===
security:
  hitl_required_stages: [5, 9, 20] # Mga yugto na nangangailangan ng pag-apruba ng tao
  allow_publish_without_approval: false
  redact_sensitive_logs: true

# === Knowledge Base ===
knowledge_base:
  backend: "markdown"              # markdown | obsidian
  root: "docs/kb"

# === Mga Notification ===
notifications:
  channel: "console"               # console | discord | slack
  target: ""

# === MetaClaw Bridge (Opsyonal) ===
metaclaw_bridge:
  enabled: false                   # Itakda sa true upang paganahin ang cross-run learning
  proxy_url: "http://localhost:30000/v1"  # MetaClaw proxy URL
  skills_dir: "~/.metaclaw/skills" # Kung saan iniimbak ang mga arc-* skill
  fallback_url: ""                 # Direktang LLM fallback kapag naka-down ang proxy
  fallback_api_key: ""             # API key para sa fallback endpoint
  lesson_to_skill:
    enabled: true                  # Auto-convert ng mga aralin sa mga kasanayan
    min_severity: "warning"        # Pinakamababang severity upang i-convert
    max_skills_per_run: 5          # Pinakamataas na bilang ng bagong kasanayan bawat run

# === OpenClaw Bridge ===
openclaw_bridge:
  use_cron: false                  # Mga naka-iskedyul na run ng pananaliksik
  use_message: false               # Mga notification ng progreso
  use_memory: false                # Pagpapanatili ng kaalaman sa iba't ibang session
  use_sessions_spawn: false        # Mag-spawn ng mga parallel na sub-session
  use_web_fetch: false             # Live na paghahanap sa web
  use_browser: false               # Koleksyon ng papel batay sa browser
```

</details>

---

## 🙏 Mga Pagpapasalamat

Inspirado ng:

- 🔬 [AI Scientist](https://github.com/SakanaAI/AI-Scientist) (Sakana AI) — Pioneer sa automated na pananaliksik
- 🧠 [AutoResearch](https://github.com/karpathy/autoresearch) (Andrej Karpathy) — End-to-end na automation ng pananaliksik
- 🌐 [FARS](https://analemma.ai/blog/introducing-fars/) (Analemma) — Fully Automated Research System

---

## 📄 Lisensya

MIT — tingnan ang [LICENSE](LICENSE) para sa mga detalye.

---

## 📌 Pagsipi

Kung natutulong sa iyo ang AutoResearchClaw, mangyaring isangguni:

```bibtex
@misc{liu2026autoresearchclaw,
  author       = {Liu, Jiaqi and Xia, Peng and Han, Siwei and Qiu, Shi and Zhang, Letian and Chen, Guiming  and Tu, Haoqin and Yang, Xinyu and and Zhou, Jiawei and Zhu, Hongtu and Li, Yun and Zhou, Yuyin and Zheng, Zeyu and Xie, Cihang and Ding, Mingyu and Yao, Huaxiu},
  title        = {AutoResearchClaw: Fully Autonomous Research from Idea to Paper},
  year         = {2026},
  organization = {GitHub},
  url          = {https://github.com/aiming-lab/AutoResearchClaw},
}
```

<p align="center">
  <sub>Ginawa nang may 🦞 ng koponan ng AutoResearchClaw</sub>
</p>

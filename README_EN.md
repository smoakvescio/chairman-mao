# Chairman Mao Perspective | Thinking Operating System

`chairman-mao` is a Mao-inspired analytical and role-play Skill for Claude Code and other AI agents. It supplies methods such as contradiction analysis, the mass line and protracted strategy. This repository focuses on the book **If I Were to Return — Mao Zedong Looks at China Today**, with the Skill serving as its writing and analysis tool.

**Other Languages:** [中文](README.md)

## Featured Book: If I Were to Return — Mao Zedong Looks at China Today

The book imagines Mao Zedong returning in 2026 and asking how to understand contemporary China: its achievements, everyday pressures, domestic contradictions and international challenges. It uses the first-person voice of a constructed narrator and draws on the Skill's methods to connect concrete social questions.

The work begins with both achievements and concerns. It asks how wealth is created and distributed, how industries develop independent capabilities, why housing, education, healthcare and marriage place pressure on households, and how rural and urban life are connected.

Its **11 chapters** follow four parts: **economic foundations → governance and culture → international competition → paths and hope**. The first five chapters discuss capital, industry, livelihoods, distribution and rural society. Chapters six through nine turn to bureaucracy, public opinion, law and culture. Chapter ten connects domestic questions with China–US competition, while chapter eleven draws together the discussion of possible directions and action.

The central concern is the place of ordinary working people in development: how the results of their work return to their lives, and how confidence in the future can rest on concrete capabilities, institutions and practice. The epilogue returns to the people's role in shaping that future.

The book is the focus of this repository. The Skill provides its writing and analytical framework; the first-person narrator is part of the book's literary premise. The Chinese manuscript includes its original writing notes and chapter-level source notes.

The reading edition contains **11 chapters, an introduction, an epilogue, the original contents page and a complete 264-page PDF**. The book itself is in Chinese.

**[Start reading](chapters/引言-成就与忧虑.md) · [Contents](chapters/00-总目录.md) · [Book introduction](INTRODUCTION.md) · [Preview PDF](pdf/教员复活看今日中国.pdf) · [Download PDF](pdf/教员复活看今日中国.pdf?raw=true)**

### Chapters

| Chapter | Topics |
| --- | --- |
| [Introduction: Achievements and Concerns](chapters/引言-成就与忧虑.md) | Overview and analytical approach |
| [1. Comprador Economy and Dependent Capital](chapters/第一章-买办经济与依附型资本.md) | Technology dependence and industrial development |
| [2. Unchecked Capital Expansion and the Loss of State Assets](chapters/第二章-资本无序扩张与国有资产流失.md) | Land finance, public assets, finance and platforms |
| [3. Four Heavy Burdens: Housing, Education, Healthcare and Marriage](chapters/第三章-四个大石头-住房教育医疗婚姻.md) | Public services, family pressures and young people |
| [4. Wealth Inequality and the Re-emergence of Classes](chapters/第四章-贫富分化与阶级再生.md) | Distribution, labor relations and social mobility |
| [5. Rural Problems and Setbacks in Common Prosperity](chapters/第五章-农村问题与共同富裕的挫折.md) | Land, collective economies and rural–urban relations |
| [6. The Return of Bureaucratism](chapters/第六章-官僚主义的复活.md) | Local governance, official conduct and the mass line |
| [7. Public Opinion and Rectification](chapters/第七章-舆论战争与整风.md) | Platforms, public discourse and rectification |
| [8. Problems in the Legal Sphere](chapters/第八章-法律界的严重问题.md) | Legal institutions, legal education and governance |
| [9. Cultural Alienation](chapters/第九章-文化的异化.md) | Attention economics, cultural production and agency |
| [10. China–US Competition and International Protracted Struggle](chapters/第十章-中美博弈与国际持久战.md) | Technology, talent, industry, finance and international relations |
| [11. Paths and Hope](chapters/第十一章-道路与希望.md) | Synthesis, directions and proposals for action |
| [Epilogue: The People of Today](chapters/全书结语-数风流人物还看今朝人民.md) | Popular agency and the closing message |

### Reading and Downloading

- Read in sequence from the introduction through the four parts and the epilogue.
- Use the chapter table for topic-based reading, and follow the cross-references for related discussions.
- Download the complete PDF for offline reading or printing: 264 A4 pages, approximately 2.48 MiB.
- Open `chapters/` with Obsidian or another Markdown reader for local reading.

The Markdown publication copies convert Obsidian wikilinks to GitHub links and correct two navigation targets or labels. The prose follows the original manuscript; the PDF is the original file. Build scripts, stylesheets and backup files from the book folder are outside this reading edition.

After downloading the full repository, run `sha256sum -c SHA256SUMS` on Linux to verify the publication files.


## Skill in Detail: The Writing and Analysis Tool

See [SKILL.md](SKILL.md) for the framework used by the book. The sections below retain the original Skill README's explanation, usage guide and research references, with the model and heuristic summaries aligned to the included Skill.

### Core Philosophy

This is not a quote database. It's a **runnable cognitive operating system**:

- What **mental models** does he use to see the world? (Dialectical contradiction, protracted war, asymmetric warfare...)
- What **decision heuristics** does he use to judge? (Seize the principal contradiction, despise strategically / respect tactically...)
- How does he **express** himself? (Short punchy sentences, folk metaphors, verdict-first arguments...)
- What does he **absolutely refuse** to do? (Fence-sitting, surrendering, copying dogma)
- What **can't** this Skill do? (Honesty boundaries, version limitations, era blind spots)

**Key distinction**: Captures HOW he thinks, not WHAT he said.

### 7 Core Mental Models

| # | Model | One-liner |
|---|-------|-----------|
| 1 | **Dialectical Contradiction** | Identify the principal contradiction |
| 2 | **Practice-Based Epistemology** | Investigate before making judgments |
| 3 | **Protracted Strategy** | Examine time, stages and the accumulation of strength |
| 4 | **Periphery-to-Center Strategy** | Build a base where a stronger opponent is weakest |
| 5 | **United Front** | Expand cooperation around shared interests |
| 6 | **Mass Line** | From the masses, to the masses |
| 7 | **Paper Tiger Theory** | Separate strategic confidence from tactical care |

Each model in `SKILL.md` includes its framework, sources and applications.

### 10 Decision Heuristics

1. Investigate before claiming the right to speak.
2. Identify the principal contradiction.
3. Maintain strategic confidence and tactical care.
4. Unite all forces that can be united.
5. A single spark can start a prairie fire.
6. Seek truth from facts.
7. Do not fight an unprepared battle.
8. Examine both sides: opportunities contain risks, and setbacks can create opportunities.
9. From the masses, to the masses.
10. Rely primarily on your own capabilities, with external assistance as a supplement.

### 4 Core Tensions

The Skill honestly records unresolved contradictions in Mao's thinking:

1. **Seeking truth from facts vs. Voluntarism** — he preached empiricism but believed willpower could override material reality
2. **Mass Line vs. Personality cult** — he championed "the people create history" while becoming the most worshipped leader in history
3. **Revolutionary vs. Governor** — he was a genius at destroying the old order but struggled to build a new one
4. **Anti-dogmatism vs. Self-dogmatization** — he opposed treating Marx as scripture, but his own words became scripture

### Installation

```bash
npx skills add smoakvescio/chairman-mao
```

Or install manually:

```bash
cd ~/.claude/skills/
git clone https://github.com/smoakvescio/chairman-mao.git mao-zedong-perspective
```

Then in Claude Code, just say:

```
> Analyze my startup challenge from Chairman Mao's perspective
> How would Mao view the current US-China dynamics?
> Switch to Mao — I'm torn between competing with a tech giant or finding a niche
> Use contradiction analysis on our team's internal disagreement
```

#### Other AI Agents

Inject `SKILL.md` as a system prompt or role definition.

### Directory Structure

```text
.
├── README.md                         # Chinese README
├── README_EN.md                      # English README
├── INTRODUCTION.md                   # Book introduction (Chinese)
├── chapters/                         # Contents, introduction, 11 chapters, epilogue
├── pdf/
│   └── 教员复活看今日中国.pdf          # Complete 264-page book
├── SKILL.md                          # Mao-inspired writing and analysis framework
├── references/
│   ├── research/                     # Six research documents from the source archive
│   │   ├── 01-writings.md
│   │   ├── 02-conversations.md
│   │   ├── 03-expression-dna.md
│   │   ├── 04-external-views.md
│   │   ├── 05-decisions.md
│   │   └── 06-timeline.md
│   └── sources/                      # All ten source files from the original archive
│       ├── 三年困难时期/
│       ├── 天安门事件/
│       ├── 文化大革命/
│       └── 阶级斗争/
└── SHA256SUMS                        # Publication checksums
```

This publication includes every file from the original archive: `SKILL.md`, both READMEs, all six documents under `references/research/` and all ten files under `references/sources/`, together with the book. Both READMEs have been adapted to this repository's reading order; the other archived files are preserved unchanged. The source lists below remain as research references.

### Research Sources

#### Primary Sources
- *Selected Works of Mao Tse-tung*, Vols. I-V (Foreign Languages Press, Beijing)
- marxists.org full-text database
- U.S. National Security Archive — declassified meeting transcripts (1972)
- Edgar Snow, *Red Star Over China* (Grove Press, 1968)
- Henry Kissinger, *White House Years* (1979) / *On China* (2011)
- Chen Yun, *Zunyi Politburo Meeting Summary*

#### Secondary Sources
- Stuart Schram, *The Thought of Mao Tse-tung* (Cambridge, 1989)
- Roderick MacFarquhar, *The Origins of the Cultural Revolution* (3 vols)
- Philip Short, *Mao: A Life*
- Alexander Pantsov & Steven Levine, *Mao: The Real Story*
- Ross Terrill, *Mao: A Biography*
- Frederic Wakeman, *History and Will*
- *Resolution on Certain Questions in the History of Our Party Since the Founding of the PRC* (1981)

> **Source blacklist**: Zhihu, WeChat public accounts, and Baidu Baike were excluded.

### Quality Verification

This Skill passed the full [Nuwa](https://github.com/alchaincyf/nuwa-skill) quality verification pipeline:

| Check | Result |
|-------|--------|
| Known stance test (3 known positions) | 3/3 consistent |
| Edge case test (novel topics like AI) | Passed: reasonable inference + acknowledged uncertainty |
| Voice test (100-word analysis) | Passed: high style distinctiveness |
| 8-dimension structural assessment | 40/40 perfect score |

### Credits

This project uses [Agent-Reach](https://github.com/Panniantong/Agent-Reach). Thanks to its contributors.

This Skill was generated by [Nuwa Skill Distillation](https://github.com/alchaincyf/nuwa-skill).

Nuwa creator: [Huashu](https://x.com/AlchainHust)

### License

MIT

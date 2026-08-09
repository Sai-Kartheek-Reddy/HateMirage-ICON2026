<table>
<tr>
<td width="160" valign="top">
<img src="assets/logo.png" alt="HateMirage logo" width="140">
</td>
<td valign="top">

# HateMirage

**Explainable Faux Hate Detection** — a shared task at **[ICON 2026](https://www.icon2026.org/)**.

🏆 **[Participate in the HateMirage ICON 2026 Shared Task on Codabench](https://www.codabench.org/competitions/17783/)**

[🌐 Website](https://sai-kartheek-reddy.github.io/HateMirage-ICON2026/) · [📄 Paper (LREC 2026)](https://arxiv.org/abs/2603.02684) · [📝 Register](https://forms.gle/zegMMsKUmpnhZ6t17) · [💬 Google Group](https://groups.google.com/g/hatemirage-icon2026)

</td>
</tr>
</table>

---

## About

Hate can hide inside comments that contain no slurs and trip no keyword filter, because the hostility is built on a fabricated premise rather than an explicit insult. **HateMirage** is a shared task on *Faux Hate*: content that is both hateful and rooted in debunked claims. Instead of a binary flag, systems are asked to explain **who** is targeted, **why** (Intent), and **what harm it could cause** (Implication).

The task is built on a corpus of 4,530 annotated comments, sourced from widely debunked claims traced to YouTube comment sections on international English news channels (English and Hindi-English code-mixed text included). Full construction details are in the paper, accepted at **LREC 2026**.

## Tasks

| | |
|---|---|
| **Task A: Target Identification** | Extract the entity or community a Faux Hate comment is actually directed against, even when the attack is implied rather than stated outright. |
| **Task B: Intent & Implication Generation** | Generate free-text explanations of the comment's Intent and its likely Implication, a structured generation problem rather than classification. |

Both tasks run on the same comments, so a single system can cover the full pipeline, or teams can enter either task on its own.

## Dataset

| Train | Validation | Test | Total |
|:---:|:---:|:---:|:---:|
| 3,171 | 453 | 906 | **4,530** |

## Key dates

See the [live timeline](https://sai-kartheek-reddy.github.io/HateMirage-ICON2026/#timeline) on the website; it auto-updates, so this README won't go stale trying to duplicate it.

## Get involved

1. **[Register your team](https://forms.gle/zegMMsKUmpnhZ6t17)**: tell us your team name and contact email.
2. **[Join the Google Group](https://groups.google.com/g/hatemirage-icon2026)**: training data, baselines, and announcements are shared there.

## Organizing Committee

- Sai Kartheek Reddy Kasu, Independent Researcher
- Shankar Biradar, Assistant Professor, MIT Manipal (MAHE)
- Sunil Saumya, Dean of Academics & Assistant Professor, IIIT Dharwad
- Md. Shad Akhtar, Assistant Professor, IIIT Delhi

## Contact

Questions about the task? Reach out to Contact: **[hatemirage-icon2026@googlegroups.com](mailto:hatemirage-icon2026@googlegroups.com)**


---

<p align="center"><sub>© 2026 HateMirage organizing committee</sub></p>

# Dhamma Vinaya Catalogue
A structured, data-ready catalogue of early Buddhist suttas, Vinaya rules, and Khandhaka sections.
Its aim is to support teachers, students, practitioners, and researchers with a structured, extensible map of the early Buddhist texts.

---

## Access & Versions

| Version                               | Description                                                                                                     | Link |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------|------|
| **Filterable view (read only)**       | Public online view where you can sort and filter, but not edit.                                                | https://docspace-yfcswq.onlyoffice.com/s/Vgk9_r7yPT5HdNM |
| **Public online – editable**          | Live online version for exploring and contributing. You can sort, filter, and edit the data.                   | https://docspace-yfcswq.onlyoffice.com/s/dkvYCLt9HT-9z5X |
| **OnlyOffice folder**                 | Folder with all related OnlyOffice documents (catalogue + supporting files).                                   | https://docspace-yfcswq.onlyoffice.com/s/ZhL2kBZbpB8QhkP |
| **Drive downloads (.xlsx / .tsv)**    | Download the catalogue as `.xlsx` or `.tsv` for offline work, analysis, or importing into other tools.         | https://drive.proton.me/urls/7HQ8WCVWPM#buHjiXWhFo7W |
| **GitHub – data and .tsv**            | Structured source data stored in version control. `.tsv` files for scripts, reproducible workflows, and reuse. | https://github.com/dhammavinaya-tools/dhamma-vinaya-catalogue |

---

## What’s in the catalogue?

The catalogue is built around three main sheets (or tables), each with one row per text or section:

- **Suttas** – discourses from the Nikāyas:
  - Nikaya/chapter/sutta codes
  - English & Pali titles
  - General themes and particular topics
  - Summaries, key excerpts, similes
  - Practice-related metadata (stage, training, aspect, teacher, audience, method, length, prominence)
  - Parallels (Nikāyas, Āgamas, Taishō, Sanskrit, Vinaya, others, partial parallels)
  - PTS references and suggested groupings

- **Pātimokkha rules** – monastic training rules:
  - Canonical VIN codes and PTS references
  - Gender (monks / nuns) and cross-correlations (bhikkhu ↔ bhikkhunī)
  - Pali and English rule names
  - Offense type and severity
  - Themes and topics
  - Full Pali and English training rules
  - No-offense conditions, offense factors (BD / BMC), notes, useful texts, Saṅgha acts, SuttaCentral link

- **Khandhakas (KD)** – Mahāvagga and Cullavagga sections:
  - KD number, Vagga code, VIN code, PTS reference, Bodhi pages
  - Pali and English section names
  - Main theme and subtopic
  - Summary
  - Key rules (prohibitions/duties) and allowances (permissions/relaxations)

---

## General instructions

A filterable catalogue of suttas and Vinaya passages:

- **Use column filters** to sort or select texts by theme, topic, length, teacher, audience, practice stage, or location in the Canon.
- **Use the Find tool** (`Ctrl+F` or `⌘+F`) to instantly locate keywords or specific terms anywhere in the sheet.

In public/shared versions, please:

- Clear any existing filters before you start.
- Clear filters again when you finish (so the next person sees the full catalogue).

---

### How to use the Suttas sheet

- Each row = **one sutta** (or sutta group).
- Use the filters on:
  - **NIKAYA / CHAPTER / SUTTA** to jump to a specific text.
  - **General Theme / Particular Topics** to find teachings by topic.
  - **Stage / Training / Aspect** to see where a sutta fits in the path (beginner → advanced, doctrinal / meditative / ethical, etc.).
  - **Teacher / Audience / Method / Length / Prominence** to find suttas suitable for talks, classes, or personal practice.
- The **Summary, Key Excerpt, Similes** columns give a quick feel for the content and style.
- **Nikayas / Āgamas / Taisho / Sanskrit / Vinaya / Others / Partial Parallels** show known parallels to other canons and texts.
- **PTS** gives page references; **Suggested / Nikaya name / Chapter name / Vagga** help group suttas into collections or study sets.

---

### How to use the Pātimokkha sheet

- Each row = **one rule** (or closely related rule set), with:
  - Canonical codes (VIN + PTS)
  - Short Pali & English names
  - Themes and topics
  - Full Pali & English training rule
  - No-offense conditions and offense factors (BD / BMC)
  - Notes, useful texts, and references
- Use filters to:
  - Select **monks / nuns** by gender.
  - Filter by **offense type** and **severity** to focus on specific classes of rules (Pārājika, Saṅghādisesa, Pācittiya, etc.).
  - Filter by **theme** or **topic** (e.g. celibacy, property, speech, community harmony).

---

### How to use the KD catalogue

- Filter by **KdNo** (KD1–KD22) to see all sections in one Khandhaka.
- Filter by **Vaggacode** (MV1–MV10, CV1–CV12) to follow the Mahāvagga / Cullavagga structure.
- Use **Theme** and **Topic** to find sections by subject (ordination, rains retreats, disputes, etc.).
- **Summary** gives a quick narrative description of each section.
- **Rules** lists key prohibitions / duties.
- **Allowances** lists permissions or relaxations.

---

## Contributing

**You are welcome to contribute, edit and add data in the public version** 

- improving summaries, themes, topics, and metadata;
- adding or correcting parallels and references;
- extending the coverage of texts and sections.

How to contribute:

- Suggest changes via GitHub issues or pull requests.
- Contribute directly in the **Public online – editable** version (see links above).
- Fork the `.tsv` data for your own projects and share improvements back.

Please keep changes **focused, cautious, and well-described**, especially for canonical references and parallels.

---

### Data formats

The data is available as:

- **.xlsx** – for spreadsheet work in OnlyOffice, LibreOffice, Excel, etc.
- **.tsv** – plain-text, script-friendly format for:
  - custom pipelines,
  - statistical analysis,
  - importing into databases or note-taking tools (e.g. Obsidian / Logseq).

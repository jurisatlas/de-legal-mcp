# Germany Legal Research MCP Server (`de-legal-mcp`)

**[Deutsch](#lang-de) | [English Documentation](#english-documentation)**

---

<a id="lang-de"></a>
## Rechts- und Rechtsprechungs-MCP-Server (`de-legal-mcp`) — Deutsch

### Über dieses Repository

Dieses Repository stellt einen Model Context Protocol (MCP) Server bereit, der Ihre KI-Anwendung (Claude Desktop, Cursor, Windsurf, VS Code / Copilot, Cline, Continue.dev oder Antigravity) direkt mit den amtlichen Gesetzesportalen und den mehrstufigen Rechtsprechungsdatenbanken für **Germany** (1. Instanz, Berufungs-/Kantons-/Oberlandesgerichte sowie Höchst- und Verfassungsgerichte) verbindet.

### Installation (Auswahl Ihrer KI-Anwendung)

1. **Herunterladen:** Klicken Sie oben rechts auf **`<> Code` -> `Download ZIP`** und entpacken Sie das Archiv auf Ihrem Computer.
2. **Installationsassistent starten:** Doppelklicken Sie auf **`Click_Here_To_Install_Windows.bat`** (Windows) oder **`Click_Here_To_Install_Mac.command`** (macOS).
3. **KI-Programm auswählen:** Wählen Sie im Fenster die von Ihnen genutzten KI-Programme aus (Claude, Cursor, Windsurf, VS Code, Antigravity), klicken Sie auf Installieren und starten Sie Ihre KI-Anwendung neu.

**Sicherheitshinweis:** Das Installationsprogramm arbeitet vollständig im Nur-Lese-Modus (Read-Only) und greift auf keinerlei persönliche Dateien auf Ihrem System zu.

### Gerichtsinstanzen und amtliche Datenquellen

| Instanz | Abgedeckte Gerichte |
|:---|:---|
| **1. Instanz (Eingangsgerichte)** | Amtsgerichte (AG), Landgerichte (LG), Verwaltungsgerichte (VG), Arbeitsgerichte (ArbG), Sozialgerichte (SG) & Finanzgerichte (FG) |
| **2. Instanz (Kantons-, Ober- und Berufungsgerichte)** | 24 Oberlandesgerichte (OLG / KG Berlin), Oberverwaltungsgerichte (OVG / VGH), Landesarbeitsgerichte (LAG) & Landessozialgerichte (LSG) across 16 Bundesländer |
| **3. Instanz (Höchst- und Verfassungsgerichte)** | Bundesverfassungsgericht (BVerfG), Bundesgerichtshof (BGH), Bundesverwaltungsgericht (BVerwG), Bundesfinanzhof (BFH), Bundesarbeitsgericht (BAG) & Bundessozialgericht (BSG) |

- **Gesetze im Internet (gesetze-im-internet.de) & Rechtsinformationen des Bundes:** [https://www.gesetze-im-internet.de](https://www.gesetze-im-internet.de) (`gesetze-im-internet.de`, `recht.bund.de`, `buzer.de`)
- **OpenLegalData.io (AG/LG/OLG/Federal) & Rechtsprechung im Internet + 16 Landesrechtsprechungsdatenbanken:** [https://de.openlegaldata.io](https://de.openlegaldata.io) (`rechtsprechung-im-internet.de`, `bundesgerichtshof.de`, `bundesverfassungsgericht.de`, `openjur.de`, `de.openlegaldata.io`)

---

<a id="english-documentation"></a>
## English Documentation

Model Context Protocol (MCP) server providing live, read-only access to **Germany (DE)** legislation, official gazettes, multi-tier judicial decisions (First Instance, Regional/Cantonal/Appellate, and Supreme/Constitutional courts, including HTML and PDF full-text extraction), and statutory citation verification across all major AI clients (**ChatGPT Desktop, OpenAI Codex CLI, Claude Desktop, Claude Code CLI, Cursor, Windsurf, VS Code / GitHub Copilot / Cline / Roo Code, Google Antigravity / Gemini CLI, Perplexity, and Continue.dev**).

---

### Interactive Desktop Setup (Select Your AI Assistant)

This package includes a graphical installer for legal practitioners and non-technical users that lets you select which AI application(s) you use:

1. **Download:** Click **`<> Code`** at the top right of this repository, select **`Download ZIP`**, and extract the folder to your computer.
2. **Run the Setup Utility:**
   - **Windows:** Double-click `Click_Here_To_Install_Windows.bat`
   - **macOS:** Double-click `Click_Here_To_Install_Mac.command`
3. **Select Your AI Client(s) & Connect:** Check the box(es) for the AI assistant(s) installed on your computer (**ChatGPT Desktop & OpenAI Codex CLI**, **Claude Desktop & Claude Code CLI**, **Cursor**, **Windsurf**, **VS Code / GitHub Copilot / Cline / Roo Code**, **Google Antigravity / Gemini CLI**, or **Perplexity / Continue.dev**), click **Install to Selected AI Clients**, and restart your selected AI application.

**System Integrity Note:** The setup utility operates strictly in read-only mode with respect to your personal files and documents. It installs an isolated Python runtime inside the extracted folder and registers the server entry only in the AI client configuration files you select.

---

### Multi-Tier Judicial Hierarchy & Live Indexed National Archives

This server performs live queries across the full judicial hierarchy and official legal archives of **Germany**, extracting full text from both HTML pages and official court/gazette PDF judgments:

| Judicial Tier | Covered Courts & Tribunals |
|:---|:---|
| **Tier 1 — First Instance** | Amtsgerichte (AG), Landgerichte (LG), Verwaltungsgerichte (VG), Arbeitsgerichte (ArbG), Sozialgerichte (SG) & Finanzgerichte (FG) |
| **Tier 2 — Regional / Cantonal / Appellate** | 24 Oberlandesgerichte (OLG / KG Berlin), Oberverwaltungsgerichte (OVG / VGH), Landesarbeitsgerichte (LAG) & Landessozialgerichte (LSG) across 16 Bundesländer |
| **Tier 3 — Supreme & Constitutional** | Bundesverfassungsgericht (BVerfG), Bundesgerichtshof (BGH), Bundesverwaltungsgericht (BVerwG), Bundesfinanzhof (BFH), Bundesarbeitsgericht (BAG) & Bundessozialgericht (BSG) |

#### Official Portals & Live Indexed Domains

- **National Legislation & Official Gazette:** Gesetze im Internet (gesetze-im-internet.de) & Rechtsinformationen des Bundes — [https://www.gesetze-im-internet.de](https://www.gesetze-im-internet.de)
  - *Indexed Legislation Domains:* `gesetze-im-internet.de`, `recht.bund.de`, `buzer.de`
- **Court Decisions & Jurisprudence Archives:** OpenLegalData.io (AG/LG/OLG/Federal) & Rechtsprechung im Internet + 16 Landesrechtsprechungsdatenbanken — [https://de.openlegaldata.io](https://de.openlegaldata.io)
  - *Indexed Judicial & Open Case Law Domains:* `rechtsprechung-im-internet.de`, `bundesgerichtshof.de`, `bundesverfassungsgericht.de`, `openjur.de`, `de.openlegaldata.io`

---

### Available MCP Tools

| Tool | Description |
|:---|:---|
| `search_legislation` | Searches enacted statutes, codes, decrees, and official gazette publications in Germany. |
| `search_case_law` | Searches national jurisprudence and open judicial archives for Germany. |
| `search_tiered_court_decisions` | Filters case law specifically by judicial instance (`first_instance`, `appellate_regional`, `supreme_constitutional`) or specific regional/cantonal/district court. |
| `list_court_hierarchy` | Returns the complete 3-tier court structure and supported regional court filters for Germany. |
| `get_legal_document_markdown` | Retrieves full statutory or judicial texts (both HTML and official `.pdf` court judgments) and converts them into clean Markdown. |
| `verify_citation` | Validates statutory and case law citations against official registries. |

---

<details>
<summary><b>Manual Configuration for Developers (Optional)</b></summary>

```json
{
  "mcpServers": {
    "de-legal-mcp": {
      "command": "uvx",
      "args": [
        "--from",
        "https://github.com/jurisatlas/de-legal-mcp/archive/refs/heads/main.zip",
        "de-legal-mcp"
      ]
    }
  }
}
```
</details>

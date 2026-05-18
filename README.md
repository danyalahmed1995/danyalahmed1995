<p align="center">
  <a href="https://github.com/danyalahmed1995">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=45&pause=1000&color=FF8C00&vCenter=true&center=true&width=600&lines=Danyal+Ahmed;AI+Systems+Architect;Senior+Unity+Engineer;Full-Stack+Developer" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <b>Game Dev & AI Systems Architect</b>  
  Specializing in autonomous agent orchestration, local RAG architectures, and scalable game systems.
</p>

<p align="center">
  <a href="https://github.com/danyalahmed1995">
    <img src="https://komarev.com/ghpvc/?username=danyalahmed1995&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
  </a>
</p>

---

## Open Source Contributions

### Major Project Contributions

| Organization | Repository | Contribution | Status |
|---|---|---|---|
| <img src="https://img.shields.io/badge/Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google" /> | [google/go-github](https://github.com/google/go-github) | Added GitHub App enterprise installation lookup support by implementing `AppsService.FindEnterpriseInstallation(ctx, enterprise)` for `GET /enterprises/{enterprise}/installation`, including regression coverage and review-driven API naming discussion. | [Merged PR #4230](https://github.com/google/go-github/pull/4230) |
| <img src="https://img.shields.io/badge/Microsoft-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> | [microsoft/agent-framework](https://github.com/microsoft/agent-framework) | Fixed an Anthropic provider integration regression by aligning `Microsoft.Extensions.AI` usage around `WebSearchToolResultContent.Results`. | [Merged PR #5709](https://github.com/microsoft/agent-framework/pull/5709) |
| <img src="https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta" /> | [facebook/docusaurus](https://github.com/facebook/docusaurus) | Fixed `@docusaurus/plugin-client-redirects` so external redirect targets are preserved instead of being modified by trailing-slash normalization. | [Merged PR #12004](https://github.com/facebook/docusaurus/pull/12004) |
| <img src="https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta" /> | [facebook/lexical](https://github.com/facebook/lexical) | Fixed nested `<br>` detection in pasted code blocks by returning recursive DOM tag matches and adding regression coverage. | [Merged PR #8487](https://github.com/facebook/lexical/pull/8487) |
| <img src="https://img.shields.io/badge/Microsoft-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> | [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | Fixed the Benchmarks GitHub Actions workflow by correcting package working directories and benchmark script paths. | [Merged PR #1826](https://github.com/microsoft/agent-governance-toolkit/pull/1826) |
| <img src="https://img.shields.io/badge/Microsoft-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> | [microsoft/PhiCookBook](https://github.com/microsoft/PhiCookBook) | Fixed an MLX Phi-4 reasoning notebook by creating the missing `./data` directory before exporting generated JSONL train/validation files. | [Merged PR #535](https://github.com/microsoft/PhiCookBook/pull/535) |
| <img src="https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta" /> | [facebook/docusaurus](https://github.com/facebook/docusaurus) | Fixed an incorrect `siteConfig.url` anchor in the i18n tutorial so it points to the correct Docusaurus config docs section. | [Merged PR #12002](https://github.com/facebook/docusaurus/pull/12002) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Clarified the CSS `<angle>` docs so unitless `0` is not presented as generally valid, preserving the legacy-context nuance and removing bare `0` from the null-angle equivalence example. | [Merged PR #44147](https://github.com/mdn/content/pull/44147) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Clarified the SVG `<feOffset>` filter example by making `filterUnits="userSpaceOnUse"` explicit, preventing readers from misreading `width` and `height` as user-space dimensions under the default `objectBoundingBox` behavior. | [Merged PR #44148](https://github.com/mdn/content/pull/44148) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Removed an outdated SVG `overflow` support warning after confirming the page’s Baseline/browser compatibility data showed broad support. | [Merged PR #44107](https://github.com/mdn/content/pull/44107) |

### Contribution Highlights

- **Google SDK Feature:** Added enterprise GitHub App installation lookup support to `google/go-github`, including tests and review discussion around long-term public API naming consistency.
- **AI Framework Regression Fix:** Fixed a Microsoft Agent Framework integration issue involving Anthropic provider support and `Microsoft.Extensions.AI` version alignment.
- **Redirect Behavior Fix:** Updated Docusaurus client redirects so absolute external URLs are preserved under `trailingSlash` handling.
- **Editor Import Fix:** Fixed a Lexical HTML paste/import edge case where nested `<br>` elements inside `<code>` were not detected as multiline code.
- **CI Workflow Fix:** Repaired a benchmark workflow in Microsoft’s Agent Governance Toolkit by aligning GitHub Actions working directories with the actual package structure.
- **Issue Discovery:** Reported the broken benchmark workflow path issue before submitting the fix.
- **AI Notebook Runtime Fix:** Fixed a Microsoft PhiCookBook MLX fine-tuning notebook that wrote JSONL outputs to a missing `./data` directory in fresh checkouts.
- **Docs Accuracy:** Fixed a Meta Docusaurus i18n tutorial link where `siteConfig.url` incorrectly pointed to the `baseUrl` docs anchor.
- **Issue Triage Support:** Helped validate and close a Continue.dev issue by confirming the fix behavior and providing follow-up context.
- **Mozilla CSS Spec Accuracy:** Clarified MDN’s CSS `<angle>` documentation so unitless `0` is not presented as generally valid, while preserving the legacy-context nuance and removing bare `0` from the null-angle example.
- **Mozilla SVG Filter Accuracy:** Clarified MDN’s `<feOffset>` example by explicitly setting `filterUnits="userSpaceOnUse"` so `width` and `height` are taught as user-space dimensions instead of relying on SVG’s default `objectBoundingBox` behavior.
- **Mozilla Docs Accuracy:** Removed an outdated SVG `overflow` warning from MDN after verifying the page’s Baseline/browser compatibility information showed broad browser support.

<p align="left">
  <a href="https://github.com/google/go-github/pull/4230">
    <img src="https://img.shields.io/badge/Google%20go--github-Merged%20PR%20%234230-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google go-github Merged PR 4230" />
  </a>
  <a href="https://github.com/microsoft/agent-framework/pull/5709">
    <img src="https://img.shields.io/badge/Microsoft%20OSS-Merged%20PR%20%235709-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft Agent Framework Merged PR 5709" />
  </a>
  <a href="https://github.com/facebook/docusaurus/pull/12004">
    <img src="https://img.shields.io/badge/Meta%20Docusaurus-Merged%20PR%20%2312004-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Docusaurus Merged PR 12004" />
  </a>
  <a href="https://github.com/facebook/lexical/pull/8487">
    <img src="https://img.shields.io/badge/Meta%20Lexical-Merged%20PR%20%238487-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Lexical Merged PR 8487" />
  </a>
  <a href="https://github.com/microsoft/agent-governance-toolkit/pull/1826">
    <img src="https://img.shields.io/badge/Microsoft%20OSS-Merged%20PR%20%231826-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft Agent Governance Toolkit Merged PR 1826" />
  </a>
  <a href="https://github.com/microsoft/PhiCookBook/pull/535">
    <img src="https://img.shields.io/badge/Microsoft%20PhiCookBook-Merged%20PR%20%23535-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft PhiCookBook Merged PR 535" />
  </a>
  <a href="https://github.com/facebook/docusaurus/pull/12002">
    <img src="https://img.shields.io/badge/Meta%20Docusaurus-Merged%20PR%20%2312002-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Docusaurus Merged PR 12002" />
  </a>
  <a href="https://github.com/microsoft/agent-governance-toolkit/issues/1825">
    <img src="https://img.shields.io/badge/Issue%20%231825-Workflow%20Path%20Bug-orange?style=for-the-badge&logo=github" alt="Issue 1825" />
  </a>
  <a href="https://github.com/continuedev/continue/issues/12312#issuecomment-4405784670">
    <img src="https://img.shields.io/badge/Continue.dev-Issue%20Triage%20Support-6f42c1?style=for-the-badge&logo=github" alt="Continue.dev Issue Triage Support" />
  </a>
  <a href="https://github.com/mdn/content/pull/44147">
    <img src="https://img.shields.io/badge/Mozilla%20MDN-Merged%20PR%20%2344147-FF7139?style=for-the-badge&logo=mozilla&logoColor=white" alt="Mozilla MDN Merged PR 44147" />
  </a>
  <a href="https://github.com/mdn/content/pull/44148">
    <img src="https://img.shields.io/badge/Mozilla%20MDN-Merged%20PR%20%2344148-FF7139?style=for-the-badge&logo=mozilla&logoColor=white" alt="Mozilla MDN Merged PR 44148" />
  </a>
  <a href="https://github.com/mdn/content/pull/44107">
    <img src="https://img.shields.io/badge/Mozilla%20MDN-Merged%20PR%20%2344107-FF7139?style=for-the-badge&logo=mozilla&logoColor=white" alt="Mozilla MDN Merged PR 44107" />
  </a>
</p>

---

## Tech Stack

### AI & Agentic Orchestration
<p align="left">
  <img src="https://skillicons.dev/icons?i=python,ts,nodejs" />
  <br>
  <img src="https://img.shields.io/badge/LangChain-121011?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-6D28D9?style=for-the-badge&logo=graph&logoColor=white" />
  <img src="https://img.shields.io/badge/CrewAI-000000?style=for-the-badge&logo=crewai&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenClaw-FF4500?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic_Claude-75013F?style=for-the-badge&logo=anthropic&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/ChromaDB-FFDC00?style=for-the-badge&logo=databricks&logoColor=black" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" />
  <img src="https://img.shields.io/badge/Llama_3.3-0668E1?style=for-the-badge&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/Tavily_AI-000000?style=for-the-badge&logo=openai&logoColor=white" />
</p>

### Game & Systems Engineering
<p align="left">
  <img src="https://skillicons.dev/icons?i=unity,cs,cpp" />
</p>

### Web & DevOps
<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,postgres,firebase,docker,git,github,aws" />
</p>

---

## Featured Portfolio

- **[Prompt Pipeline](https://github.com/danyalahmed1995/PromptPipeline)**: Turns large codebases into structured AI execution plans for ChatGPT & Codex.

- **[DocuVerdict](https://github.com/danyalahmed1995/DocuVerdict)**: AI-powered document extraction and QA workbench that validates structured outputs (JSON) against real-world data like invoices and reports.

- **[AgentRun Ledger](https://github.com/danyalahmed1995/AgentRun-Ledger)**: Local-first CLI + dashboard that tracks AI agent sessions with file changes, command logs, and auto-generated audit reports.

- **[RAG Regression Lab](https://github.com/danyalahmed1995/RAG-Regression-Lab)**: A regression testing and evaluation tool for RAG systems with a visual dashboard, deterministic scoring, and agent-aware logging to detect and prevent silent AI failures.

- **[OpsPilot](https://github.com/danyalahmed1995/OpsPilot)**: Internal Business Operations Platform.

---

## Current Focus

- Building practical AI tooling for agentic development workflows.
- Improving RAG evaluation, document extraction QA, and autonomous coding pipelines.
- Contributing focused fixes to open-source AI, agent, and developer-tooling ecosystems.

---

<p align="center">
  <b>AI systems, game engineering, and open-source fixes with receipts.</b>
</p>

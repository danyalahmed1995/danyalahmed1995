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


<p align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://streak-stats.demolab.com?user=danyalahmed1995&theme=github-dark-blue&hide_border=true&border_radius=8" alt="GitHub Streak" />
  </a>
</p>

---

## Open Source Contributions

### Major Project Contributions

<details>
<summary><strong>View major project contributions</strong></summary>

<br>

| Organization | Repository | Contribution | Status |
|---|---|---|---|
| <img src="https://img.shields.io/badge/Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google" /> | [google/go-github](https://github.com/google/go-github) | Added GitHub App enterprise installation lookup support by implementing `AppsService.FindEnterpriseInstallation(ctx, enterprise)` for `GET /enterprises/{enterprise}/installation`, including regression coverage and review-driven API naming discussion. | [Merged PR #4230](https://github.com/google/go-github/pull/4230) |
| <img src="https://img.shields.io/badge/Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google" /> | [google/adk-python](https://github.com/google/adk-python) | Fixed Windows test collection for `tests/unittests/tools/test_bash_tool.py` by adding a module-level Windows skip before importing Python's Unix-only `resource` module, with targeted Windows validation. | [Merged via Copybara #5680](https://github.com/google/adk-python/pull/5680) |
| <img src="https://img.shields.io/badge/Microsoft-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> | [microsoft/agent-framework](https://github.com/microsoft/agent-framework) | Fixed an Anthropic provider integration regression by aligning `Microsoft.Extensions.AI` usage around `WebSearchToolResultContent.Results`. | [Merged PR #5709](https://github.com/microsoft/agent-framework/pull/5709) |
| <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" /> | [huggingface/transformers](https://github.com/huggingface/transformers) | Guarded the continuous batching `DeviceMesh` import so Transformers can import cleanly when `torch.distributed` is unavailable, while preserving `DeviceMesh` support when distributed features are available. | [Merged PR #46205](https://github.com/huggingface/transformers/pull/46205) |
| <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" /> | [cloudflare/workers-sdk](https://github.com/cloudflare/workers-sdk) | Improved Wrangler API-token validation by detecting characters that cannot be encoded in the HTTP `Authorization` header, replacing the low-level `ByteString` failure with a clearer error and regression coverage. | [Merged PR #14002](https://github.com/cloudflare/workers-sdk/pull/14002) |
| <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" /> | [vercel/next.js](https://github.com/vercel/next.js) | Fixed the `Instrumentation.onRequestError` docs example so the error parameter is treated as `unknown` and narrowed before reading `message`/`digest`, matching the current Next.js type contract. | [Merged PR #94518](https://github.com/vercel/next.js/pull/94518) |
| <img src="https://img.shields.io/badge/Moby-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Moby" /> | [moby/moby](https://github.com/moby/moby) | Documented the `--firewall-backend` daemon option in the `dockerd` manual page after `dockerd --help` exposed the flag but `man dockerd` did not. | [Merged PR #52696](https://github.com/moby/moby/pull/52696) |
| <img src="https://img.shields.io/badge/KhronosGroup-AC162C?style=flat-square&logo=vulkan&logoColor=white" alt="KhronosGroup" /> | [KhronosGroup/Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) | Added 32-bit Ubuntu CI coverage using GCC/G++ multilib and `-m32` flags, keeping header generation and unit-test builds covered while skipping samples for the cross-compilation entry. | [Merged PR #2585](https://github.com/KhronosGroup/Vulkan-Hpp/pull/2585) |
| <img src="https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta" /> | [facebook/docusaurus](https://github.com/facebook/docusaurus) | Fixed `@docusaurus/plugin-client-redirects` so external redirect targets are preserved instead of being modified by trailing-slash normalization. | [Merged PR #12004](https://github.com/facebook/docusaurus/pull/12004) |
| <img src="https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta" /> | [facebook/lexical](https://github.com/facebook/lexical) | Fixed nested `<br>` detection in pasted code blocks by returning recursive DOM tag matches and adding regression coverage. | [Merged PR #8487](https://github.com/facebook/lexical/pull/8487) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mozilla/pdf.js](https://github.com/mozilla/pdf.js) | Fixed PDF.js text-layer selection/highlight alignment by preventing inherited `letter-spacing` and `word-spacing` from affecting the text layer and its hidden measurement canvas, with regression coverage for inherited spacing. | [Merged PR #21321](https://github.com/mozilla/pdf.js/pull/21321) |
| <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" /> | [gradio-app/gradio](https://github.com/gradio-app/gradio) | Fixed a `gr.Dataframe(datatype="auto")` runtime crash for empty and one-dimensional list/NumPy values by guarding datatype inference before two-dimensional indexing and adding regression coverage for edge cases missed by earlier closed PR attempts. | [Merged PR #13391](https://github.com/gradio-app/gradio/pull/13391) |
| <img src="https://img.shields.io/badge/KhronosGroup-005A9C?style=flat-square&logo=opengl&logoColor=white" alt="KhronosGroup" /> | [KhronosGroup/glTF](https://github.com/KhronosGroup/glTF) | Added the `PYTHA` vendor prefix to the glTF extension prefix registry for PYTHA Lab GmbH, closing the prefix request for future PYTHA-specific glTF extension work. | [Merged PR #2582](https://github.com/KhronosGroup/glTF/pull/2582) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/browser-compat-data](https://github.com/mdn/browser-compat-data) | Improved MDN Browser Compat Data lint tooling so targeted `lint:fix` runs fail when unfixable lint errors remain after the fixer runs, preventing false-success lint/pre-commit workflows after maintainer performance review. | [Merged PR #29690](https://github.com/mdn/browser-compat-data/pull/29690) |
| <img src="https://img.shields.io/badge/Microsoft-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> | [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | Fixed the Benchmarks GitHub Actions workflow by correcting package working directories and benchmark script paths. | [Merged PR #1826](https://github.com/microsoft/agent-governance-toolkit/pull/1826) |
| <img src="https://img.shields.io/badge/Microsoft-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft" /> | [microsoft/PhiCookBook](https://github.com/microsoft/PhiCookBook) | Fixed an MLX Phi-4 reasoning notebook by creating the missing `./data` directory before exporting generated JSONL train/validation files. | [Merged PR #535](https://github.com/microsoft/PhiCookBook/pull/535) |
| <img src="https://img.shields.io/badge/Meta-0866FF?style=flat-square&logo=meta&logoColor=white" alt="Meta" /> | [facebook/docusaurus](https://github.com/facebook/docusaurus) | Fixed an incorrect `siteConfig.url` anchor in the i18n tutorial so it points to the correct Docusaurus config docs section. | [Merged PR #12002](https://github.com/facebook/docusaurus/pull/12002) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Documented cross-browser Manifest V3 background fallback behavior in the WebExtensions `background` manifest docs by explaining how extensions can pair `background.scripts` with `background.service_worker`, while clarifying when `background.preferred_environment` is needed. | [Merged PR #44108](https://github.com/mdn/content/pull/44108) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Clarified the CSS `<angle>` docs so unitless `0` is not presented as generally valid, preserving the legacy-context nuance and removing bare `0` from the null-angle equivalence example. | [Merged PR #44147](https://github.com/mdn/content/pull/44147) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Clarified the SVG `<feOffset>` filter example by making `filterUnits="userSpaceOnUse"` explicit, preventing readers from misreading `width` and `height` as user-space dimensions under the default `objectBoundingBox` behavior. | [Merged PR #44148](https://github.com/mdn/content/pull/44148) |
| <img src="https://img.shields.io/badge/Mozilla-FF7139?style=flat-square&logo=mozilla&logoColor=white" alt="Mozilla" /> | [mdn/content](https://github.com/mdn/content) | Removed an outdated SVG `overflow` support warning after confirming the page’s Baseline/browser compatibility data showed broad support. | [Merged PR #44107](https://github.com/mdn/content/pull/44107) |

</details>

### Contribution Highlights

<details>
<summary><strong>View contribution highlights</strong></summary>

<br>

- **Google SDK Feature:** Added enterprise GitHub App installation lookup support to `google/go-github`, including tests and review discussion around long-term public API naming consistency.
- **Google ADK Python Test Fix:** Fixed Windows test collection for `tests/unittests/tools/test_bash_tool.py` by adding a module-level Windows skip before importing Python's Unix-only `resource` module, with targeted Windows/Python validation; merged via Copybara.
- **AI Framework Regression Fix:** Fixed a Microsoft Agent Framework integration issue involving Anthropic provider support and `Microsoft.Extensions.AI` version alignment.
- **Hugging Face Transformers Import Fix:** Guarded the continuous-batching `DeviceMesh` import so Transformers no longer fails to import when `torch.distributed` is unavailable, while keeping distributed support active when available.
- **Cloudflare Wrangler Error Handling:** Replaced a cryptic `ByteString` failure for invalid `CLOUDFLARE_API_TOKEN` characters with a clearer Wrangler error, backed by regression coverage for problematic token characters.
- **Next.js Instrumentation Docs Fix:** Corrected the `onRequestError` docs/example so the error parameter is handled as `unknown` and narrowed before reading `message` or `digest`, aligning the example with the current type contract.
- **Moby Man Page Docs:** Documented the `dockerd --firewall-backend` daemon option in the Moby manual page after the flag appeared in `dockerd --help` but was missing from `man dockerd`.
- **Khronos Vulkan-Hpp CI Coverage:** Added 32-bit Ubuntu CI coverage using GCC/G++ multilib and `-m32`, exercising header generation and unit-test builds while skipping samples for the cross-compilation entry.
- **Redirect Behavior Fix:** Updated Docusaurus client redirects so absolute external URLs are preserved under `trailingSlash` handling.
- **Editor Import Fix:** Fixed a Lexical HTML paste/import edge case where nested `<br>` elements inside `<code>` were not detected as multiline code.
- **PDF.js Text Layer Fix:** Prevented inherited `letter-spacing` and `word-spacing` from affecting PDF.js text-layer positioning, keeping selection/highlight alignment stable and adding regression coverage.
- **Hugging Face / Gradio Runtime Fix:** Fixed a `gr.Dataframe(datatype="auto")` crash for empty and one-dimensional list/NumPy inputs, adding regression tests for the full edge-case family after two earlier PR attempts were closed.
- **Khronos glTF Registry Update:** Added the `PYTHA` vendor prefix to the KhronosGroup/glTF extension prefix registry, closing PYTHA Lab GmbH’s prefix request for future glTF extension work.
- **Mozilla BCD Tooling Fix:** Improved MDN Browser Compat Data `lint:fix` so targeted fixer runs fail when unfixable lint errors remain, preventing false-success lint/pre-commit workflows after maintainer discussion and performance testing.
- **CI Workflow Fix:** Repaired a benchmark workflow in Microsoft’s Agent Governance Toolkit by aligning GitHub Actions working directories with the actual package structure.
- **Issue Discovery:** Reported the broken benchmark workflow path issue before submitting the fix.
- **AI Notebook Runtime Fix:** Fixed a Microsoft PhiCookBook MLX fine-tuning notebook that wrote JSONL outputs to a missing `./data` directory in fresh checkouts.
- **Docs Accuracy:** Fixed a Meta Docusaurus i18n tutorial link where `siteConfig.url` incorrectly pointed to the `baseUrl` docs anchor.
- **Issue Triage Support:** Helped validate and close a Continue.dev issue by confirming the fix behavior and providing follow-up context.
- **AWS CLI Issue Triage:** Helped close an AWS CLI `ssm start-session` port-forwarding issue by identifying and communicating the likely ownership boundary around local port bind failures and Session Manager plugin behavior.
- **Supabase PostgREST Issue Triage:** Helped close a Supabase issue involving persistent PostgREST `PGRST002` schema-cache 503 failures by narrowing the report around PostgREST recovery and infrastructure-side investigation.
- **Supabase Auth UI Issue Triage:** Helped close a Supabase Auth Users UI race-condition report by clarifying the async store-mutator concern and its actionability boundary.
- **Mozilla WebExtensions MV3 Docs:** Documented cross-browser Manifest V3 background fallback behavior by clarifying how `background.scripts` and `background.service_worker` work together, plus when `background.preferred_environment` is actually needed.
- **Mozilla CSS Spec Accuracy:** Clarified MDN’s CSS `<angle>` documentation so unitless `0` is not presented as generally valid, while preserving the legacy-context nuance and removing bare `0` from the null-angle example.
- **Mozilla SVG Filter Accuracy:** Clarified MDN’s `<feOffset>` example by explicitly setting `filterUnits="userSpaceOnUse"` so `width` and `height` are taught as user-space dimensions instead of relying on SVG’s default `objectBoundingBox` behavior.
- **Mozilla Docs Accuracy:** Removed an outdated SVG `overflow` warning from MDN after verifying the page’s Baseline/browser compatibility information showed broad browser support.

</details>
<p align="left">
  <a href="https://github.com/google/go-github/pull/4230">
    <img src="https://img.shields.io/badge/Google%20go--github-Merged%20PR%20%234230-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google go-github Merged PR 4230" />
  </a>
  <a href="https://github.com/google/adk-python/pull/5680">
    <img src="https://img.shields.io/badge/Google%20ADK--Python-Merged%20via%20Copybara%20%235680-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google ADK Python Merged via Copybara 5680" />
  </a>
  <a href="https://github.com/microsoft/agent-framework/pull/5709">
    <img src="https://img.shields.io/badge/Microsoft%20OSS-Merged%20PR%20%235709-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft Agent Framework Merged PR 5709" />
  </a>
  <a href="https://github.com/huggingface/transformers/pull/46205">
    <img src="https://img.shields.io/badge/Hugging%20Face%20Transformers-Merged%20PR%20%2346205-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face Transformers Merged PR 46205" />
  </a>
  <a href="https://github.com/cloudflare/workers-sdk/pull/14002">
    <img src="https://img.shields.io/badge/Cloudflare%20Workers--SDK-Merged%20PR%20%2314002-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare Workers SDK Merged PR 14002" />
  </a>
  <a href="https://github.com/vercel/next.js/pull/94518">
    <img src="https://img.shields.io/badge/Vercel%20Next.js-Merged%20PR%20%2394518-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Next.js Merged PR 94518" />
  </a>
  <a href="https://github.com/moby/moby/pull/52696">
    <img src="https://img.shields.io/badge/Moby-Merged%20PR%20%2352696-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Moby Merged PR 52696" />
  </a>
  <a href="https://github.com/KhronosGroup/Vulkan-Hpp/pull/2585">
    <img src="https://img.shields.io/badge/KhronosGroup%20Vulkan--Hpp-Merged%20PR%20%232585-AC162C?style=for-the-badge&logo=vulkan&logoColor=white" alt="KhronosGroup Vulkan-Hpp Merged PR 2585" />
  </a>
  <a href="https://github.com/facebook/docusaurus/pull/12004">
    <img src="https://img.shields.io/badge/Meta%20Docusaurus-Merged%20PR%20%2312004-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Docusaurus Merged PR 12004" />
  </a>
  <a href="https://github.com/facebook/lexical/pull/8487">
    <img src="https://img.shields.io/badge/Meta%20Lexical-Merged%20PR%20%238487-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Lexical Merged PR 8487" />
  </a>
  <a href="https://github.com/mozilla/pdf.js/pull/21321">
    <img src="https://img.shields.io/badge/Mozilla%20pdf.js-Merged%20PR%20%2321321-FF7139?style=for-the-badge&logo=mozilla&logoColor=white" alt="Mozilla pdf.js Merged PR 21321" />
  </a>
  <a href="https://github.com/gradio-app/gradio/pull/13391">
    <img src="https://img.shields.io/badge/Hugging%20Face%20Gradio-Merged%20PR%20%2313391-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face Gradio Merged PR 13391" />
  </a>
  <a href="https://github.com/KhronosGroup/glTF/pull/2582">
    <img src="https://img.shields.io/badge/KhronosGroup%20glTF-Merged%20PR%20%232582-005A9C?style=for-the-badge&logo=opengl&logoColor=white" alt="KhronosGroup glTF Merged PR 2582" />
  </a>
  <a href="https://github.com/open-telemetry/opentelemetry-js-contrib/issues/3518#issuecomment-4532505005">
    <img src="https://img.shields.io/badge/OpenTelemetry-Issue%20%233518%20Closed-4F3BAB?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry Issue 3518 Closed" />
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
  <a href="https://github.com/aws/aws-cli/issues/10320#issuecomment-4544227483">
    <img src="https://img.shields.io/badge/AWS%20CLI-Issue%20%2310320%20Closed-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS CLI Issue 10320 Closed" />
  </a>
  <a href="https://github.com/supabase/supabase/issues/46237#issuecomment-4624939520">
    <img src="https://img.shields.io/badge/Supabase-Issue%20%2346237%20Closed-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase Issue 46237 Closed" />
  </a>
  <a href="https://github.com/supabase/supabase/issues/46547#event-26295737193">
    <img src="https://img.shields.io/badge/Supabase-Issue%20%2346547%20Closed-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase Issue 46547 Closed" />
  </a>
  <a href="https://github.com/mdn/browser-compat-data/pull/29690">
    <img src="https://img.shields.io/badge/Mozilla%20BCD-Merged%20PR%20%2329690-FF7139?style=for-the-badge&logo=mozilla&logoColor=white" alt="Mozilla BCD Merged PR 29690" />
  </a>
  <a href="https://github.com/mdn/content/pull/44108">
    <img src="https://img.shields.io/badge/Mozilla%20MDN-Merged%20PR%20%2344108-FF7139?style=for-the-badge&logo=mozilla&logoColor=white" alt="Mozilla MDN Merged PR 44108" />
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

* <a href="https://github.com/danyalahmed1995/EXT"><img src="assets/ext-icon.png" width="42" align="center" alt="EXT icon" /></a> **[EXT](https://github.com/danyalahmed1995/EXT)**: Local-first Markdown and plain text workspace for organizing, reading, and editing existing `.md` and `.txt` files directly from the filesystem. Built with Tauri, Rust, React, Vite, and CodeMirror.

* **[Prompt Pipeline](https://github.com/danyalahmed1995/PromptPipeline)**: Turns large codebases into structured AI execution plans for ChatGPT & Codex.

* **[DocuVerdict](https://github.com/danyalahmed1995/DocuVerdict)**: AI-powered document extraction and QA workbench that validates structured outputs against real-world data like invoices and reports.

* **[AgentRun Ledger](https://github.com/danyalahmed1995/AgentRun-Ledger)**: Local-first CLI and dashboard that tracks AI agent sessions with file changes, command logs, and auto-generated audit reports.

* **[RAG Regression Lab](https://github.com/danyalahmed1995/RAG-Regression-Lab)**: Regression testing and evaluation tool for RAG systems with a visual dashboard, deterministic scoring, and agent-aware logging.

* **[OpsPilot](https://github.com/danyalahmed1995/OpsPilot)**: Internal business operations platform.


---

## Current Focus

- Building practical AI tooling for agentic development workflows.
- Improving RAG evaluation, document extraction QA, and autonomous coding pipelines.
- Contributing focused fixes to open-source AI, agent, and developer-tooling ecosystems.

---

<p align="center">
  <b>AI systems, game engineering, and open-source fixes with receipts.</b>
</p>
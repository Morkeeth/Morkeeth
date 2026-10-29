# Oscar’s tools for agents

Checked29 October2026. This is a public-source discovery and usage catalog. Commands are relative to the linked repository root unless an installation is stated. Read that repository’s README and existing AGENTS.md before running it; install only its documented prerequisites.

Live means a current public tool or asset, not that every integration was tested. Frozen entries are retained references. Killed entries must stay closed. **Unverified** means current operational status or the named runtime has not been established; a working help screen proves only CLI availability.

This catalog contains no private records, credentials, personal source paths or financial figures. Live provider calls, personal-data access, posting, publishing, deployment and submissions need separate user authorization. The checks below used public source, synthetic fixtures and a temporary empty home with provider credentials absent.

## Choose by task

- Recover coding work: [Transcripto](#transcripto), [STRIVE](#strive).
- Check instructions and evidence: [Helicon](#mountain-of-helicon), [Agent Science](#agent-science), [Witness](#agent-work-record-witness-ata).
- Find and evaluate skills: [SkillWire](#skillwire), [MAGNET](#agents-for-humans).
- Inspect app journeys: [Agentic Swarm Simulator](#agentic-swarm-studio), [ReadyCounter](#readycounter).
- Inspect usage or fleets: [Local Token Inventory](#where-did-the-tokens-go-public), [fleet](#fleet).

## Catalog

<a id="transcripto"></a>
### Transcripto

Inspect recorded coding-agent requests, tool calls and results.

- **Use when:** Recover what happened in a coding task; start with the synthetic replay before reading user-authorized local records.
- **Entry:** `python3 -m transcripto replay --demo --json`. Source: [transcripto.py](https://github.com/Morkeeth/transcripto/blob/c8a8e6112a5cb6c6a08cb07d5f8b7c5bf9eaa878/transcripto.py).
- **Repository:** [Morkeeth/transcripto](https://github.com/Morkeeth/transcripto).
- **Status:** live.
- **Proof checked29 Oct:** Synthetic replay passed; recorded tool status is not task correctness. Additional reproducible test source: [experiments/theme-replay/tests/test_stage0_live.py](https://github.com/Morkeeth/transcripto/blob/c8a8e6112a5cb6c6a08cb07d5f8b7c5bf9eaa878/experiments/theme-replay/tests/test_stage0_live.py).

<a id="skillwire"></a>
### SkillWire

Find, inspect and download pinned public agent skills.

- **Use when:** Choose a skill for a concrete task, inspect its source, then use the downloadable local paired-evaluation kit before claiming benefit.
- **Entry:** `python3 scripts/recheck_public_outcomes.py`. Source: [scripts/recheck_public_outcomes.py](https://github.com/Morkeeth/skillwire/blob/ce804b6d695db3abeb0d4e663382ae7ad6920c99/scripts/recheck_public_outcomes.py).
- **Repository:** [Morkeeth/skillwire](https://github.com/Morkeeth/skillwire).
- **Status:** live.
- **Proof checked29 Oct:** Saved public outcomes rechecked with zero model calls. This is replay, not a fresh skill-efficacy study. Additional reproducible test source: [tests/test_downloaded_eval_kit.py](https://github.com/Morkeeth/skillwire/blob/ce804b6d695db3abeb0d4e663382ae7ad6920c99/tests/test_downloaded_eval_kit.py).

<a id="strive"></a>
### STRIVE

Capture coding-agent sessions as private previews and optional shared run cards.

- **Use when:** Prepare a source-backed run preview; keep publication and audience changes under the user’s control.
- **Entry:** `python3 -m agentgrinder --help`. Source: [agentgrinder/__main__.py](https://github.com/Morkeeth/strive/blob/50558891d5e976599ac45189f453fa60c25ad95d/agentgrinder/__main__.py).
- **Repository:** [Morkeeth/strive](https://github.com/Morkeeth/strive).
- **Status:** live.
- **Proof checked29 Oct:** CLI help and the day-card checks passed; hosted persistence and publishing were not exercised. Additional reproducible test source: [templates/grokbot/post-agent-run/scripts/test_contract.py](https://github.com/Morkeeth/strive/blob/50558891d5e976599ac45189f453fa60c25ad95d/templates/grokbot/post-agent-run/scripts/test_contract.py).

<a id="taste-city"></a>
### Taste City

Explore culture and compare ideas with Qloo taste-graph evidence.

- **Use when:** Explore the explicitly fictional no-key sample or build a cultural shortlist; a live Qloo request requires configured access and permission.
- **Entry:** `python3 build_static.py`. Source: [build_static.py](https://github.com/Morkeeth/taste-city/blob/f5ce9267429909feb4cbb756e071372b706e77f6/build_static.py).
- **Repository:** [Morkeeth/taste-city](https://github.com/Morkeeth/taste-city).
- **Status:** live.
- **Proof checked29 Oct:** Static build passed without provider credentials; live Qloo behavior and frontier-model superiority were not tested. Additional reproducible test source: [test_agent_planner.py](https://github.com/Morkeeth/taste-city/blob/f5ce9267429909feb4cbb756e071372b706e77f6/test_agent_planner.py).

<a id="agentic-swarm-studio"></a>
### Agentic Swarm Simulator

Let model visitors rehearse a web task and return a recheckable repair path.

- **Use when:** Inspect recorded failures and repair evidence; use the README’s no-key recheck before authorizing any new model visitor.
- **Entry:** `python3 -m sim.repair_loop --help`. Source: [sim/repair_loop.py](https://github.com/Morkeeth/agentic-swarm-studio/blob/22bea7d133be7d2e6deceade08e524034678623c/sim/repair_loop.py).
- **Repository:** [Morkeeth/agentic-swarm-studio](https://github.com/Morkeeth/agentic-swarm-studio).
- **Status:** live.
- **Proof checked29 Oct:** Repair-loop help passed. A new model run or full browser repair recheck was not performed. Additional reproducible test source: [examples/overturn/test_returned_path.py](https://github.com/Morkeeth/agentic-swarm-studio/blob/22bea7d133be7d2e6deceade08e524034678623c/examples/overturn/test_returned_path.py).

<a id="where-did-the-tokens-go-public"></a>
### Local Token Inventory

Inspect local coding-agent usage with a synthetic demo and an agent CLI.

- **Use when:** Check harness coverage or review a synthetic usage example; connecting real local records requires the user’s consent.
- **Entry:** `python3 -m tokens.agent --help`. Source: [tokens/agent.py](https://github.com/Morkeeth/where-did-the-tokens-go-public/blob/c53e41802288bbcda0a0fbdb22ec8168d635c039/tokens/agent.py).
- **Repository:** [Morkeeth/where-did-the-tokens-go-public](https://github.com/Morkeeth/where-did-the-tokens-go-public).
- **Status:** live.
- **Proof checked29 Oct:** Agent CLI help and the two product tests passed; no real user records were imported. Additional reproducible test source: [tests/test_local_server.py](https://github.com/Morkeeth/where-did-the-tokens-go-public/blob/c53e41802288bbcda0a0fbdb22ec8168d635c039/tests/test_local_server.py).

<a id="mountain-of-helicon"></a>
### Mountain of Helicon

Check agent rule files against repository facts and inspect memory provenance.

- **Use when:** Before following repository instructions, check whether their paths and claims still match the checkout.
- **Entry:** `python3 -m helicon --help`. Source: [helicon/__main__.py](https://github.com/Morkeeth/mountain-of-helicon/blob/9d31a58bb08995590991a4454998d57ce2b27a08/helicon/__main__.py).
- **Repository:** [Morkeeth/mountain-of-helicon](https://github.com/Morkeeth/mountain-of-helicon).
- **Status:** live.
- **Proof checked29 Oct:** Help passed. Review, CI and memory experiments have separate commands in the README; no model-backed judgment was run. Additional reproducible test source: [bench/adversarial-2026-09-22/fixtures/c1_renamed_function/grader/test_hidden.py](https://github.com/Morkeeth/mountain-of-helicon/blob/9d31a58bb08995590991a4454998d57ce2b27a08/bench/adversarial-2026-09-22/fixtures/c1_renamed_function/grader/test_hidden.py).

<a id="agent-science"></a>
### Agent Science

Keep research questions, cited evidence, decisions and repository experiments together.

- **Use when:** Research a builder decision, inspect exact source evidence and retain a revisable decision; start locally without live discovery.
- **Entry:** `python3 -m clearance --help`. Source: [clearance/__main__.py](https://github.com/Morkeeth/agent-science/blob/df794ee218f4a4d972828abf4f92127d44ec184d/clearance/__main__.py).
- **Repository:** [Morkeeth/agent-science](https://github.com/Morkeeth/agent-science).
- **Status:** frozen.
- **Proof checked29 Oct:** CLI help and14 evidence-case tests passed. Frozen refers to the project’s build scope, not a broken CLI. Live search was not run. Additional reproducible test source: [tests/test_adk_default_path.py](https://github.com/Morkeeth/agent-science/blob/df794ee218f4a4d972828abf4f92127d44ec184d/tests/test_adk_default_path.py).

<a id="arc-agi-3-probe"></a>
### ARC KAGGLE Probe

Record no-op actions and compare guarded versus unguarded game agents.

- **Use when:** Reproduce a recorded action-efficiency experiment; read the negative results before proposing a solver improvement.
- **Entry:** `python3 harness.py --help`. Source: [harness.py](https://github.com/Morkeeth/arc-agi-3-probe/blob/640d5254dabb760103e467b3ce0e208127e2434b/harness.py).
- **Repository:** [Morkeeth/arc-agi-3-probe](https://github.com/Morkeeth/arc-agi-3-probe).
- **Status:** live.
- **Proof checked29 Oct:** Harness help passed. No game run, notebook submission or score improvement was attempted. Additional reproducible test source: [tests/test_ab_l4.py](https://github.com/Morkeeth/arc-agi-3-probe/blob/640d5254dabb760103e467b3ce0e208127e2434b/tests/test_ab_l4.py).

<a id="duck-control"></a>
### Duck Control

Provide a readable Kaggle notebook around the externally supplied Duck harness.

- **Use when:** Inspect the notebook, declared datasets and runtime requirements before a separately authorized Kaggle run.
- **Entry:** `duck-control.ipynb`. Source: [duck-control.ipynb](https://github.com/Morkeeth/duck-control/blob/64c8ab83454894c7369641ebc107a8f235522b83/duck-control.ipynb).
- **Repository:** [Morkeeth/duck-control](https://github.com/Morkeeth/duck-control).
- **Status:** live.
- **Proof checked29 Oct:** Notebook and kernel-metadata.json exist and parse as JSON. Runtime and external solver execution remain UNVERIFIED.

<a id="readycounter"></a>
### ReadyCounter

Audit what shopping agents can read and expose browser-native WebMCP shopping tools.

- **Use when:** Inspect a storefront’s agent-facing catalog or work with its18 declared WebMCP tools; the human retains checkout control.
- **Entry:** `node scripts/verify-tool-schemas.mjs`. Source: [scripts/verify-tool-schemas.mjs](https://github.com/Morkeeth/readycounter/blob/b977f165d085da4430d06c2c98472be3a38b546a/scripts/verify-tool-schemas.mjs).
- **Repository:** [Morkeeth/readycounter](https://github.com/Morkeeth/readycounter).
- **Status:** unverified.
- **Proof checked29 Oct:** All18 tool-schema checks passed. Current hosted availability, store audits and native WebMCP execution remain UNVERIFIED.

<a id="pigeon"></a>
### pigeon

Find, check and rotate API-key copies through a macOS CLI.

- **Use when:** Inspect the key-management workflow before explicitly authorized credential work; help is safe to start with.
- **Entry:** `zsh coo --help`. Source: [coo](https://github.com/Morkeeth/pigeon/blob/22e6f06a8cc31ca60629cb6ab4e0d71387b25cc7/coo).
- **Repository:** [Morkeeth/pigeon](https://github.com/Morkeeth/pigeon).
- **Status:** unverified.
- **Proof checked29 Oct:** Help passed in an empty temporary home. Keychain access, credential discovery, provider probes and rotation remain UNVERIFIED and were not run.

<a id="agents-for-humans"></a>
### MAGNET

Record agent-stack adoption and rerun explicit evaluation probes.

- **Use when:** Measure a specific stack change against a chosen check; do not substitute adoption counts for usefulness.
- **Entry:** `python3 -m magnet.cli --help`. Source: [magnet/cli.py](https://github.com/Morkeeth/agents-for-humans/blob/ea15a3b590135bbdec045f03320519b012454bac/magnet/cli.py).
- **Repository:** [Morkeeth/agents-for-humans](https://github.com/Morkeeth/agents-for-humans).
- **Status:** unverified.
- **Proof checked29 Oct:** The correct module help passed. python3 -m magnet is not a valid entry point. Eval execution and Strands integration remain UNVERIFIED. Additional reproducible test source: [tests/test_absolute_level.py](https://github.com/Morkeeth/agents-for-humans/blob/ea15a3b590135bbdec045f03320519b012454bac/tests/test_absolute_level.py).

<a id="agent-work-record-witness-ata"></a>
### Agent Work Record Witness

Compare an agent’s done-report with evidence on the repository object.

- **Use when:** Audit a recorded completion claim without executing commands copied from that report.
- **Entry:** `python3 -m gate.outcome_gate --help`. Source: [gate/outcome_gate.py](https://github.com/Morkeeth/agent-work-record-witness-ata/blob/4a45551297c6d878257a516c90baf2f2fb103eb2/gate/outcome_gate.py).
- **Repository:** [Morkeeth/agent-work-record-witness-ata](https://github.com/Morkeeth/agent-work-record-witness-ata).
- **Status:** unverified.
- **Proof checked29 Oct:** Help and tests/test_record.py passed. This is local record behavior, not a fresh hosted fleet validation. Additional reproducible test source: [contract/test_adjacency.py](https://github.com/Morkeeth/agent-work-record-witness-ata/blob/4a45551297c6d878257a516c90baf2f2fb103eb2/contract/test_adjacency.py).

<a id="fleet"></a>
### fleet

Inspect coding-agent lanes and their recorded outcomes from one config.

- **Use when:** Check a fleet configuration and the repositories it names; distinguish recorded status from independently verified completion.
- **Entry:** `python3 fleet --help`. Source: [fleet](https://github.com/Morkeeth/fleet/blob/219cec4680e57caeeb1687545776f90658e064b9/fleet).
- **Repository:** [Morkeeth/fleet](https://github.com/Morkeeth/fleet).
- **Status:** unverified.
- **Proof checked29 Oct:** Help passed. A configured fleet scan and ongoing service operation remain UNVERIFIED.

<a id="nullspace"></a>
### Nullspace

Record missing dataset demand as DataHub metadata.

- **Use when:** Keep a failed data lookup visible to a builder; follow the README’s local DataHub setup before making graph writes.
- **Entry:** `NULLSPACE_STORE=memory python3 -m nullspace.cli dump`. Source: [nullspace/cli.py](https://github.com/Morkeeth/nullspace/blob/b23402d1b2d389cc80bfd59772a2b67db8fd7235/nullspace/cli.py).
- **Repository:** [Morkeeth/nullspace](https://github.com/Morkeeth/nullspace).
- **Status:** unverified.
- **Proof checked29 Oct:** Entry point exists. Help failed here because the datahub dependency is absent; DataHub and builder execution remain UNVERIFIED. Additional reproducible test source: [app/tests/test_discover.py](https://github.com/Morkeeth/nullspace/blob/b23402d1b2d389cc80bfd59772a2b67db8fd7235/app/tests/test_discover.py).

<a id="nullspace-dbt"></a>
### Nullspace dbt companion

Hold the warehouse model project targeted by Nullspace’s builder.

- **Use when:** Inspect a proposed warehouse model alongside the parent Nullspace workflow; use synthetic local warehouse data.
- **Entry:** `dbt_project.yml`. Source: [dbt_project.yml](https://github.com/Morkeeth/nullspace-dbt/blob/a08394c1187e7363d733d94232a11843c4b062d0/dbt_project.yml).
- **Repository:** [Morkeeth/nullspace-dbt](https://github.com/Morkeeth/nullspace-dbt).
- **Status:** unverified.
- **Proof checked29 Oct:** dbt_project.yml and the model source folder exist. No dbt build, warehouse access or model-result validation was run.

<a id="Litmus-Anthropic-gtm"></a>
### Litmus

Expose source-backed lead ranking through a dashboard, CLI and MCP.

- **Use when:** Inspect a lead brief with its source evidence rather than acting on an unexplained ranking.
- **Entry:** `npm run cli -- help`. Source: [bin/litmus.ts](https://github.com/Morkeeth/Litmus-Anthropic-gtm/blob/e7d9402076d489f9cb9ca0cba29272cda9d32c9a/bin/litmus.ts).
- **Repository:** [Morkeeth/Litmus-Anthropic-gtm](https://github.com/Morkeeth/Litmus-Anthropic-gtm).
- **Status:** unverified.
- **Proof checked29 Oct:** The CLI script exists in package.json; execution failed because tsx is not installed. MCP, live data and ranking quality remain UNVERIFIED.

<a id="BriefMCP"></a>
### BriefMCP

Provide project knowledge context through a frontend and companion MCP ecosystem.

- **Use when:** Inspect shared project context; this repository is the frontend, not the separate published MCP package.
- **Entry:** `npm run dev`. Source: [package.json](https://github.com/Morkeeth/BriefMCP/blob/1d864c8ca2b0a2b9d551747816d6cf276aa7d4e4/package.json).
- **Repository:** [Morkeeth/BriefMCP](https://github.com/Morkeeth/BriefMCP).
- **Status:** unverified.
- **Proof checked29 Oct:** Frontend dev script exists. Its mcp-server directory has manifests but no server implementation; do not invent a node index.js entry. Startup and the external companion MCP remain UNVERIFIED.

<a id="chatinsight"></a>
### ChatInsights MCP

Expose permission-controlled macOS services through a native MCP application.

- **Use when:** Review the public MCP interfaces and requested permissions before granting access to any personal source.
- **Entry:** `open Package.swift`. Source: [Package.swift](https://github.com/Morkeeth/chatinsight/blob/90c798275358e911b5a9a46d254af1df66027d83/Package.swift).
- **Repository:** [Morkeeth/chatinsight](https://github.com/Morkeeth/chatinsight).
- **Status:** unverified.
- **Proof checked29 Oct:** Package.swift and Sources/MCPCore/MCPServer.swift exist. No build, permission grant, personal-data read or live MCP call was run.

<a id="brand-palette-studio"></a>
### Brand Palette Studio

Create and export aesthetic palette cards in a browser.

- **Use when:** Prepare a visual palette reference or inspect the export UI before using it in a design task.
- **Entry:** `npm run dev`. Source: [package.json](https://github.com/Morkeeth/brand-palette-studio/blob/b40644080197300e0cd433541bd0865e79abfd27/package.json).
- **Repository:** [Morkeeth/brand-palette-studio](https://github.com/Morkeeth/brand-palette-studio).
- **Status:** unverified.
- **Proof checked29 Oct:** The dev script and application sources exist. Dependencies, browser export and current hosted availability remain UNVERIFIED.

<a id="fika-art"></a>
### Fika art

Provide reusable public line graphics for a morning email.

- **Use when:** Select an existing mark or section glyph for a Fika-compatible layout; this is an asset library, not an executable generator.
- **Entry:** `marks/mark-sun.png`. Source: [marks/mark-sun.png](https://github.com/Morkeeth/fika-art/blob/2f1d46a77326208ea567654eb467368eec44bdee/marks/mark-sun.png).
- **Repository:** [Morkeeth/fika-art](https://github.com/Morkeeth/fika-art).
- **Status:** live.
- **Proof checked29 Oct:** The referenced PNG and glyphs folder exist. No generator or rendering test is claimed.

<a id="weirder-md"></a>
### Weirder

Explore six interactions with plain Markdown in one standalone HTML page.

- **Use when:** Study an archived interaction prototype; do not assume this is a maintained app.
- **Entry:** `index.html`. Source: [index.html](https://github.com/Morkeeth/weirder-md/blob/32985ad3fa1225b8971881b6ae1c28a406f063f2/index.html).
- **Repository:** [Morkeeth/weirder-md](https://github.com/Morkeeth/weirder-md).
- **Status:** frozen.
- **Proof checked29 Oct:** index.html exists. Repository is archived; browser behavior is UNVERIFIED in this pass.

<a id="agentgrinder"></a>
### Agent Grinder, historical

Render coding-agent run cards from supported transcripts.

- **Use when:** Reproduce the historical Agent Grinder entry; choose STRIVE for the current social product.
- **Entry:** `python3 -m agentgrinder --help`. Source: [agentgrinder/__main__.py](https://github.com/Morkeeth/agentgrinder/blob/9ba9d0942375c7bfe9d36e466e35436eea4a844b/agentgrinder/__main__.py).
- **Repository:** [Morkeeth/agentgrinder](https://github.com/Morkeeth/agentgrinder).
- **Status:** frozen.
- **Proof checked29 Oct:** CLI help passed. Legacy hosted state and coaching remain UNVERIFIED. Additional reproducible test source: [tests/test_agent_api.py](https://github.com/Morkeeth/agentgrinder/blob/9ba9d0942375c7bfe9d36e466e35436eea4a844b/tests/test_agent_api.py).

<a id="simulated-market"></a>
### simulated-market, historical source snapshot

Preserve an earlier app-check workspace and supporting simulation modules.

- **Use when:** Reproduce an older snapshot; choose Agentic Swarm Simulator for the current release.
- **Entry:** `python3 -m sim.workspace --help`. Source: [sim/workspace.py](https://github.com/Morkeeth/simulated-market/blob/9d13d7eba9329a756ba6f59b9afa9013400550f9/sim/workspace.py).
- **Repository:** [Morkeeth/simulated-market](https://github.com/Morkeeth/simulated-market).
- **Status:** frozen.
- **Proof checked29 Oct:** The help invocation exited0 with no output. Workspace service and model execution remain UNVERIFIED; this is not proof of a running server. Additional reproducible test source: [tests/test_app_check.py](https://github.com/Morkeeth/simulated-market/blob/9d13d7eba9329a756ba6f59b9afa9013400550f9/tests/test_app_check.py).

<a id="arena"></a>
### ARENA

Run sealed two-agent bouts and retain a score sheet.

- **Use when:** Inspect historical bout fixtures only; this project is killed and must not be reactivated from this catalog.
- **Entry:** `python3 scripts/judge examples/BOUT-001/bout.json`. Source: [scripts/judge](https://github.com/MorkeethHQ/arena/blob/538b92585ab9c6bd006a6f00137200910d3aa95a/scripts/judge).
- **Repository:** [MorkeethHQ/arena](https://github.com/MorkeethHQ/arena).
- **Status:** killed.
- **Proof checked29 Oct:** BOUT-001 fixture completed locally. This verifies the retained fixture, not a new live duel or a reopened project. Additional reproducible test source: [tests/test_fixture_smoke.py](https://github.com/MorkeethHQ/arena/blob/538b92585ab9c6bd006a6f00137200910d3aa95a/tests/test_fixture_smoke.py).

## Coverage and limits

The source pass checked the project registry, local command wrappers, installed skill descriptions, public repository roots and the existing Hub. The registry and Hub are discovery inputs, not proof a command works. Public source revisions above bind each entry to the files inspected.

Private-only tools and internal orchestration are deliberately absent. Third-party binaries installed alongside Oscar’s tools are not attributed to him. Personal sites, journal applications, financial or wallet tools, career material and standalone experiment write-ups are outside this public tool catalog. Shared/team projects remain attributed through their own repositories.

No model generation, provider trial, database migration or public action was performed as a tool-verification check. Synthetic examples are not user results. No command listed as unverified should be treated as having passed an end-to-end check.

Repository guides link to the entry in this file. Existing AGENTS.md files are preserved. Archived repositories remain read-only; a local guide proposal does not mean a PR can be opened against an archived repository.

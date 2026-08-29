# Wazoo

World models as a service for AI agents.

## Platform

<table>
<tr>
<td>

<b>[wazoo-api](https://github.com/wazootech/wazoo-api)</b><br>
Control plane: users, Worlds, platform tokens, usage, billing

</td>
<td>

<b>[worlds-api](https://github.com/wazootech/worlds-api)</b><br>
Data plane: search, SPARQL, import, export

</td>
</tr>
<tr>
<td>

<b>[wazoo-console](https://github.com/wazootech/wazoo-console)</b><br>
Management-plane UI (private beta)

</td>
<td>

<b>[wazoo-desktop](https://github.com/wazootech/wazoo-desktop)</b><br>
Native desktop app (early stage)

</td>
</tr>
</table>

## SDKs

<table>
<tr>
<td>

<b>[wazoo-client-ts](https://github.com/wazootech/wazoo-client-ts)</b><br>
[`@wazoo/client`](https://jsr.io/@wazoo/client) — Management-plane TypeScript SDK

</td>
<td>

<b>[worlds-client-ts](https://github.com/wazootech/worlds-client-ts)</b><br>
[`@worlds/client`](https://jsr.io/@worlds/client) — Generated data-plane HTTP client

</td>
</tr>
<tr>
<td>

<b>[worlds-sdk-ts](https://github.com/wazootech/worlds-sdk-ts)</b><br>
[`@worlds/sdk`](https://jsr.io/@worlds/sdk) — Embeddable Worlds SDK (in-process graph ops)

</td>
<td>

<b>[sparql-engine](https://github.com/wazootech/sparql-engine)</b><br>
[`@wazoo/sparql-engine`](https://jsr.io/@wazoo/sparql-engine) — Zero-dependency SPARQL 1.1/1.2 engine

</td>
</tr>
<tr>
<td>

<b>[worlds-kit](https://github.com/wazootech/worlds-kit)</b><br>
[`@wazoo/worlds-kit`](https://www.npmjs.com/package/@wazoo/worlds-kit) — RDF-native React composition framework

</td>
<td>

<b>[wazoo-tools](https://github.com/wazootech/wazoo-tools)</b><br>
[`@wazoo/tools`](https://jsr.io/@wazoo/tools) — Vercel AI SDK tools for Worlds knowledge graphs

</td>
</tr>
</table>

## Storage Adapters

<table>
<tr>
<td>

<b>[worlds-libsql](https://github.com/wazootech/worlds-libsql)</b><br>
[`@worlds/libsql`](https://jsr.io/@worlds/libsql) — libSQL/Turso adapter

</td>
<td>

<b>[worlds-postgres](https://github.com/wazootech/worlds-postgres)</b><br>
[`@worlds/postgres`](https://jsr.io/@worlds/postgres) — PostgreSQL adapter

</td>
</tr>
<tr>
<td>

<b>[worlds-sqlite](https://github.com/wazootech/worlds-sqlite)</b><br>
[`@worlds/sqlite`](https://jsr.io/@worlds/sqlite) — Local SQLite adapter

</td>
<td>

<b>[worlds-cloudflare](https://github.com/wazootech/worlds-cloudflare)</b><br>
[`@worlds/cloudflare`](https://jsr.io/@worlds/cloudflare) — Cloudflare D1 adapter

</td>
</tr>
<tr>
<td>

<b>[worlds-indexeddb](https://github.com/wazootech/worlds-indexeddb)</b><br>
[`@worlds/indexeddb`](https://jsr.io/@worlds/indexeddb) — Browser IndexedDB adapter

</td>
<td>

</td>
</tr>
</table>

## Memory

<table>
<tr>
<td>

<b>[memsdk](https://github.com/wazootech/memsdk)</b><br>
Portable AI memory SDK (Supermemory-compatible interface)

</td>
<td>

<b>[memsdk-letta](https://github.com/wazootech/memsdk-letta)</b><br>
Letta-backed adapter for memsdk

</td>
</tr>
<tr>
<td>

<b>[memsdk-worlds](https://github.com/wazootech/memsdk-worlds)</b><br>
Worlds-backed adapter for memsdk (WIP)

</td>
<td>

<b>[wazoo-memorybench](https://github.com/wazootech/wazoo-memorybench)</b><br>
Pluggable benchmarking framework for memory and context systems

</td>
</tr>
</table>

## Tools & CLI

<table>
<tr>
<td>

<b>[wazoo-cli](https://github.com/wazootech/wazoo-cli)</b><br>
Command-line client for the Wazoo platform

</td>
<td>

<b>[workspace-cli](https://github.com/wazootech/workspace-cli)</b><br>
[`@wazoo/workspace`](https://jsr.io/@wazoo/workspace) — Git-native multi-repo workspace CLI

</td>
</tr>
<tr>
<td>

<b>[wiki](https://github.com/wazootech/wiki)</b><br>
Verifiable, agent-friendly CLI with SHACL validation and SPARQL querying

</td>
<td>

<b>[wiki-templates](https://github.com/wazootech/wiki-templates)</b><br>
Starter templates for Wiki CLI (Quartz, Astro, Next.js, Mintlify, and more)

</td>
</tr>
<tr>
<td>

<b>[linked-markdown](https://github.com/wazootech/linked-markdown)</b><br>
Protocol and spec for linked data through Markdown documents

</td>
<td>

<b>[linked-markdown-ts](https://github.com/wazootech/linked-markdown-ts)</b><br>
[`@wazoo/linked-markdown`](https://jsr.io/@wazoo/linked-markdown) — TypeScript implementation

</td>
</tr>
<tr>
<td>

<b>[linked-markdown-py](https://github.com/wazootech/linked-markdown-py)</b><br>
[`linked-markdown`](https://pypi.org/project/linked-markdown/) — Python implementation

</td>
<td>

<b>[commentsh](https://github.com/EthanThatOneKid/commentsh)</b><br>
Comment Shell — run shell commands from inside code comments

</td>
</tr>
</table>

## Agent Integration

<table>
<tr>
<td>

<b>[wazoo-skills](https://github.com/wazootech/wazoo-skills)</b><br>
Agent skills for coding agents (Claude Code, Cursor, OpenCode, Gemini)

</td>
<td>

<b>[wazoo-factory](https://github.com/wazootech/wazoo-factory)</b><br>
AI-powered software delivery: planning, implementation, verification, and PR handoff

</td>
</tr>
</table>

## Internal

<table>
<tr>
<td>

<b>[memory](https://github.com/wazootech/memory)</b><br>
Semantic company brain — version-controlled wiki for strategy and operations

</td>
<td>

<b>[worlds-vps](https://github.com/wazootech/worlds-vps)</b><br>
Terraform and Docker Compose for VPS deployment

</td>
</tr>
<tr>
<td>

<b>[wazoo-e2e](https://github.com/wazootech/wazoo-e2e)</b><br>
Reusable E2E integration and smoke test flows for the platform

</td>
<td>

<b>[memsdk-e2e](https://github.com/wazootech/memsdk-e2e)</b><br>
E2E compatibility tests for the memsdk ecosystem

</td>
</tr>
</table>

## Websites & Docs

[Console](https://console.wazoo.dev) · [Documentation](https://docs.wazoo.dev) · [Wazoo.dev](https://wazoo.dev)

All projects: [docs.wazoo.dev/projects](https://docs.wazoo.dev/projects)

## Community

[Discord](https://discord.gg/wpaavgRMAE) · [X/Twitter](https://x.com/wazootech) · [LinkedIn](https://www.linkedin.com/company/wazootech/) · [Instagram](https://www.instagram.com/wazootech/)

[Request access](https://forms.gle/Se2rd3Znsr4S7Xz56) to the private beta

# Vault

A personal life wiki maintained by Claude. The vault is a compounding knowledge graph — every conversation, document, and idea you feed it makes the whole thing smarter over time. Built for Obsidian.

## What it is

The vault is a long-running record of your life: thoughts, work, relationships, health, finances, creative output, and anything else that matters. Unlike a note-taking app, it grows in value through cross-referencing and synthesis — not just storage.

Claude maintains it. You direct it.

## How it's organized

```
vault/
├── raw/        ← drop anything here
├── files/      ← permanent documents (PDFs, photos, records)
├── llm-wiki/   ← Claude's synthesized knowledge graph
└── sot-wiki/   ← validated ground truth, approved by you
```

**raw/** is your inbox. Drop files here without thinking about where they go — Claude routes them.

**files/** stores originals that have value as artifacts: contracts, medical records, photos, personal letters.

**llm-wiki/** is where Claude writes freely. Dense, interlinked pages that synthesize everything you've fed the vault. Claude owns this layer entirely.

**sot-wiki/** is ground truth. Claude can only *propose* additions here — you approve, reject, or edit each one. If llm-wiki ever contradicts sot-wiki, sot-wiki wins.

## How to use it

**Drop content.** Put anything in `raw/` and tell Claude to ingest it — articles, PDFs, voice transcripts, screenshots, notes. Claude decides where it goes and what it means.

**Ask questions.** Ask Claude anything about your life, your documents, or past conversations. It traces through the knowledge graph to find the answer.

**Review proposals.** Claude periodically proposes facts for sot-wiki — things it believes are definitively true about you. Open `sot-wiki/proposals.md` and approve or reject them.

**Let it run.** Claude journals automatically every 5 messages and runs a health check every 20. You don't need to manage this.

## Core idea

The wiki is the artifact, not the chat. Conversations are ephemeral. The vault persists and compounds. Every session should leave it richer than before.

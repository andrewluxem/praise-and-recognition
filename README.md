# praise-and-recognition

Drafts evidence-bound private or public recognition notes without inventing impact or consent.

It produces:

- **Specific Praise and Recognition Notes:** a working artifact built from supplied facts, labeled inference, and visible missing fields.

It executes the [Praise & Recognition playbook](https://www.andrewluxem.com/playbooks/praise-and-recognition). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/praise-and-recognition.git
cp -r praise-and-recognition/skills/praise-and-recognition ~/.claude/skills/
```

For Codex, copy the same complete folder to the Codex skills directory:

```bash
cp -r praise-and-recognition/skills/praise-and-recognition ~/.codex/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/praise-and-recognition
/plugin install praise-and-recognition@praise-and-recognition
```

For clients that install from an archive, use the versioned [praise-and-recognition v1.0.0 ZIP](https://www.andrewluxem.com/downloads/praise-and-recognition-v1.0.0.zip).

## Invoke it

```text
Write specific praise and recognition notes from this evidence
Use the praise-and-recognition skill.
```

Naming the skill is always valid: `use the praise-and-recognition skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/praise-and-recognition/
  assets/praise-and-recognition-notes-template.md
  LICENSE.md
  meta.yaml
  references/recognition-note-standard.md
  SKILL.md
README.md
LICENSE
```

The complete canonical package is copied under `skills/praise-and-recognition/`, including every asset, reference, test prompt, source note, changelog entry, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, `.claude-plugin/plugin.json`, and `.claude-plugin/marketplace.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/praise-and-recognition/LICENSE.md](skills/praise-and-recognition/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.

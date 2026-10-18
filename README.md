# to-spec-ja

会話の内容から日本語の仕様（spec）を書いて GitHub Issue に起票する Agent Skill（Claude Code / Codex）。

[mattpocock/skills](https://github.com/mattpocock/skills) の `to-spec` をもとに、日本語の Issue 規約（問題 / 症状 / 原因 / 修正方針・事実と推測の区別・判定できる完了条件）と組み合わせたもの。repo に `AGENTS.md` / `CLAUDE.md` の Issue 規約や `.github/ISSUE_TEMPLATE/` があれば、そちらに従う。

## インストール

```bash
git clone https://github.com/engchina/to-spec-ja ~/.claude/skills/to-spec-ja
```

更新は `git -C ~/.claude/skills/to-spec-ja pull`。

## 使い方

仕様にしたい内容を会話で詰めたあと（`/grill-me` など）、`/to-spec-ja` を実行する。テストの継ぎ目とラベルを 1 回確かめてから起票する。

## License

MIT（元の `to-spec` の著作権表示を含む。`LICENSE` を参照）。

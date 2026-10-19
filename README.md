# OneMemory

OneMemory is a macOS menu bar app that remembers the text you've seen on screen and suggests
how to finish what you're typing.

- **Search everything you've seen.** Press ⌃⌥M and search the text of the windows you've used:
  messages, pages, documents. Each result says where and when you saw it, and opens it again.
- **Autocomplete everywhere.** Grey suggestions appear after the caret in most apps (Mail, Notes,
  Slack, browsers). Press Tab to accept. Suggestions can draw on what you've seen before, such as
  an address or a colleague's name.
- **On your Mac.** Capture, search and the built-in suggestion model run on this Mac. Secrets such
  as tokens and keys are removed before anything is saved, and password fields are never read.
  You can also use Ollama, LM Studio, the Anthropic or OpenAI API, or the Claude CLI for suggestions.

## Install

Download the latest `OneMemory-<version>.dmg` from
[Releases](https://github.com/jhasubhash/onememory-releases/releases), open it, and drag OneMemory
to Applications. It's signed with a Developer ID and notarized by Apple.

On first launch, grant **Accessibility** (required) in System Settings → Privacy & Security.
**Screen Recording** is optional; it lets OneMemory read apps that don't share their text.
To use the built-in suggestion model, download one in Settings → Autocomplete.

Requires macOS 26 or later on Apple silicon.

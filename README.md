# DiT Mods — Issue Tracker

This is the place to report bugs, suggest features, and ask questions about DiT's Minecraft mods published on [Modrinth](https://modrinth.com).

This repository holds **tickets only**. There's no source code here. To download the mods, go to their Modrinth pages below.

## Mods

| Mod | Description | Loader | Minecraft | Side |
| --- | --- | --- | --- | --- |
| [LavaConduit](https://modrinth.com/mod/lavaconduit) | *Under review on Modrinth — coming soon.* | Fabric | — | — |
| [MuddyWaters](https://modrinth.com/mod/muddywaters) | Over time, turns dirt next to or under water into mud or biome-specific "shoreline" blocks, without changing world generation settings. | Fabric | 26.2, 26.3 | Server |

## Reporting an issue

**[Open a new issue →](https://github.com/DiT-MG-Dev/trackers/issues/new/choose)**

Choose the template that fits:

- **Bug report**: something is broken, behaves unexpectedly, or crashes the game.
- **Feature request**: an idea for something new or a change to existing behaviour.
- **Question / feedback**: how-to questions, configuration or compatibility help, and general feedback.

Tips for a useful report:

- **Search first.** If someone has already reported it, add a 👍 reaction or extra details to that issue instead of opening a new one.
- **One issue per problem.** Separate issues are easier to track and close.
- **Include versions.** Give the mod version, Minecraft version, and Fabric Loader version.
- **Attach logs.** For crashes, include the crash report or `logs/latest.log`. Upload large logs to [mclo.gs](https://mclo.gs) and paste the link.

## Community standards

Everyone who takes part here is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md). In short:

- **Be respectful.** Be patient and constructive. The mods are maintained in spare time.
- **Stay on topic.** Issues should be about the mods listed above.
- **No harassment, hate speech, spam, or self-promotion.**
- **No piracy.** Don't post links to cracked or re-hosted copies of mods or of Minecraft.
- **Don't bump.** Instead of commenting "+1" or "any update?", use a 👍 reaction.
- **Write in English** where possible so everyone can follow along.

The maintainer may edit, close, or lock issues that break these standards. To flag serious abuse, use GitHub's **Report content** option on the comment or issue.

<details>
<summary><strong>Maintainer: adding a new mod</strong></summary>

1. Add the mod's name to the `mod` dropdown in **all three** forms in [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/). Keep the list alphabetical.
2. Add a Modrinth contact link to [`.github/ISSUE_TEMPLATE/config.yml`](.github/ISSUE_TEMPLATE/config.yml).
3. Add a row to the **Mods** table above.
4. Create the label: `gh label create "mod: <slug>" --color 5319E7 --description "<Name>"`.
5. On Modrinth, set the project's **Issues** link to `https://github.com/DiT-MG-Dev/trackers/issues`.

</details>

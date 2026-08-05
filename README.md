# Codex Fan Pets

Fan-made custom pets for Codex.

## Pets

| Klee / 可莉 | yoimiya宵宫 | Sandrone / 桑多涅（木偶） |
|---|---|---|
| <img src="assets/klee-preview.gif" alt="Klee Codex pet preview" width="256"> | <img src="assets/yoimiya-preview.gif" alt="yoimiya宵宫 Codex pet preview" width="256"> | <img src="assets/sandrone-preview.gif" alt="Sandrone 桑多涅（木偶） Codex pet preview" width="256"> |
| `klee` | `yoimiya宵宫` | `sandrone桑多涅-marionette木偶` |

| Rich Paimon财神派蒙 | Hilichurl / 丘丘人 | furina芙宁娜 |
|---|---|---|
| <img src="assets/paimon-preview.gif" alt="Rich Paimon财神派蒙 Codex pet preview" width="256"> | <img src="assets/hilichurl-preview.gif" alt="Hilichurl 丘丘人 Codex pet preview" width="256"> | <img src="assets/furina-preview.gif" alt="furina芙宁娜 Codex pet preview" width="256"> |
| `Rich Paimon财神派蒙` | `Hilichurl丘丘人` | `furina芙宁娜` |

These are fan-made Codex pets inspired by characters and creatures from Genshin Impact.

This project is unofficial and is not affiliated with OpenAI, Codex, HoYoverse, or Genshin Impact.

## Install

From this repository root:

```powershell
$pet = "furina芙宁娜" # or "sandrone-marionette" / "Hilichurl丘丘人" / "Rich Paimon财神派蒙" / "yoimiya宵宫" / "klee"
$dest = "$env:USERPROFILE\.codex\pets\$pet"
New-Item -ItemType Directory -Force -Path $dest | Out-Null
Copy-Item ".\pets\$pet\pet.json", ".\pets\$pet\spritesheet.png" -Destination $dest -Force
```

Then open Codex and refresh custom pets from the appearance settings.

## Usage

Personal use only. Do not sell, redistribute, or claim these assets as official.

Genshin Impact, Klee, Yoimiya, Paimon, Furina, Sandrone, and Hilichurls belong to HoYoverse.

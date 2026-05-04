# Codex Fan Pets

Fan-made custom pets for Codex.

## Pets

### Klee

Klee is a fan-made Codex pet inspired by Klee from Genshin Impact.

<img src="assets/klee-preview.gif" alt="Klee Codex pet preview" width="384">

This project is unofficial and is not affiliated with OpenAI, Codex, HoYoverse, or Genshin Impact.

## Install

From this repository root:

```powershell
$pet = "klee"
$dest = "$env:USERPROFILE\.codex\pets\$pet"
New-Item -ItemType Directory -Force -Path $dest | Out-Null
Copy-Item ".\pets\$pet\pet.json", ".\pets\$pet\spritesheet.webp" -Destination $dest -Force
```

Then open Codex and refresh custom pets from the appearance settings.

## Usage

Personal use only. Do not sell, redistribute, or claim these assets as official.

Genshin Impact and Klee belong to HoYoverse.

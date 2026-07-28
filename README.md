# paperclip-skills

Paperclip ve Claude Code için üç mühendislik skill'i. Her dizin bir skill:
kökünde `SKILL.md`, gerekiyorsa yanında referans dosyaları.

| Skill | Ne işe yarar |
|---|---|
| [`karpathy-guidelines`](karpathy-guidelines) | Yapay zekânın sık yaptığı kodlama hatalarını önler: aşırı karmaşıklaştırma, gereksiz geniş değişiklik, dağınık düzenleme. |
| [`react-native-skills`](react-native-skills) | React Native ve Expo performans kuralları — 13 kategoride 35+ kural, doğru/yanlış örnekleriyle. |
| [`vanity-engineering-review`](vanity-engineering-review) | "Gösteriş mühendisliği" denetimi: gerçek ihtiyaç yerine ilgi çektiği için kurulmuş yapıları bulur. |

## Kurulum

Paperclip: **Skills → New → Import from path or URL**, sonra bu deponun bir
alt dizin URL'i:

```
https://github.com/tuncasoftbildik/paperclip-skills/tree/main/karpathy-guidelines
```

Claude Code: dizini `~/.claude/skills/` altına kopyalayın.

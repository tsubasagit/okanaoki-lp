# OKA — 個人ページ LP

作曲家・OKA（株式会社ヌメロ.8 代表）の個人ページ。プロフィールと、音楽を体験できる **FLUX RING** をなぜつくったのか、を伝える 1 枚物の LP。

- 公開: https://tsubasagit.github.io/oka-lp/
- 単一 HTML 完結（依存ゼロ）。`index.html` のみ。

## トンマナ（FLUX RING 確定仕様準拠）
- 配色トークン: page `#0E0C20` / violet `#7C62D6` / blue `#4684E0` / シアン `#60CEE0`（要所一点）。暖色不使用。
- 三憲法: AI を名乗らない／効能を謳わない／値引き・煽りをしない。
- 星はホタル状の明滅（周期 3 秒）、`prefers-reduced-motion` 対応。

## 公開前に差し替える項目
1. ポートレート: 既定の藍紫グラデ玉 → 実写真（`.portrait` を `<img>` 化）
2. CTA リンク: `href="#"` → App Store / Google Play
3. OGP: `og:image`・本番ドメイン

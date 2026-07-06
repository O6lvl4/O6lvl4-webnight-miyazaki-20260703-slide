# WASM x Almide — Webナイト宮崎 2026-07-03

登壇スライド「467バイトの Hello World から、ブラウザで動く 1-bit LLM まで — 自作言語で見てきた WebAssembly の現在地」

**Slides: https://o6lvl4.github.io/O6lvl4-webnight-miyazaki-20260703-slide/**

- 依存ゼロの自己完結 HTML 1 枚（`index.html`）。`open index.html` でも動く
- 操作: `→` / `←` / Space / クリック（右半分で進む）/ スワイプ。`#12` のようにページ直リンク可
- 26 枚。10 分コア想定、デモを広げて 20〜30 分に伸縮可能

## デモ一覧

| デモ | Repository | GitHub Pages |
|---|---|---|
| 音のシンセ（AudioWorklet・2,637 B） | [O6lvl4/almide-audio-poc](https://github.com/O6lvl4/almide-audio-poc) | [Live](https://o6lvl4.github.io/almide-audio-poc/) |
| obsid — 3D レンダラ（Heightmap / 球 / トーラス） | [almide-graphics/obsid](https://github.com/almide-graphics/obsid) | [Live](https://almide-graphics.github.io/obsid/) |
| ceangal — WebGPU UI フレームワーク | [almide-graphics/ceangal](https://github.com/almide-graphics/ceangal) | [Todo](https://almide-graphics.github.io/ceangal/) · [Stress](https://almide-graphics.github.io/ceangal/stress.html) |
| playground — ブラウザ内コンパイラ | [almide/playground](https://github.com/almide/playground) | [Live](https://almide.github.io/playground/) |
| nn chat — Qwen3 をブラウザで（WebGPU） | [almide-graphics/nn](https://github.com/almide-graphics/nn) | [Live](https://almide-graphics.github.io/nn/web/) |
| Bonsai — 1-bit LLM を純 WASM で | [almide/bonsai-almide](https://github.com/almide/bonsai-almide) | [Live](https://almide.github.io/bonsai-almide/) |
| porta — AI エージェント用サンドボックス（CLI） | [almide/porta](https://github.com/almide/porta) | —（Web デモなし） |
| MSR 日次ダッシュボード | [almide/almide-dojo](https://github.com/almide/almide-dojo) | [Live](https://almide.github.io/almide-dojo/) |

言語本体: [almide/almide](https://github.com/almide/almide) · [Playground で試す](https://almide.github.io/playground/)

## 出典

スライド中の数字はすべて実測・出典つき（almide 0.28.0 時点）。収集元と検証メモは手元の MATERIALS.md（非公開・ローカルのみ）に整理済み。

# Awesome Audio Softwares（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

音声処理・音楽制作・可視化・解析に役立つソフトウェアのキュレーションリストです。DAW、エディタ、プラグインホスト、オープンソースツール、ビジュアライゼーション、解析ツールをカバーします。

## 目次

- [DAW](#daw)
- [オーディオエディタ](#オーディオエディタ)
- [プラグインホストとフォーマット](#プラグインホストとフォーマット)
- [エフェクト・処理](#エフェクト処理)
- [シンセ・モジュラー](#シンセモジュラー)
- [音楽ビジュアライゼーション](#音楽ビジュアライゼーション)
- [オーディオ解析・メーター](#オーディオ解析メーター)
- [DJ・ライブ](#djライブ)
- [インフラ・I/O](#インフラio)
- [ライブラリ・フレームワーク](#ライブラリフレームワーク)
- [関連リスト](#関連リスト)
- [コントリビューション](#コントリビューション)

---

## DAW

マルチトラック録音、MIDI、ミキシング、アレンジ向けのデジタル・オーディオ・ワークステーション。

### オープンソース / 無料

- [Ardour](https://ardour.org/) - プロ向けオープンソース DAW。オーディオ/MIDI 録音・ミキシング・オートメーション、プラグインホスト（LV2、VST2/VST3、AU、LADSPA）。Linux / macOS / Windows。
- [LMMS](https://lmms.io/) - エレクトロニック向けオープンソース DAW。パターンシーケンス、ピアノロール、内蔵シンセ/エフェクト、VST/SoundFont。([GitHub](https://github.com/LMMS/lmms))
- [Qtractor](https://qtractor.sourceforge.io/) - Qt ベースの Linux DAW。MIDI/オーディオ、JACK 親和のルーティング。
- [Zrythm](https://www.zrythm.org/) - タイムライン編集・オートメーション・LV2/VST/CLAP 対応の現代的 GPL DAW。v2（C++/Qt で書き直し）は 2026 年時点でアルファテスト中。
- [Stargate](https://github.com/stargatedaw/stargate) - ルーティング行列と内蔵プラグインを備えた軽量クロスプラットフォーム DAW。低スペック向けも意識。
- [Waveform Free](https://www.tracktion.com/products/waveform-free) - Tracktion Waveform の無料版。プラグインホスト付きのフル DAW（登録が必要）。
- [Cakewalk Sonar](https://www.cakewalk.com/sonar) - フル機能の Windows DAW。提供終了した Cakewalk by BandLab（旧 SONAR 系）の後継。メンバーシップ不要の無料ティアあり、既存の `.cwp` プロジェクトも開ける。

### 商用（参考）

広く使われる商用 DAW。相互運用やワークフローの文脈用。

- [REAPER](https://www.reaper.fm/) - 軽量でスクリプト性の高い DAW（Cockos）。幅広いプラグイン形式（VST/VST3/AU/CLAP/LV2/JS）と寛容な評価ライセンス。([cockos.com/reaper](https://www.cockos.com/reaper/))
- [Ableton Live](https://www.ableton.com/live/) - セッション/アレンジ型。エレクトロニックとライブ向けに人気。
- [Logic Pro](https://www.apple.com/logic-pro/) - Apple の macOS/iPad DAW。内蔵音源とミキシングが充実。
- [FL Studio](https://www.image-line.com/fl-studio/) - パターン/プレイリスト中心の DAW（Image-Line）。ビートメイキングに強い。
- [Cubase](https://www.steinberg.net/cubase/) - Steinberg の定番制作 DAW。VST エコシステムの起点。
- [Bitwig Studio](https://www.bitwig.com/) - モジュラー/クリップランチャー型。The Grid と変調・ルーティングが特徴。

---

## オーディオエディタ

録音、クリーンアップ、ポッドキャスト、ファイル編集向け。

- [Audacity](https://www.audacityteam.org/) - 無料オープンソースのマルチトラック音声エディタ/レコーダ。ポッドキャストや簡易編集に定番。VST3/Nyquist。Audacity 4（2026年9月）で非破壊・重ね/グループ化可能なクリップ、UI 刷新、ワークスペースを導入。([GitHub](https://github.com/audacity/audacity)、[変更履歴](https://www.audacityteam.org/changelog/))
- [Tenacity](https://tenacityaudio.org/) - Audacity のコミュニティフォーク。libre 寄りの既定とプラグイン形式（VST、LV2、LADSPA、AU）。([GitHub](https://github.com/tenacityteam/tenacity))
- [Ocenaudio](https://www.ocenaudio.com/) - リアルタイムエフェクトプレビュー、VST、強力なスペクトログラムを備えた無料クロスプラットフォームエディタ。

---

## プラグインホストとフォーマット

スタンドアロンホストとプラグインが出荷される形式。

- [Carla](https://kx.studio/Applications:Carla) - モジュラー型プラグインホスト（KXStudio）。LADSPA、DSSI、LV2、VST2/VST3、AU、SF2/SFZ。JACK およびネイティブドライバ。([GitHub](https://github.com/falkTX/Carla))
- [LV2](https://lv2plug.in/) - Linux を中心に広く使われるオープンなプラグイン規格（LADSPA/DSSI 系の後継）。
- [CLAP](https://cleveraudio.org/) - 現代的なオープンプラグイン API（CLever Audio Plugin）。ホスト/プラグイン対応が拡大中。
- [JUCE](https://juce.com/) - 多くの商用・OSS オーディオアプリ/プラグインに使われるクロスプラットフォーム C++ フレームワーク。

---

## エフェクト・処理

FX スイート、リスニング向けツール、処理チェーン。

- [LSP Plugins](https://lsp-plug.in/) - EQ・ダイナミクス・メーター・空間系など大規模なオープンソースプロセッサ群（LV2/LADSPA/VST/CLAP およびスタンドアロン）。
- [EffeTune](https://github.com/Frieve-A/effetune) - Frieve-A による、音楽鑑賞体験を向上させるリアルタイムオーディオエフェクトプロセッサー。
- [Airwindows Consolidated](https://www.airwindows.com/consolidated/) - Chris Johnson による無料・MIT ライセンスの Airwindows エフェクト全種を 1 つにまとめたプラグイン（CLAP/VST3/AU/LV2、macOS/Windows/Linux）。
- [Neural Amp Modeler](https://www.neuralampmodeler.com/) - ニューラルネットでギターアンプ/ペダルをキャプチャ・再生する無料オープンソースプラグイン。コミュニティのモデルが豊富。([GitHub](https://github.com/sdatkinson/NeuralAmpModelerPlugin))
- [Ultimate Vocal Remover](https://github.com/anjok07/ultimatevocalremovergui) - Demucs や MDX-Net などのモデルを使う AI ステム分離（ボーカル/伴奏/ドラム等）のオープンソース GUI。
- ホスト内蔵 FX - 上記 DAW の多くは有用な EQ・ダイナミクス・ディレイ・リバーブを同梱。主要チェーンは耐久性のある公式ドキュメントを優先。

---

## シンセ・モジュラー

楽器、モジュラー環境、ドラムマシン。

- [VCV Rack](https://vcvrack.com/) - 仮想 Eurorack モジュラーシンセ。無料の Rack Free と商用モジュール。DAW プラグインあり。
- [Cardinal](https://cardinal.kx.studio/) - VCV Rack 系のオープンソースモジュラー（プラグイン/スタンドアロン）。([GitHub](https://github.com/DISTRHO/Cardinal))
- [plugdata](https://plugdata.org/) - Pure Data をプラグイン（VST3/AU/LV2/CLAP）およびスタンドアロンで使える、モダンなビジュアルパッチング GUI。([GitHub](https://github.com/plugdata-team/plugdata))
- [Bespoke Synth](https://bespokesynth.com/) - ノードベースのモジュラーシンセ/DAW ハイブリッド。複雑なルーティングと VST ホスト。([GitHub](https://github.com/BespokeSynth/BespokeSynth))
- [Surge XT](https://surge-synthesizer.github.io/) - オープンソースのハイブリッドシンセ（ウェーブテーブル/FM など）。VST3/AU/LV2/CLAP。([GitHub](https://github.com/surge-synthesizer/surge))
- [Vital](https://vital.audio/) - スペクトルワーピング型ウェーブテーブルシンセ（無料＋有料ティア）。
- [ZynAddSubFX](https://zynaddsubfx.sourceforge.io/) - 定番オープンソースソフトシンセ（加算/減算/パッド）。([GitHub](https://github.com/zynaddsubfx/zynaddsubfx))
- [Hydrogen](https://github.com/hydrogen-music/hydrogen) - オープンソースのドラムマシン/パターンシーケンサ（Linux 中心、他 OS ビルドあり）。

---

## 音楽ビジュアライゼーション

オーディオや MIDI に反応するリアルタイムビジュアル。

- [projectM](https://github.com/projectM-visualizer/projectm) - MilkDrop 互換のクロスプラットフォーム OSS 音楽ビジュアライゼーションライブラリ。OpenGL でリアルタイム描画。
- [MilkDrop](https://en.wikipedia.org/wiki/MilkDrop) - Ryan Geiss による Winamp 用の定番ハードウェア加速ビジュアライザ。ビート同期のユーザー「プリセット」。
- [Advanced Visualization Studio (AVS)](https://en.wikipedia.org/wiki/Advanced_Visualization_Studio) - Nullsoft による Winamp 用ビジュアライザ。独自エフェクトチェーンを構築可能。
- [G-Force](https://en.wikipedia.org/wiki/G-Force_(visualization_software)) - Andy O'Meara による人気ビジュアライザ。精巧で有機的な 3D ビジュアル。
- [harmony_visualizer](https://github.com/Frieve-A/harmony_visualizer) - Frieve-A による、MIDI 入力のハーモニー可視化ツール。

---

## オーディオ解析・メーター

スペクトログラム、MIR、ラウドネスメーター、レビュー用ユーティリティ。

- [Sonic Visualiser](https://www.sonicvisualiser.org/) - 音楽録音の詳細な可視化・解析・注釈向けオープンソースアプリ。Vamp フィーチャプラグイン対応。([GitHub](https://github.com/sonic-visualiser/sonic-visualiser))
- [Spek](https://www.spek.cc/) - エンコードや転送確認向けの軽量オープンソース音響スペクトル解析（スペクトログラム）。([GitHub](https://github.com/alexkay/spek))
- [Prism](https://github.com/Boof2015/prism) - スペクトラム、オシロ、ベクトルスコープ、スペクトログラム、VU、LUFS などを備えた無料 OSS メーター/ビジュアライザ（デスクトップおよび VST3/AU）。
- [Vamp plugins](https://vamp-plugins.org/) - Sonic Visualiser などで使う音声特徴抽出プラグイン API/コレクション。
- [librosa](https://librosa.org/) - 音楽・音声解析向け Python ライブラリ（スペクトログラム、MFCC、onset/beat、MIR）。([GitHub](https://github.com/librosa/librosa))
- [aubio](https://aubio.org/) - onset・ピッチ・テンポ・ビート・MFCC 向け C/Python ライブラリと CLI。([GitHub](https://github.com/aubio/aubio))
- [Frieve's Sound Toolbox](https://github.com/Frieve-A/sound_toolbox) - Frieve-A によるブラウザ上のサウンド関連ツール集。プレビュープレーヤー、ABX テスター、デジタルサンプリングビジュアライザーなど。
- [DIP Bench](https://github.com/Frieve-A/dipbench) - Frieve-A によるデジタルピアノのベンチマークツール。
- [Audio Review](https://github.com/Frieve-A/audioreview) - Frieve-A による、ヘッドフォン・スピーカー・アンプなどを客観評価するレビューサイトのソース。

---

## DJ・ライブ

- [Mixxx](https://mixxx.org/) - ビートマッチ、エフェクト、MIDI/HID コントローラ、ライブラリ管理を備えた無料オープンソース DJ ソフト。([GitHub](https://github.com/mixxxdj/mixxx))

---

## インフラ・I/O

多くの Linux（および一部クロスプラットフォーム）ツールの下で使う低レイテンシ音声配管。

- [JACK](https://jackaudio.org/) - プロ向け低レイテンシ音声接続キット。Linux スタジオグラフの中核として依然重要。
- [PipeWire](https://pipewire.org/) - PulseAudio と JACK を置き換え/橋渡しできる現代的な Linux マルチメディアサーバー。
- [SonoBus](https://sonobus.net/) - リモートセッションや共同作業向けの、低レイテンシ P2P ネットワーク音声ストリーミング（OSS、スタンドアロン/プラグイン）。([GitHub](https://github.com/sonosaurus/sonobus))

---

## ライブラリ・フレームワーク

アプリ、プラグイン、研究コードの構成要素。

- [JUCE](https://juce.com/) - [プラグインホストとフォーマット](#プラグインホストとフォーマット) を参照。
- [librosa](https://librosa.org/) / [aubio](https://aubio.org/) - [オーディオ解析・メーター](#オーディオ解析メーター) を参照。

---

## 関連リスト

- [OpenAudio](https://github.com/webprofusion/OpenAudio) - オープンソースのオーディオアプリ・プラグイン・ライブラリのカタログ。
- [awesome-linuxaudio](https://github.com/nodiscc/awesome-linuxaudio) - Linux 向けオーディオソフトの大規模リスト（DAW、シンセ、エフェクト、ユーティリティ）。
- [awesome-audio-dsp](https://github.com/BillyDM/awesome-audio-dsp) - オーディオ DSP リソース、OSS プラグイン、学習素材。
- [Linux DAW](https://linuxdaw.org/) - Linux DAW / プラグインのキュレーションディレクトリ。
- [awesome.re](https://awesome.re/) - Awesome マニフェスト。

---

## コントリビューション

コントリビューション歓迎です。ツール追加、リンク切れ修正、カテゴリ提案はプルリクエストでどうぞ。

**公式/ドキュメントの耐久性のある URL**、短い説明、実出荷されているツールを優先してください。製品名はそのまま。オープンソースは明示すると分かりやすいです。

## ライセンス

[LICENSE](LICENSE) を参照してください。

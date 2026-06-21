# コツコツ英検 音声パック

聞き流し（バックグラウンド再生）用の事前生成音声。本体アプリ [kotsukotsu-english] が後からダウンロードして使う。

- 生成: edge-tts（en=en-US-AriaNeural / ja=ja-JP-NanamiNeural）
- 配布: 級ごとの zip を Releases に置く（例: `audio-pre2.zip`）
- 各クリップのファイル名は `<id>_<kind>_<hash>.mp3`（hash=元テキストsha1先頭8桁。テキスト変更時の同期用）
- kind: hw(見出し語) / mean(意味) / colen・colja(コロケ) / ex0en・ex0ja(例文)

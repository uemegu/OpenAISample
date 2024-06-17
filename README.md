# OpenAISample

## whisper_browser_sample.html

OpenAI の Audio API（whisper) をブラウザ完結でマイク入力→文字起こしまで実行するサンプルです  
初回のStartボタンを押した後は追加でJS/WASMのダウンロードが実行されるため、少し待ってから音声の取得が始まります

This is a sample of OpenAI's Audio API (whisper) for microphone input to transcription with a simple browser interface.  
After pressing the Start button for the first time, additional JS/WASM downloads will be executed, so wait a bit before starting to acquire audio

### Reference

* https://knowledge.sakura.ad.jp/34497/
* https://zenn.dev/tatsuyasusukida/articles/097321c14ec6f5


## chatGPT_and_SpeechSysnthesis.html

OpenAI の Chat API（ChatGPT) の応答をストリーミングで処理しながらVOICEVOXで音声合成して喋らせるサンプルです

This is a sample that synthesizes speech using VOICEVOX while processing the responses from OpenAI's Chat API (ChatGPT) in a streaming manner.

### Reference

* https://zenn.dev/himanushi/articles/99579cf407c30b
* https://qiita.com/mikito/items/21aa74c3850a70c647f7


## tts_browser_sample.html

OpenAI の　Text-to-Speech をブラウザ完結で動かすサンプルです

This is a Text-to-Speech service of OpenAI.

## voicebox_sample.html

ローカルのVOICEVOXサーバーを呼び出して音声合成をするサンプルです

This is a sample that calls a local VOICEVOX server and synthesizes speech.

# tool_openai_whisper

* 此文檔紀錄如何用 R 套件 [audio.whisper](https://github.com/bnosac/audio.whisper)來使用 OpenAI Whisper 語音轉逐字稿的服務
* 你也可以使用此替代軟體 [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper)，但免費版只支援到 Small 模型。你可以先試試看，若準確度不佳，再來考慮此份代碼
* 建議將此 .Rmd 複製到你的專案資料夾使用，避免覆蓋掉原檔案
* 音檔的前 30 秒是 whisper 用來辨識音檔的時間，若你的音檔前面是不相干的內容或空白建議先剪掉，否則很容易整篇都出現「無法辨識」

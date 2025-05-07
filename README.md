const responses = [
    {
      keywords: ["天氣", "氣溫", "氣象"],
      replies: ["今天晴朗 ☀️", "有點陰，但不會下雨 ☁️", "可能會有午後雷陣雨 ⛈️，出門請帶傘！"]
    },
    {
      keywords: ["你是誰", "你叫什麼", "你是什麼"],
      replies: ["我是你的 AI 小幫手！🤖", "我被設計來幫助你解決問題～", "我雖然不是人類，但我很樂意幫你 💡"]
    },
    {
      keywords: ["時間", "幾點", "現在"],
      replies: [() => `現在時間是 ${new Date().toLocaleTimeString()}`]
    },
    {
      keywords: ["再見", "掰掰", "bye"],
      replies: ["掰掰～祝你有美好的一天！🌈", "下次再見囉～", "我會想你的 💕"]
    }
![image](https://github.com/user-attachments/assets/1c63516f-e3c8-473a-a527-cbebd7cfbadc)

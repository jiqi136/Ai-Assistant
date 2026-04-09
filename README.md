
[ **English** ] | [ [**中文版**](https://github.com/jiqi136/Ai-Assistant/blob/main/Chinese.md) ] [远古洛书-无限数值幻方](https://github.com/jiqi136/Magic-square/blob/main/%E8%BF%9C%E5%8F%A4%E6%B4%9B%E4%B9%A6-%E6%97%A0%E9%99%90%E6%95%B0%E5%80%BC%E5%B9%BB%E6%96%B9-%E4%B8%AD%E6%96%87.md)
[Infinite Numerical Magic Square](https://github.com/jiqi136/Magic-square)


---

[Open Source] Novel Writing & AI Programming Assistant (V23.1) Green Portable Edition
---
## Software Name
[Open Source] Novel Writing & AI Programming Assistant (V23.1) Green Portable Edition
## Supported Platforms
Windows 7 / Win10 / Win11

---

**Core Highlight: Adapts to mainstream API route relays, using both domestic and overseas hottest AI models via relay**

---

![B3.png](https://h1.appinn.me/file/1757443254500_B3.png)



### 🔥 Core Advantages  
| **Feature** | **Description**  | 
| :--- | :---  | 
| **Integrates World's Hottest AI Models** | Adapts to mainstream API route relays, using relayed models such as Gemini, Claude, GPT, Grok, etc.  | 
| **Best-in-Class Image Generation** | Adapts image generation AI model Nano Banana [G Gemini * Nano Banana gemini-flash-image] | 
| **Multimodal**      | Image reading and PDF file reading capabilities. | 
| **Multi-Channel AI Engine** | Official DeepSeek + multiple free R1.  | 
| **Custom Integration of Various Models** | Besides deepseek-r1, you can also integrate various AI models such as Qwen, Doubao, etc.  | 
| **Free Format Conversion** | One-click conversion of AI content from any webpage to plain text, web HTML, forum BBCode for easy sharing | 
| **Custom Web Search Settings** | Invokes local browser, fetches content from dozens of webpages in real-time with full-text reference | 
| **Zero Hardware Requirements** | Compatible with Windows 7+ systems, runs instantly on any ordinary computer | 
| **Data Security** | Local encrypted SQLite storage, chat history supports password hiding (click ◆ to hide) | 
| **History Search** | Supports keyword search in local storage for quick retrieval of past records | 
| **Favorites** | One-click bookmarking of important conversations, supports categorization and custom notes for easy personal knowledge base construction. | 




![tu1.png](https://github.com/jiqi136/Ai-Assistant/blob/main/app/tu1.png?raw=true)

![B1.png](https://h1.appinn.me/file/1757443253459_B1.png)

---

1.  **Smart Conversation Management, Flexible and Resource-Saving:**
    *   **Precise Context Control:** Unique multi-round conversation management options, clear context on demand to save token consumption and maintain conversation focus:
        *   `Clear All Context`: Clears the entire conversation context to restart the dialogue.
        *   `Multi-round Conversation Management Tool`: Remove individual conversation turns arbitrarily, master the entire conversation context for optimal AI dialogue.
        *   `Context Input Text`: Input custom text within the multi-round conversation context to manipulate the entire dialogue context.



![tu2B.png](https://github.com/jiqi136/Ai-Assistant/blob/main/app/tu2B.png?raw=true)


---

#  **📥 Program & Open Source Code [Download Link]:  :**

*   **Ai-Assistant/releases  Download:** [https://github.com/jiqi136/Ai-Assistant/releases](https://github.com/jiqi136/Ai-Assistant/releases)
*   
*   **sourceforge.net Download  :**
[https://sourceforge.net/p/ai-assistan](https://sourceforge.net/p/ai-assistan)



---

### Go Language Source Code Build Instructions
Building the project requires only the following two core files:
- **`main.go`**  
  The program entry file, containing the main business logic implementation.
- **`go.mod`**  
  The Go module definition file, used for managing project dependencies and version information.
Download the above files and import them into the project directory to start building.

---


## 📜 Apache 2.0 Open Source License

This project is licensed under the permissive **Apache 2.0 License**. This means you have complete freedom to use the source code.

You can: (Plain English explanation)
-   ✅ **Commercial Use:** Allows using this work and its derivatives for commercial purposes and selling them.
-   ✅ **Modify and Redistribute:** Allows modifying the code and redistributing it under either open-source or closed-source terms.

---
## Like this project? Don't forget to give it a ⭐! Your support is the motivation for continued maintenance.

---
---
### This program uses the lightweight desktop PC-Gui framework

## PC-Gui: Born for AI, a lightweight desktop GUI framework natively supporting Deepseek-style real-time typewriter streaming output! 🎉

[ [**Apache 2.0 Open Source Code https://github.com/jiqi136/PC-Gui**](https://github.com/jiqi136/PC-Gui) ] 

> 💡 **Core Philosophy: Rapid Development · Minimal Size · Native Performance · Helping Build Quality Tools Users Are Willing to Pay For**

On the desktop, users' demand for efficient, practical tools has never waned, and they have a strong willingness to pay.
PC-Gui aims to help developers quickly respond to this market need, building compact yet powerful commercial desktop applications using the simplest and most stable technologies.

---

### Core Tech Stack

Abandoning complex dependencies and bloated third-party GUI libraries, returning to the essence of programming: **building desktop applications with a backend mindset**.
By using a stable Go backend to provide web services driving a flexible web frontend, achieving unparalleled lightweightness and performance.

| Component | Technical Details |
| :--- | :--- |
| **Backend Service** | Go language, provides local web services based on the standard library `net/http`. |
| **Frontend Interface** | HTML, JavaScript, CSS standard web technologies. |
| **Data Storage** | Locally encrypted SQLite database, lightweight and reliable. |


<br>

### Core Advantages & Multi-Solution Comparison

| Category | ✅ PC-Gui Advantages | ⚠️ Other Solutions Comparison |
| :--- | :--- | :--- |
| **🚀 Zero Dependency Runtime** | **Backend Go language** enables rapid development, strong typing for easy maintenance; cross-compiles to a single executable file, no runtime or library installation required by users, double-click to run. | ⚠️ Requires users to pre-install and configure complex environments and dependencies like WebView2, Python, C++, Node.js. |
| **🎨 Interface Technology (HTML)** | **HTML** frontend interface can be quickly generated using numerous templates and AI tools, achieving high efficiency and easily creating beautiful, modern visual styles. | Traditional GUI library interfaces are often outdated with high customization difficulty. |
| **AI Streaming Output** | Only requires simple asynchronous handling to achieve streaming output of AI content, enhancing user experience. | Implementing streaming output typically requires handling complex callbacks or multi-threading. |
| **Markdown Rendering** | Perfectly renders Markdown format returned by AI, with syntax highlighting for various languages. | Chatbox, Cherry, etc., have relatively basic Markdown rendering and code highlighting. |
| **Single File Deployment** | Using Go's standard library `embed`, all static resources (images, CSS, etc.) can be directly bundled into a single executable file, and directly accessed by reusing the HTML service. | Bloated dependencies: Requires external packaging tools, resulting in large bundle sizes or scattered files, complex deployment. |
| **📦 Minimal Size** | Packaged application size is only **10-25MB**, effortless distribution and download. | ⚠️ Applications based on Electron / WebView2 typically exceed **100MB**. |
| **🧠 Ultra-Low Memory Usage** | Runtime memory usage is only about **8MB**, CPU overhead nearly zero, light and fast. | ⚠️ Electron / WebView2 applications easily consume over **500MB** of memory. |
| **Code Security** | Go compiled binary files, combined with garble obfuscation technology, effectively prevent logic from being decompiled. | Easy to leak: Python, Node.js scripting languages are extremely easy to decompile and expose, no trade secrets. |
| **💻 Cross-Platform Compatibility** | Go language natively supports Windows 7/10/11, Linux, macOS, covering the widest user base. | Solutions like Webview2 do not support older systems like Windows 7. |
| **Runtime Stability** | Core relies only on Go's official standard library, ensuring long-term stable operation without crashes. | Relies on many third-party libraries, with risks of version compatibility and stability issues. |
| **💯 Complete Control** | Core code relies only on Go's official standard library, **no third-party GUI framework black boxes**, code is completely self-controllable, facilitating long-term maintenance and troubleshooting. | ⚠️ Relies on large third-party frameworks with redundant code, making troubleshooting difficult when encountering complex issues. |
| **🌐 Globalization Support** | Interface based on standard web pages, can directly leverage the browser's **built-in translation feature**, easily supporting hundreds of global languages. | Requires built-in multilingual text libraries, massive effort. |
| **💡 Cross-Language Reusability** | The framework concept is clear, any language that supports HTTP services (e.g., C#, Python, Rust) can learn from it. | Frameworks are deeply tied to specific languages or platforms, difficult to migrate. |


<br>

## To Developers

Today, as the AI wave sweeps the globe and the job market faces challenges, mastering a skill that can rapidly create value is crucial.

I hope PC-Gui, this lightweight and efficient framework, can become a sharp tool in your hands, helping you quickly turn ideas into reality, develop practical desktop tools users are willing to pay for, and ultimately achieve personal value and commercial success.

[ [**Apache 2.0 Open Source Code https://github.com/jiqi136/PC-Gui**](https://github.com/jiqi136/PC-Gui) ] 


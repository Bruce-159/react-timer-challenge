#React Timer Challenge  
[🔗 GitHub 部署頁面](https://bruce-159.github.io/react-timer-challenge/)  

這是一個結合計時器、挑戰模式與 React 進階功能的專案，旨在強化我對 Refs、DOM 操作、狀態與效能優化、Modal 元件管理 與 Portals 等核心觀念的理解與實作能力。  
  
此專案涵蓋以下 React 關鍵技術與開發觀念：  

Forwarding Refs 與 useImperativeHandle  
自訂 Modal 元件時使用 forwardRef 將 ref 傳遞到內部元素  
使用 useImperativeHandle 定義元件公開的控制 API（例如 .open()、.close()）  
  
Portals：將 Modal 元件渲染至 root 外的節點  
使用 ReactDOM.createPortal() 將 Modal 元件渲染到 #modal-root，避免樣式覆蓋與結構混亂  
  
 Component Composition  
將挑戰邏輯與 UI 拆分為獨立元件，如 ChallengeInput, ChallengeTimer, ResultModal 等，提高可維護性  

##預覽畫面  
![image](https://github.com/user-attachments/assets/02e9909f-7364-429e-9142-8b68703e384a)
![image](https://github.com/user-attachments/assets/a0b83f81-0bcc-458f-a5fd-d0327e87ebf4)


香港 3D 極速駕駛｜PWA V0.1

1. index.html：遊戲主程式
2. manifest.webmanifest：加入 iPhone 主畫面設定
3. sw.js：基本快取
4. icons/：App 圖示

使用注意：
- 必須部署在 HTTPS 網址，Safari 才可「加入主畫面」。
- Three.js 由 jsDelivr CDN 載入，首次開啟需要網絡。
- 目前快取的是遊戲外殼，不代表完整離線遊玩。
- 這是 PWA，不是已簽署的原生 iOS IPA。
- 正式原生 App 仍需 iOS 建置及簽署流程。
- V0.1 車輛與城市是程序化幾何原型，尚非最終寫實資產。

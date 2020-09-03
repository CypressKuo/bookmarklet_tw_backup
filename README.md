# bookmarklet_tw_backup

(備份用)

safari bookmarklet 簡體轉繁體

把 bookmarklet_tw.js 的內容放到 jsbin => https://output.jsbin.com/budohow/1.js

safari 書籤加入
javascript:(function(){var%20s=document.getElementById("tongwenlet_tw");if(s!=null){document.body.removeChild(s);}var%20s=document.createElement("script");s.language="javascript";s.type="text/javascript";s.src="https://output.jsbin.com/budohow/1.js";s.id="tongwenlet_tw";document.body.appendChild(s);%20})();

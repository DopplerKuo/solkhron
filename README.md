## 檔案結構
- `public/index.html` 為入口
- 其餘資源在 `public/aseets/` 裡面
其中使用 scss，推薦用 prepros 去做編譯
cool-style.com.tw

## Prepros 
1. 可以將 scss 編譯成 css，其他工用可自行研究
2. 開啟 localhost
備註：用 prepros 時，新增專案只需要將 public 資料夾拖曳進去即可，最外層不需要（不然會跑不起來）

## 部署推薦： Heroku
如果有任何疑問可以問 doppler.kuo@gmail.com
`.config`, `Gemfile`, `Gemfile.lock` 以及將資源都放進 public 是使用 ruby 語言為底部署到 Heroku 的其中一種方式，隨時可以根據喜好換主機

### 部署方法
(需要申請 heroku 帳號，並且我把專案 share 權限給開發者)
`git remote add heroku https://git.heroku.com/solkhron.git`
`git add .`
`git commit -m "something"`
`git push heroku master`
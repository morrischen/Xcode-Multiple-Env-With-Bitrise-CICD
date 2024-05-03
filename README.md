## Xcode多環境與Bitrise自動部署設定

### 1. 建立Xcode環境設定檔

* 建立`Development xcconfig`
* ![Development設定檔](./images/fig.1.png)
* 建立`Production xcconfig`
* ![Production設定檔](./images/fig.1-2.png)

### 2. 設定Xcode Project的Configurations

* 建立`Debug Configurations`，並選擇環境設定檔為`Development xcconfig`
* 建立`Stage Configurations`，並選擇環境設定檔為`Stage xcconfig`
* 建立`Release Configurations`，並選擇環境設定檔為`Production xcconfig`
* ![Project Configurations](./images/fig.2.png)

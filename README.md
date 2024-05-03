## Xcode多環境與Bitrise自動部署設定

### 1. 建立Xcode環境設定檔

* 建立`Development xcconfig`
* ![Development設定檔](./images/fig.1-1.png)
* 建立`Production xcconfig`
* ![Production設定檔](./images/fig.1-2.png)

### 2. 設定Xcode Project的Configurations

* 建立`Debug Configuration`，並選擇環境設定檔為`Development xcconfig`
* 建立`Stage Configuration`，並選擇環境設定檔為`Stage xcconfig`
* 建立`Release Configuration`，並選擇環境設定檔為`Production xcconfig`
* ![Project Configurations](./images/fig.2.png)

### 3. 建立Xcode Build Schemes

* 建立`Development Scheme`
* ![New Development Scheme](./images/fig.3-1.png)
* ![New Development Scheme](./images/fig.3-2.png)
* 設定`Development Scheme`
* ![Edit Development Scheme](./images/fig.3-3.png)
* ![Edit Development Scheme](./images/fig.3-4.png)

### 4. 設定Xcode Signing
* 設定Signing為`Automatically Manage Signing`
* ![Xcode Signing](./images/fig.4.png)

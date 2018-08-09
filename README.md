The Traditional Chinese translation pack for SonarQube
=======

Author: Poy Chang <poypost@gmail.com>

Latest version: (https://github.com/poychang/sonar-l10n-zh-tw/releases/latest)

compatibility Matrix: 

---

這是 SonarQube 的繁體中文包

相容列表如下：

**SonarQube**    |**7.0**|**7.1**|**7.2**|       |       |       |       |       |
-----------------|-------|-------|-------|-------|-------|-------|-------|-------|
sonar-l10n-zh-tw |       |       |7.2.x  |       |       |       |       |       |

## 安裝方式

請至 [Release](https://github.com/poychang/sonar-l10n-zh-tw/releases) 下載最新版的 `.jar` 檔，下載完成後複製至 SonarQube 安裝目錄下的 `\extensions\plugins` 資料夾中，重新啟動系統即可。

## 開發相關

對應的 SonarQube 版本升版時`,請同步修改下列 2 個檔案內容：

* `pom.xml`
    * 修改 `<version>` 區段的版本號
* `.travis.yml` 
    * 修改 `before_deploy` 的 `git tag` 指令
    * 修改 `deploy` 的 `file` 檔名

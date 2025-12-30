# 編譯專案

## 將文件轉為 HTML 網站

### 手動編譯

請先取得 mdbook（可以在[其專案](https://github.com/rust-lang/mdBook)的 [releases](https://github.com/rust-lang/mdBook/releases) 中找到已編譯好的執行檔 ）

然後到本專案的資料夾，執行 `mdbook build` 即可。

完整的指令如下：

```shell
C:\> cd {{專案資料夾}}
C:\{{專案資料夾}}> mdbook build
```

### By Github Actions

本專案已經有撰寫好 github action

#### 自動編譯

文件每次更新都會自動編譯。

首先進去 **Actions** > **Build book to html files** 

![Actions](template-resources/image.png)

![Build book to html files](template-resources/image-1.png)

選擇最新一次執行任務。

![最新一次執行任務](template-resources/image-2.png)


任務執行完成後，**Artifacts**會有編譯好的 HTML 網站打包成 .zip 壓縮檔。

![alt text](template-resources/image-3.png)


#### 手動執行 github action

一樣進去 **Actions** > **Build book to html files** 

然後選擇 `Run workflow 🔻` 按鈕，選擇`Run workflow`即可




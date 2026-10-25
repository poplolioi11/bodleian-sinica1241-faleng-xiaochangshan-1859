# 《論發冷小腸疝兩症》：1859 年博濟醫局本 AI 獨立校讀資料

## 正式發布狀態（2026-10-25）

**v0.2.0 已正式發布，DOI 已在 DataCite 登記為 findable。**

- 本版 DOI：[10.5281/zenodo.23636930](https://doi.org/10.5281/zenodo.23636930)。
- 全版本 DOI：[10.5281/zenodo.23636108](https://doi.org/10.5281/zenodo.23636108)。
- 初錄 v0.1.0 DOI：[10.5281/zenodo.23636109](https://doi.org/10.5281/zenodo.23636109)。
- [v0.2.0 固定發行包](https://github.com/poplolioi11/bodleian-sinica1241-faleng-xiaochangshan-1859/releases/tag/v0.2.0)，提交 `5908a17d6bf1143ca7ecbe5a9673c724fbaf29c1`。

兩端公開 ZIP 已匿名下載比對，47,420 bytes、16 個檔案逐位元一致；SHA-256：`88d74baa0b9113c3b950bd2e90b2682e4130158e3f260a7ba94c8ba17cbd6fbb`。本版保留3個疑字與2處刻點未解，仍未經人類雙校、專家審定或同儕審查。

本節是封存後僅補入 main 分支 README 的狀態說明。固定 ZIP、tag 內的 reserved／草稿字樣及 `VALIDATION.json` 的 `doi_status_at_build` 均記錄製備當時狀態；本次沒有替換封存檔案或改寫舊 tag。`SHA256SUMS` 只用來驗證固定發行包，不適用於後續已更新的 main README。

整理者：**poplolioi11**。資料、編碼與封存包 **v0.2.0**；日期 **2026-10-25**。

底本為牛津大學 Bodleian Libraries 藏 **Sinica 1241**，卷首「咸豐九年新鍥」「博濟醫局藏板」。Serica 書目將作品歸於 **J. G. Kerr（嘉約翰，1824–1901）**；這是歷史作者歸屬，並非本資料集整理者或館方背書。

本版完成全部10幅固定影像原印文字層的獨立AI視讀、逐單位比較及回圖處置；保留**3個疑字、2處刻點位置未解**。這是AI校讀資料，未經人類雙校、專家審定或同儕審查，未測逐字準確率。

## 範圍與下載

- [book.json](book.json)：固定原文、逐頁來源、單位與疑讀。
- [book.txt](book.txt)：直接閱讀的UTF-8文字；`〔unit:…〕`是現代導航標籤。
- [book.tei.xml](book.tei.xml)：TEI P5，與JSON逐單位字串及順序一致。
- [source-pages.json](source-pages.json)：來源頁序、影像URL、尺寸及SHA-256。
- [uncertainties.json](uncertainties.json)：3個未定字與2處未定刻點。
- [CORRECTIONS.json](CORRECTIONS.json)：相對v0.1.0的逐項訂正、小註掛接及覆核摘要。

10幅掃描呈現18個可見書面，包含封面、封裡及空白；其中12面有原印文字。官方pp.[1]–[14]是內頁面標籤，與原刻版心葉碼分開記錄。全篇宗教前言、醫學正文、題名、刊記、小註、版心及圖題均在範圍內。全冊外觀有一幅疝帶線圖，本包僅保存其文字描述及圖題，未重建幾何。後加英文展覽標籤、手寫、藏章與拍攝尺卡排除於原作轉錄。

本版有**116個定位單位、1689個Unicode碼點**，對47個既有或新增單位作文字／點號／層別調整；包含7個初錄漏錄的版心單位，以及將已錄小字另立1個單位。原有108個unit ID全部保留。版本差異及未解以檔案記錄為準；單位數、疑字數與校讀覆蓋不代表準確率。

## 覆核、字形與限制

初錄由Gemini `gemini-3.8-flash-high`分兩批讀圖。另一個未見初錄的Codex工作先讀全部10幅固定2200px影像，封存讀字後才比較；比較階段另用同一官方canvas的8幅4000px影像回看分歧。主代理回到底本裁定關鍵文字、圖題、量詞小註、7個新增葉碼及未解處。

獨立工作以`gpt-6-astra / ultra`設定請求，但工作者只回報可確認為GPT-6（Codex），未取得更細的實際型號證據；本包不把設定值當作實際模型驗證。全部108個初錄單位、15筆初錄疑讀及10幅版式均已比較。39欄刻點專項中37欄可裁定、2欄回圖後仍未解，沒有尚未查的項目。完整問答、專用程式、提示、技能、工作裁片及私人紀錄未公開，本包不承諾從原圖完整重跑。

忠實保留可辨原字與異體；原刻點形以「、」編碼，數位字形不是原刻字形摹本。保留原書可見但語意異常的用字，不以經文或現代醫學知識改成通行說法。疑字`start/end`採Unicode碼點0起算半開區間`[start,end)`；刻點缺席的疑讀以相鄰實字為錨，並非該字未識。小註的子行與掛接邊界另見`CORRECTIONS.json`；TEI按原單位分層存字，未另編完整校勘app。

資料可供定位、檢索及後續校訂；精確引文、字形、語詞／數量分析請核對原圖與疑讀。圖形幾何及機械效能不在本包可分析範圍。本書為十九世紀醫學史材料，並非現代診療指引。

## 底本、查重與權利

[Digital Bodleian](https://digital.bodleian.ox.ac.uk/objects/3a397e45-295b-4a9c-a8a5-1b2db808b2b0/) ／ [官方IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/3a397e45-295b-4a9c-a8a5-1b2db808b2b0.json) ／ [Serica醫學書目](https://serica.ie/SericaProject/data/976.html)。

2026-10-25的有限查重包含維基文庫（含四庫相關查詢）、CTP、Kanripo官方公開庫索引、識典及公開網路。已查範圍未找到可用文字；Kanripo網站受限，未聲稱全庫全文檢索成功。不宣稱全球首次或全球沒有其他轉錄。

1859年已刊歷史原文按公有領域處理，不新增商用、改作或署名限制。具著作權的自有說明與編排採**CC BY 4.0**。館方影像仍受[CC BY-NC 4.0與館方條款](https://digital.bodleian.ox.ac.uk/terms/)規範；本包不包含掃描、裁片或館方標誌，也不代館方重新授權。詳[RIGHTS.md](RIGHTS.md)、[LICENSE.md](LICENSE.md)。

## 引用、固定版本與訂正

poplolioi11（2026）。《論發冷小腸疝兩症》：1859年博濟醫局本AI獨立校讀資料（v0.2.0，保留未解）［資料集］。引用本版DOI並附unit ID、原頁及館藏底本；歷史作者與本次整理分開引用。

[本版固定GitHub發行](https://github.com/poplolioi11/bodleian-sinica1241-faleng-xiaochangshan-1859/releases/tag/v0.2.0) ／ [CITATION.cff](CITATION.cff)。本包製備時的DOI預留狀態列於文末；正式公開狀態以Zenodo紀錄及GitHub Release為準。

初錄v0.1.0已於2026-10-25正式發布並完成公開回讀：版本DOI [10.5281/zenodo.23636109](https://doi.org/10.5281/zenodo.23636109)，全版本DOI [10.5281/zenodo.23636108](https://doi.org/10.5281/zenodo.23636108)。第一版固定包中的reserved／草稿字樣記錄製備當時狀態；其檔案、tag及DOI均完整保留。

[VALIDATION.json](VALIDATION.json)列實際JSON schema、TXT／TEI逐字回讀、來源對應、官方TEI Relax NG與CFF schema檢核。`SHA256SUMS`對應本次固定白名單包，不是日後更新的main分支全部檔案。格式、雜湊、DOI及模型一致不證明讀字正確。

請在[Issues](https://github.com/poplolioi11/bodleian-sinica1241-faleng-xiaochangshan-1859/issues)附unit ID、原頁、現錄、建議讀法與影像依據；修訂另發新版本，不覆寫已引用包。

## English summary

Source-first independent AI image reading, complete comparison and source adjudication of the 1859 Boji imprint, Bodleian Sinica 1241, attributed by Serica to J. G. Kerr. Version 0.2.0 covers the original printed text in all ten fixed images: eighteen visible book surfaces, twelve text-bearing faces. The complete religious preface is included. The truss diagram is described, not geometrically reconstructed. There are 116 units, 1689 Unicode code points, three unresolved graphs and two unresolved punctuation locations. Human double collation, expert review and peer review have not been performed; no measured accuracy is claimed. JSON/TXT/TEI, source hashes, corrections, note attachments and layered rights are provided. Source scans, processing programs, prompts and private work records are excluded. Public-domain historical text has no new restrictions; copyrightable original documentation is CC BY 4.0.

預留版本 DOI（reserved；尚未確認正式發布）： https://doi.org/10.5281/zenodo.23636930

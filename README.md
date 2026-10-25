# 《論發冷小腸疝兩症》：1859 年博濟醫局本初錄資料集

整理者：**poplolioi11**。資料與封存包版本：**v0.1.0**。文件日期：2026-10-25。

本資料集依牛津大學 Bodleian Libraries 所藏 **Sinica 1241** 的數位影像整理《論發冷小腸疝兩症》。品質狀態為**指定原印文字範圍完整初錄，未經獨立覆核**；「完整」指下述範圍已處理，並非逐字準確的保證。未經人類雙校、專家審定或同儕審查。

## 作品與底本

底本卷首載「咸豐九年」「博濟醫局藏板」，即 1859 年刊本。Serica 書目將作品歸於 **J. G. Kerr（嘉約翰，1824–1901）**；作者歸屬採書目依據，與底本可見刊刻資訊分開記錄。

- [Digital Bodleian 館藏影像](https://digital.bodleian.ox.ac.uk/objects/3a397e45-295b-4a9c-a8a5-1b2db808b2b0/)
- [館方 IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/3a397e45-295b-4a9c-a8a5-1b2db808b2b0.json)
- [Serica 醫學書目](https://serica.ie/SericaProject/data/976.html)

10 幅影像共呈現 18 個可見書面，包含封面、封裡及空白；本版初錄 **12 個原印文字面**。官方影像標籤的 pp. [1]–[14] 是 14 個內頁面，其中有空白，與原刻版心的一、二、三、四及書目頁數分開記錄，不互相推算。詳細定位見 [PROVENANCE.md](PROVENANCE.md)。

收錄原作題名、刊記、宗教前言、醫學正文、圖題及可辨版心文字；宗教前言保留全文。書中一幅疝帶線圖保留圖題、文字標示及描述，**未重製幾何圖形**。後加英文展覽貼簽、手寫文字及館藏章不列入原作轉錄。這是文字資料集，並非全部視覺與收藏痕跡的摹錄。

## 資料格式

公開包提供 UTF-8 JSON、TXT、TEI XML，以及疑字紀錄。JSON 為本版固定文字與定位記錄；TXT 與 TEI 從同一份固定資料衍生。來源影像、影像裁片與專用處理程式不隨包提供。

文字順序依古籍右至左欄序及實際書面整理；影像 ID（c01–c10）與書面側別 R／L 用於對應底本。保留可見標點位置，但將原刻點號統一以頓號「、」表示，並非點形摹本。Unicode 字元盡量保留可辨異體；數位字元、字型呈現與原刻字形不完全等同。疑讀、缺損與圖像描述須連同資料中的狀態欄位閱讀。

## 方法、覆核與使用限制

本版以 Gemini gemini-3.8-flash-high 分兩批直接讀取指定影像；主代理檢查全幅版式、整理來源範圍及疑讀。共108個定位單位、1692個Unicode碼點，保留15筆整單位疑讀範圍。沒有□占位不表示逐字確定。疑讀 start/end 採Unicode碼點0起算半開區間[start,end)，本版大多定位至整欄，候選可能只涉及該欄部分字。完整初錄後尚未完成獨立影像校讀；AI 輸出、格式檢查及模型一致均不能作為準確率證明。專用提示、技能、處理程式及完整工作紀錄未公開，因此本包不提供由影像完全重跑的公開流程。

資料適用於原頁定位、初步檢索及後續校訂。引用關鍵字句、研究醫療觀念或分析字形時，應回到館方影像核對。線圖僅有文字描述，不適合據此研究圖形比例或構造。本書屬醫學史材料，內容反映十九世紀知識與宗教觀點，**不作現代醫療建議**。

2026-10-25 的有限查重涵蓋維基文庫（含四庫相關檢索）、Chinese Text Project、Kanripo 官方公開程式碼庫索引、識典及公開網路。已查範圍未找到可用電子文字；相符命中為書目與醫史介紹。這不表示全球不存在其他轉錄或未索引成果，也不以「首度數位化」作為本版主張。

格式驗證、逐字往返、官方TEI Relax NG與CFF schema的實際結果見 [VALIDATION.json](VALIDATION.json)。[PUBLIC-FILES.txt](PUBLIC-FILES.txt)列出固定公開白名單，[SHA256SUMS](SHA256SUMS)核對本次固定發行包；這些檢核不證明讀字正確。詳細驗證程式未公開。

## 權利與開放使用

已刊古籍原文不因本次轉錄新增使用限制；具著作權的自有說明與編排採 **CC BY 4.0**。館方掃描標示 **CC BY-NC 4.0**，本包不收錄掃描、裁片或館方標誌。資料開放政策不延伸到館方影像或未公開工具。詳見 [RIGHTS.md](RIGHTS.md) 與 [LICENSE.md](LICENSE.md)。本成果不代表與牛津大學或 Bodleian Libraries 合作，也不暗示其背書。

## 引用與版本

引用實際使用的固定版本：

> poplolioi11（2026）。《論發冷小腸疝兩症》：1859 年博濟醫局本初錄資料集（v0.1.0，完整初錄／未經獨立覆核）［資料集］。GitHub。

[固定版本入口](https://github.com/poplolioi11/bodleian-sinica1241-faleng-xiaochangshan-1859/releases/tag/v0.1.0) 與 [CITATION.cff](CITATION.cff) 供引用使用；封存 DOI 及製備時狀態列於本文末。

歷史作品、館藏底本及本次數位整理應分開引用。引用字句請附書面 ID、欄行定位及館方影像連結；版本號或 DOI 不代表審定本。檔案校驗值只能確認檔案完整性，不能證明讀字正確。

原文修訂將另發新版本，保存 v0.1.0 及公開訂正差異。可在 [Issues](https://github.com/poplolioi11/bodleian-sinica1241-faleng-xiaochangshan-1859/issues) 提供原頁、位置、現錄、建議讀法與影像依據；不必提供私人身分或使用報告。

## English summary

This dataset presents an AI-assisted initial transcription of the 1859 Boji Medical Institution edition of *Lun fa leng xiao chang shan liang zheng*, held as Bodleian Library Sinica 1241 and attributed by Serica to J. G. Kerr. Version v0.1.0 covers twelve printed text-bearing sides within ten digital images, including the religious preface. The hernia-truss diagram is described in words; its geometry is not reproduced. JSON, TXT and TEI XML retain source locations and uncertainty. No independent collation, human double proofreading, expert certification or peer review has been completed. Historical text carries no new restrictions; original copyrighted documentation is CC BY 4.0. Bodleian images are excluded and retain their separate terms.

預留版本 DOI（reserved；尚未確認正式發布）： https://doi.org/10.5281/zenodo.23636109

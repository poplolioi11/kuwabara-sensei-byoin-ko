# 桑原先生病因考（RB00002130） / Kuwabara Sensei byōinkō: Transcription Dataset

底本為京都大學附屬圖書館富士川文庫藏抄本 RB00002130，索書號 ク/22。京都大學附屬圖書館富士川文庫藏一冊和裝中本抄本，館目署桑原遜著。館目著錄附書為「与青木松柏子書」，原抄本附書題作「與青木松伯子書」。 [館目](https://rmda.kulib.kyoto-u.ac.jp/item/rb00002130) · [館藏 IIIF](https://rmda.kulib.kyoto-u.ac.jp/iiif/metadata_manifest/RB00002130/manifest.json)

《桑原先生病因考》是京都大學館目署桑原遜著的漢文醫學寫本，按病證討論症候與病因，主篇由骨熱等病證起筆。冊末合綴致青木松伯子的書札，保存醫學問答與書信交流的材料。此冊可供研究日本近世以漢文寫成的病因論述及醫家之間的文字往來。本資料集以京都大學附屬圖書館富士川文庫藏抄本 RB00002130 為底本，共取 22 幅固定影像，其中 17 幅用於轉錄正文，提供 JSON、TXT、TEI 和逐項覆核紀錄。此版為 AI 校讀稿，740 項比對中原有 208 項未解。人工全文二校待完成。

Kuwabara Sensei byōinkō is a medical manuscript in literary Chinese, attributed to 桑原遜 in Kyoto University’s catalogue. Its main text discusses signs and causes of illnesses, opening with a section on bone heat. An appended letter addressed to 青木松伯子 preserves material on medical enquiry and correspondence. The manuscript can inform research on Japanese medical writing in literary Chinese and written exchanges among medical practitioners. This dataset uses 22 fixed images from the Fujikawa Collection, Kyoto University Main Library, record RB00002130. The main text is transcribed from 17 pages. The AI-reviewed JSON, TXT and TEI transcription records 208 unresolved comparison items from the primary review. Full human collation is outstanding.

京都大學館目將主篇《桑原先生病因考》署為桑原遜著。第 20 幅左面附書署款的寶曆九年屬信件，現冊抄寫年代未詳。2016 是館方數位化年度。 [京都大學館目](https://rmda.kulib.kyoto-u.ac.jp/item/rb00002130)

Kyoto University’s catalogue attributes the main work to 桑原遜. The ninth year of Hōreki in the closing inscription on the left of image 20 dates the letter. The copying date of the extant manuscript is unknown. Kyoto University records digitization in fiscal year 2016.

[p003 原書前封](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002130%2FRB00002130_00003_0.ptif/full/2000,/0/default.jpg) · [p004 主篇起首](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002130%2FRB00002130_00004_0.ptif/full/2000,/0/default.jpg) · [p018 合綴篇界與附書題](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002130%2FRB00002130_00018_0.ptif/full/2000,/0/default.jpg) · [p020 附書署款](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002130%2FRB00002130_00020_0.ptif/full/2000,/0/default.jpg) · [p022 後封墨書](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002130%2FRB00002130_00022_0.ptif/full/2000,/0/default.jpg)

## 資料與校讀

- data/document.json 保留歷史文字、原圖位置、疑讀與缺口。
- data/text.txt 與 data/text.tei.xml 為全文與 TEI，附文字單位的對應檔。
- data/review.json 保留 740 項比對、未解 ID 和採用紀錄。定版仍有 208 項未解。
- data/manifest.json 與 PACKAGE-SHA256SUMS.txt 記錄固定發行的檔案雜湊。

底本的 22 幅館方 IIIF 影像均保有來源位置。錄文涵蓋封套、書衣、主篇、附書、署款及後封可見墨記。第 1、2 幅同一大書套題籤收錄一次，第 2 幅另錄獨立脊籤。第 18 幅右面是主篇結尾，左面另起附書。

The dataset retains the source locations of all 22 IIIF images. It includes the case and cover titles, main work, appended letter and its closing inscription, and visible rear-cover writing. The repeated large case label is recorded once, and the spine label in image 2 is a separate inscription. The main work ends on the right of image 18, and the letter starts on the left.

初錄與第二路讀稿各以同一批固定原圖為據。Claude 完成第 1–22 幅初錄與第 1–22 幅第二路讀稿。Claude 依原圖覆核 740 項比對。程式列出的 740 項比對均有逐項紀錄。採入 46 項有影像依據的更正，保留未解位置與候選。另有 36 項異讀保留原讀及候選。程式驗收確認公開 JSON、TXT 和 TEI 的逐欄內容一致。TEI 通過 P5 4.12.0 Relax NG。人工全文二校、專家審定和準確率量測待完成。

The two independent readings used the same fixed source images. Claude produced the first reading for images 1–22 and the second reading for images 1–22. Claude reviewed 740 comparison items against the images. The dataset records 740 comparison items. The edition incorporates 46 corrections supported by the images. The initial readings and alternatives remain recorded for 36 further proposed changes. Automated validation confirmed that the transcription content agrees column by column across JSON, TXT and TEI. The TEI passed P5 4.12.0 Relax NG validation. Full human collation, expert assessment and accuracy measurement are outstanding.

## 權利與引用

京都大學公告原資料保護期已滿及所藏圖像二次利用條件。新增且受著作權保護的說明與整理編排採 CC BY 4.0。 [權利說明](LICENSE.md)

曲宸宇（Chu, Chen-Yu）。2026。桑原先生病因考（RB00002130） / Kuwabara Sensei byōinkō: Transcription Dataset。v0.1.0。資料集。 [固定發行](https://github.com/poplolioi11/kuwabara-sensei-byoin-ko/releases/tag/v0.1.0) · [ORCID](https://orcid.org/0009-0003-9738-6914)

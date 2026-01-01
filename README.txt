README
（プログラムファイルをお使いになる前にお読みください）

本書『マーケティング・データ分析 -- 実務とリサーチをつなぐ』（田頭拓己著，2025年，有斐閣）をご購入いただきありがとうございます。
本フォルダには、本書の解説で使用しているRのプログラムコードおよびデータファイルを収録しています。

■ 収録内容と構成
ダウンロードしたフォルダ内には、章ごとのフォルダ（chapter01, chapter04...）が含まれています。
各章のフォルダ内には以下のファイルが格納されています。

例：「chapter04」フォルダの場合
・chapter04.Rproj ： RStudioプロジェクトファイル（※起動用）
・mktg04.R        ： Rスクリプトファイル（プログラム本体）
・data            ： 分析用データが入ったフォルダ

■ 動作確認環境
本ファイルの動作は、以下の環境で確認しています。
OS：Windows 11
Rバージョン：4.3.0
RStudioバージョン：2025.05.0

※これ以外の環境や、Rの新しいバージョンでは、挙動が異なる場合やエラーが出る可能性があります。

■ 使用方法
本書のプログラムを正しく動作させるために、以下の手順でファイルを開いてください。

1. 学習したい章のフォルダ（例：chapter04）を開きます。
2. フォルダ内にある拡張子が「.Rproj」のファイル（例：chapter04.Rproj）をダブルクリックします。
   → RStudioが起動し、その章専用の作業環境（ワーキングディレクトリ）が自動的に設定されます。
3. RStudioの画面右下の「Files」タブから、拡張子が「.R」のファイル（例：mktg04.R）をクリックして開いてください。

■ 文字コードについて
本ファイルは「UTF-8」形式で保存されています。Windows環境で日本語が文字化けする場合は、RStudioのメニューから [File] > [Reopen with Encoding...] を選択し、「UTF-8」を指定して開き直してください。

■ 利用条件・ライセンス（重要）
本フォルダに含まれるファイルは、種類によって利用条件が異なります。必ず以下をご確認ください。

【A. プログラムコード（.Rファイル等）】
プログラムコードは「MITライセンス」の下で提供されています。
著作権表示（Copyright (c) 2025 Takumi Tagashira）を含める限り、商用・非商用を問わず、複製・改変・再配布・販売などが自由に行えます。
（※具体的なライセンス条文は後述の [MIT License Text] を参照してください）

【B. データファイル（dataフォルダ内のファイル）】
データファイルは、MITライセンスの対象外です。
これらは、購入者が本書の内容を理解するための学習、および個人的な研究の範囲内でのみ利用可能です。
著者の許可なく、データファイルを第三者へ再配布すること、ウェブサイト等で公開すること、および商用利用することを固く禁じます。

■ 免責事項
ファイルの内容に誤りのないようできる限り注意を払いましたが、本ファイル（コードおよびデータ）を利用した結果生じた損害等については、著者および株式会社有斐閣は一切の責任を負いません。あらかじめご了承ください。
また、本ファイルの内容に関する個別の技術的なサポートや質問には応じかねますので、併せてご了承ください。

-- [ MIT License Text for Program Code ] -------------------------

MIT License

Copyright (c) 2025 Takumi Tagashira

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
------------------------------------------------------------------
2025年12月
株式会社有斐閣　書籍編集第2部
https://www.yuhikaku.co.jp/
------------------------------------------------------------------
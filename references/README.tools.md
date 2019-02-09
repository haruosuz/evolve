Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2018-12

----------

# tools
ツール

## Table of Contents
- [featuring](#featuring)
- [updates](#updates)
  - [2018](#2018)
- [unclassified](#unclassified)
- [OrthoFinder](#orthofinder)
- [tree](#tree)
  - [FastTree](#FastTree)
  - [RAxML](#raxml)
- [timetree](#timetree)
- [iTOL](#itol)
- [MEGA](#mega)
- [Gblocks](#gblocks)
- [trimAl](#trimal)
- [HyPhy](#hyphy)

----------
## featuring

http://d.hatena.ne.jp/haruosuz/20080813
系統解析 - Haruo Suzuki / Bioinformatics

August 6, 2013
http://yuifu.github.io/pplacer-tutorial/
pplacerの使い方 – Haruka Ozaki, Ph.D. – Computational biolology & Bioinformatics
pplacerはメタゲノムデータ中にどのような種が多いかを可視化・比較するツールです．


http://kazumaxneo.hatenablog.com/entry/2018/07/20/212444
web上でマルチプルアライメントを実行し分子系統樹を出力する MAFFT online service - macでインフォマティクス

----------
## updates

### 2018

----------
## unclassified

https://www.ncbi.nlm.nih.gov/pubmed/28174903
Bioinformatics. 2017 Jun 15;33(12):1886-1888. doi: 10.1093/bioinformatics/btx063.
Phyx: phylogenetic tools for unix.

http://kazumaxneo.hatenablog.com/entry/2017/09/09/014350
コード領域のアミノ酸配列を考えてマルチプルアライメントを行うMUCSE - macでインフォマティクス

http://yukke.hateblo.jp/entry/2015/10/05/120924
ランダムな塩基配列をつくる - yukke::note

http://d.hatena.ne.jp/hoxo_m/20121031/p1
16S rRNA解析のクオリティフィルタリングについて - ほくそ笑む
Sliding Window フィルタ

https://git.scicore.unibas.ch/TBRU/Treemmer
Treemmer 
Python tool to reduce size and redundancy of phylogenetic datasets


----------
## HyPhy
https://www.youtube.com/watch?v=4gcQ6CCTRIY
Introduction to HyPhy: Hypothesis testing using Phylogenies - YouTube

https://github.com/haruosuz/mgsa/tree/master/hyphy


----------
## OrthoFinder
http://www.stevekellylab.com/software/orthofinder
https://github.com/davidemms/OrthoFinder
https://github.com/davidemms/OrthoFinder/blob/master/OrthoFinder-manual.pdf

![](https://raw.githubusercontent.com/davidemms/OrthoFinder/master/orthofinder/workflow.png)

2018 年 11 月 9 日　改訂
井上 潤
http://www.fish-evol.com/orthofinder_ji.html
Orthofinder (githab) はオーソログを推定するプログラムです．配列類似性 all-in-all 比較の結果を用いた MCL 解析によるグルーピングから，オーソログをオーソグループ (orthogroup) として推定します．

オーソロジーは遺伝子系統樹によって推定するもので，配列類似性は予想にすぎない，

https://www.hobochuritsu.com/entry/2018/10/24/204801
OrthoFinderでFastTreeを使おうとしたらエラーが出た - ほぼ中立ブログ
オーソログ推定プログラム「OrthoFinder」は、推定したオーソロググループ配列を使用してそのまま系統樹作成まで行うことができます。

http://kazumaxneo.hatenablog.com/entry/2017/08/01/201224
OrthoFinderでオルソロググループを探索する - macでインフォマティクス

2017/2/22
https://qiita.com/okuman/items/c7ef9588e990a670d3ee
OrthoFinderを用いたOrthologous解析 - Qiita
OrthoFinderでは、MCL (markov cluster algorithm)を用いてオーソログを推定します。
このOrthoGroupにはオーソログだけでなく、パラログも含まれてしまう

----------
## tree

21 Nov 2017
https://twitter.com/RokasLab/status/933007398398251009
RokasLab on Twitter: "Interested on how fast ML phylogenetic programs (RAxML/ExaML, PhyML, IQ-TREE, &FastTree) perform on state-of-the-art empirical phylogenomic… https://t.co/tRfWRSZawe"

http://togotv.dbcls.jp/20180403.html
MAFFT・RAxML・FigTreeを組み合わせて分子系統解析を行う 統合TV(togotv)｜生命科学系DB・ツール使い倒し系チャンネル

### FastTree

http://www.microbesonline.org/fasttree/
FastTree 2.1: Approximately-Maximum-Likelihood Trees for Large Alignments

2018-10-26
https://www.hobochuritsu.com/entry/2018/10/26/223658
FastTreeの使い方まとめ - ほぼ中立ブログ

RAxMLとFastTreeの比較に関するツイート
https://twitter.com/pathogenomenick/status/453823811805544448
https://www.ncbi.nlm.nih.gov/pubmed/22132132
PLoS One. 2011;6(11):e27731. doi: 10.1371/journal.pone.0027731. Epub 2011 Nov 21.
RAxML and FastTree: comparing two methods for large-scale maximum likelihood phylogeny estimation.
Liu K1, Linder CR, Warnow T.

### RAxML

https://sco.h-its.org/exelixis/web/software/raxml/index.html
RAxML - Randomized Axelerated Maximum Likelihood

https://sco.h-its.org/exelixis/web/software/raxml/hands_on.html
RAxML hands-on session

2017-05-25
https://qiita.com/MaedaTaro_Umiushi/items/3bc287672429ba1a511f
Phylogenomic解析をBiopython＋RaxML＋Conselでやってみる その2-AU検定 - Qiita

2017年3月5日
http://www.tezuru-mozuru.com/?p=9808
RAxMLによる最尤法系統樹推定 – チームてづるもづる

2016-12-02
http://www.geocities.jp/ancientfishtree/raxmlExample.html
RAxML・簡単な例題 - 井上潤

2016-10-12
http://www.geocities.jp/ancientfishtree/RAxML.html
RAxML - 井上 潤

https://www.fifthdimension.jp/documents/molphytextbook/
Life is fifthdimension.::Documents::分子系統学演習
https://www.fifthdimension.jp/documents/molphytextbook/molphytextbook.ja.pdf
2015年度版PDF(2015年10月20日更新)

https://sites.google.com/site/ouminishiswebsite/8-shi-yan-fang-fa-deta-jie-xi/raxmlde-xi-tong-jie-xi
系統解析: RAxML - Oumi Nishi's Website

----------
## timetree
http://www.timetree.org/

http://yagays.github.io/blog/2013/07/10/timetree/
TimeTreeで生物種間の分岐年代を調べる - Wolfeyes Bioinformatics beta

2017年1月6日
http://trhujgitudjf.blogspot.com/2017/01/imetree-timescale-of-life.html
土と生き物: TimeTree: the timescale of life

http://molbiol.hatenablog.com/entry/2016/02/27/203751
TimeTreeアプリは学術的なアプリである - 生物学研究者の言いたい放題ブログ

https://www.jstage.jst.go.jp/article/sjst/54/3/54_13037/_article/-char/ja/
オンラインツール“TimeTree: the timescale of life”を用いた生物多様性科学の授業開発とその評価
塩野 貴之, 真栄城 亮, 楠本 聞太郎, 久保田 康裕
2014 年 54 巻 3 号 p. 427-437
https://www.jstage.jst.go.jp/article/sjst/54/3/54_13037/_pdf


----------
## iTOL

https://besshomanabulumi.wixsite.com/manabuhome/research-tips
iTOL: 系統樹をかっこよくメイクアップできるツール。
ProtTest3: ML,Bayes系統樹を書くときの置換モデルを推定してくれるツール。

2017.8.3
https://besshomanabulumi.wixsite.com/manabuhome/itol
iTOLの使い方
系統樹のFigureをかっこよく仕上げられるツール。

2017.8.10
https://besshomanabulumi.wixsite.com/manabuhome/itol-1
ProtTest3の使い方
ProtTest 3は塩基・アミノ酸の置換モデルを推定してくれる無料ツールです。

http://itol.embl.de
iTOL: Interactive Tree Of Life

https://www.ncbi.nlm.nih.gov/pubmed/27095192
Nucleic Acids Res. 2016 Jul 8;44(W1):W242-5. doi: 10.1093/nar/gkw290. Epub 2016 Apr 19.
Interactive tree of life (iTOL) v3: an online tool for the display and annotation of phylogenetic and other trees.
Letunic I1, Bork P2.

----------
## MEGA

http://evolgen.biol.se.tmu.ac.jp/MEGA/
MEGA: Molecular Evolutionary Genetics Analysis software

MEGA3 チュートリアル（Actin gene coding region を例題として）
- 入力データの準備
- 配列データのアライメント
- 分子系統樹の作成

https://togotv.dbcls.jp/20171106.html
2017-11-06 MEGA7を使って配列のアラインメント・系統解析を行う

http://evolgen.biol.se.tmu.ac.jp/labo/tamura/161026.pdf
実習1: MEGA7のダウンロードとインストール

http://evolgen.biol.se.tmu.ac.jp/labo/tamura/141106.htm
実習１：　MEGA6のダウンロードとインストール

http://cse.naro.affrc.go.jp/minaka/cladist/KoichiroTamura_tutorial2014.pdf
実習1: MEGA6のダウンロードとインストール

----------
## Gblocks

http://sy41211.hatenablog.com/entry/2015/12/04/195438
配列保存領域の抽出プログラムGblocksの使い方 - バイオインフォマティクス初心者の日常

http://molevol.cmima.csic.es/castresana/Gblocks.html
http://molevol.cmima.csic.es/castresana/Gblocks/Gblocks_documentation.html

https://www.ncbi.nlm.nih.gov/pubmed/17654362
Syst Biol. 2007 Aug;56(4):564-77.
Improvement of phylogenies after removing divergent and ambiguously aligned blocks from protein sequence alignments.
Talavera G1, Castresana J.

https://www.ncbi.nlm.nih.gov/pubmed/10742046
Mol Biol Evol. 2000 Apr;17(4):540-52.
Selection of conserved blocks from multiple alignments for their use in phylogenetic analysis.
Castresana J1.

----------
## trimAl

http://trimal.cgenomics.org

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2712344/
trimAl: a tool for automated alignment trimming in large-scale phylogenetic analyses
In most scenarios (90%), trimAl outperformed Gblocks v0.91b with default parameters. 

http://www.geocities.jp/ancientfishtree/trimAl_ji.html
trimAl - 井上 潤

https://www.fifthdimension.jp/documents/molphytextbook/molphytextbook.ja.html
1.5.3 整列の信頼できない座位
ここではtrimAlを用いて整列の信頼できない座位をトリミングする手順を説明します。

https://www.fifthdimension.jp/wiki.cgi?page=%CA%AC%BB%D2%B0%E4%C5%C1%B3%D8%B4%D8%CF%A2
分子遺伝学関連 - Life is fifthdimension.
 Gblocks
　multiple sequence alignmentからalignmentの信頼性の低い座位を探し出して除去するためのソフト。
 trimAl
　Gblocksを発展させてパラメータ自動設定機能を充実させたようなもの。


----------




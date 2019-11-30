Last Update: 2019-11-17

----------

# evolve.tools
ツール

## Table of Contents
- [featuring](#featuring)
- [updates](#updates)
[2018](#2018)
- [unclassified](#unclassified)
- [OrthoFinder](#orthofinder)
- [alignment](#alignment)
  - [mafft](#mafft)
- [tree](#tree) 系統樹作成
  - [IQ-Tree](#iqtree)
  - [FastTree](#fasttree)
  - [RAxML](#raxml)
- [timetree](#timetree)
- [iTOL](#itol)
- [MEGA](#mega)
- [Gblocks](#gblocks)
- [trimAl](#trimal)
- [HyPhy](#hyphy)
- [Notung](#notung)

----------
## featuring

http://fish-evol.com/link.html
系統解析リンク集 - 井上 潤

http://www.tezuru-mozuru.com/?cat=200
系統解析 – チームてづるもづる

http://d.hatena.ne.jp/haruosuz/20080813
系統解析 - Haruo Suzuki / Bioinformatics

- 多重配列アライメントと系統樹 [Multiple Alignment and Phylogenetic trees](https://github.com/haruosuz/r4bioinfo/blob/master/R_Avril_Coghlan/README.md#multiple-alignment-and-phylogenetic-trees)
- https://github.com/haruosuz/DS4GD/blob/master/2018giga/CaseStudy.md

----------
## updates


### 2019


2019年09月25日に更新
https://qiita.com/MaedaTaro_Umiushi/items/d3e04cf4e2f6e0588406
ggtreeを使ってRで系統樹を扱う

https://twitter.com/art_poon/status/1188654334436872192
Art Poon on Twitter: "For my #BioInformatics class, I wrote a #d3js interactive #dataviz to teach my students the difference between an unrooted and rooted phylogeny. This displays a simplified version of the @sabeti_lab's Ebola virus phylogeny - root-to-tip regression is next! https://t.co/COTdboVyfb" / Twitter
12:10 PM · Oct 28, 2019


### 2018

2018年07月27日
https://qiita.com/MaedaTaro_Umiushi/items/7c8cee435347eeee1cf5
orthofinder + mafft + trimal + iq-treeでゲノム規模のデータから系統樹を作る - Qiita

2017年05月26日
https://qiita.com/okuman/items/3dd1cd1292940442fcd0
ETE Toolkitを使ってPythonで色々な形の系統樹を書く

https://www.ncbi.nlm.nih.gov/pubmed/28174903
Bioinformatics. 2017 Jun 15;33(12):1886-1888. doi: 10.1093/bioinformatics/btx063.
Phyx: phylogenetic tools for unix.

2015/08/31
http://www.kenkyuu2.net/cgi-biotech2012/biotechforum.cgi?mode=view;Code=4381
BioTechnicalフォーラム [16SrRNAによる系統解析]

August 6, 2013
http://yuifu.github.io/pplacer-tutorial/
pplacerの使い方 – Haruka Ozaki, Ph.D. – Computational biolology & Bioinformatics
pplacerはメタゲノムデータ中にどのような種が多いかを可視化・比較するツールです．

----------
## Count

http://www.iro.umontreal.ca/~csuros/gene_content/count.html
Count: analysis of gene content evolution

https://www.ncbi.nlm.nih.gov/pubmed/20551134
Bioinformatics. 2010 Aug 1;26(15):1910-2. doi: 10.1093/bioinformatics/btq315. Epub 2010 Jun 15.
Count: evolutionary analysis of phylogenetic profiles with parsimony and likelihood.
Csurös M1.

----------
## Notung

http://www.cs.cmu.edu/~durand/Notung/
Notung-2.9 is a gene tree-species tree reconciliation software package that supports duplication-loss (DL) and duplication-transfer-loss (DTL) event models with a parsimony-based optimization criterion.

https://www.ncbi.nlm.nih.gov/pubmed/27998934
Bioinformatics. 2017 Mar 1;33(5):640-649. doi: 10.1093/bioinformatics/btw686.
Xenolog classification.
Darby CA1, Stolzer M1, Ropp PJ1, Barker D2, Durand D1,3.
horizontal transfer

http://www.fish-evol.org/Notung_JI.html
Notung - 井上 潤
201７ 年 12 月 10 日　改訂
Notung は species tree (広く認められている系統樹) と gene tree (一つの種から複数のホモログを含む) を比較して，遺伝子重複と欠失が生じたノードを再節約推定するプログラムです．
得られた gene tree を species tree と照らし合わせて，遺伝子重複が生じた node を推定します．こちらにどのような解析が行われるか図で表されています．
http://goby.compbio.cs.cmu.edu/Notung/dupTimes.html

----------
## DupliPHY

www.bioinf.manchester.ac.uk/dupliphy

https://www.ncbi.nlm.nih.gov/pubmed/25294920
Bioinformatics. 2015 Feb 1;31(3):416-7. doi: 10.1093/bioinformatics/btu645. Epub 2014 Oct 7.
DupliPHY-Web: a web server for DupliPHY and DupliPHY-ML.
Ames RM1, Lovell SC1.

https://www.ncbi.nlm.nih.gov/pubmed/22039210
Bioinformatics. 2012 Jan 1;28(1):48-55. doi: 10.1093/bioinformatics/btr592. Epub 2011 Oct 28.
Determining the evolutionary history of gene families.
Ames RM1, Money D, Ghatge VP, Whelan S, Lovell SC.
https://academic.oup.com/bioinformatics/article/28/1/48/218268
- tree reconciliation techniques (Akerborg et al., 2009; Chen et al., 2000; Page, 1998; Tofigh et al., 2010). These methods infer gene trees for each gene family, and then reconcile these trees with a known species tree to infer gain and loss events.
- The probabilistic model implemented in COUNT (Csuros, 2010) only annotates ancestral species as containing 0, 1 or more members of a family, whereas the parsimony method produces indistinguishable results from DupliPHY (Supplementary Material). The method of (Iwasaki and Takagi, 2007) allows a maximum gene family size of three.
- COUNT (Csuros, 2010) provides a parsimony reconstruction of the ancestral size of gene families. We find that there is very little difference between DupliPHY and COUNT for simulations under any of the three models (Supplementary Fig. S2). 

----------
## HyPhy
https://www.youtube.com/watch?v=4gcQ6CCTRIY
Introduction to HyPhy: Hypothesis testing using Phylogenies - YouTube

https://github.com/haruosuz/mgsa/tree/master/hyphy

----------
## unclassified

http://yukke.hateblo.jp/entry/2015/10/05/120924
ランダムな塩基配列をつくる - yukke::note

https://git.scicore.unibas.ch/TBRU/Treemmer
Treemmer 
Python tool to reduce size and redundancy of phylogenetic datasets


----------
## alignment
アライメント

### mafft

https://mafft.cbrc.jp/alignment/software/

https://twitter.com/chasewnelson/status/1186164467622498305
Chase W. Nelson on Twitter: "@MinionLab @AprilWei001 The #MAFFT output for the same data was (1) faster and (2) makes actual sense. Thanks again! https://t.co/8bR2nJt1t1" / Twitter
3:17 PM · Oct 21, 20

2019/10/19
https://kimbio.info/mafft→raxml→figtreeで遺伝子の系統樹を作成する-ubuntu19-04
MAFFT→RAxML→FigTreeで遺伝子の系統樹を作成する - Ubuntu19.04 - Kim Biology & Informatics

http://kazumaxneo.hatenablog.com/entry/2017/10/18/000312
マルチプルアライメントを行うMAFFT - macでインフォマティクス

http://kazumaxneo.hatenablog.com/entry/2018/07/20/212444
web上でマルチプルアライメントを実行し分子系統樹を出力する MAFFT online service - macでインフォマティクス

http://kazumaxneo.hatenablog.com/entry/2017/09/09/014350
コード領域のアミノ酸配列を考えてマルチプルアライメントを行うMUCSE - macでインフォマティクス

----------
## OrthoFinder

https://github.com/davidemms/OrthoFinder

Published: 14 November 2019
https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1832-y
OrthoFinder: phylogenetic orthology inference for comparative genomics
David M. Emms & Steven Kelly

- http://www.stevekellylab.com/software/orthofinder
- https://github.com/davidemms/OrthoFinder
- https://github.com/davidemms/OrthoFinder/blob/master/OrthoFinder-manual.pdf

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

### iqtree
http://www.iqtree.org/
Efficient software for phylogenomic inference
Latest version 1.6.9 (December 20, 2018)

https://www.hobochuritsu.com/entry/2018/10/21/125017
IQ-Treeの使い方まとめ - ほぼ中立ブログ

2017年3月22日
http://www.tezuru-mozuru.com/?p=9927
iqtreeによる最尤法系統樹推定 – チームてづるもづる

### FastTree

http://www.microbesonline.org/fasttree/
FastTree 2.1: Approximately-Maximum-Likelihood Trees for Large Alignments

FastTree computes local support values with the Shimodaira-Hasegawa test
http://www.microbesonline.org/fasttree/#Support
If you want to use the traditional bootstrap instead, 

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
http://www.fish-evol.org/raxmlExample.html
RAxML・簡単な例題 - 井上潤

2016-10-12
http://www.fish-evol.org/RAxML.html
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
MEGA: Molecular Evolutionary Genetics Analysis software

https://www.megasoftware.net/

http://evolgen.biol.se.tmu.ac.jp/MEGA/
MEGAXがリリースされました。(6/1/2018)

MEGA3 チュートリアル（Actin gene coding region を例題として）
- 入力データの準備
- 配列データのアライメント
- 分子系統樹の作成

2018/01/20
https://ultrabem-branch3.com/informatics/bioinformatics/tree_make_mega_ml
系統樹の作り方: MEGA で最尤法を使う

https://togotv.dbcls.jp/20171106.html
2017-11-06 MEGA7を使って配列のアラインメント・系統解析を行う

http://evolgen.biol.se.tmu.ac.jp/labo/tamura/161026.pdf
実習1: MEGA7のダウンロードとインストール

http://evolgen.biol.se.tmu.ac.jp/labo/tamura/141106.htm
実習１：　MEGA6のダウンロードとインストール

http://cse.naro.affrc.go.jp/minaka/cladist/KoichiroTamura_tutorial2014.pdf
実習1: MEGA6のダウンロードとインストール

https://www.ncbi.nlm.nih.gov/pubmed/29722887
Mol Biol Evol. 2018 Jun 1;35(6):1547-1549. doi: 10.1093/molbev/msy096.
MEGA X: Molecular Evolutionary Genetics Analysis across Computing Platforms.
Kumar S1,2,3, Stecher G1, Li M1, Knyaz C1, Tamura K4,5.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5967553/


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




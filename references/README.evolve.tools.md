Last Update: 2020-05

----------

# evolve.tools
進化系統解析ツール

## Table of Contents
- [unclassified](#unclassified)
- [featuring](#featuring)
- [updates](#updates)
[2019](#2019)
[2018](#2018)
[2017](#2017)
- [ortholog](#ortholog)
  - [JustOrthologs](JustOrthologs)
  - [OrthoFinder](#orthofinder)
- [alignment](#alignment) アライメント、編集
  - [gap](#gap)
  - [mafft](#mafft)
  - [Gblocks](#gblocks)
  - [trimAl](#trimal)
- [tree](#tree) 系統樹
  - [IQ-Tree](#iqtree)
  - [FastTree](#fasttree)
  - [RAxML](#raxml)
  - [bcgTree](#bcgTree)
  - [phylophlan](#phylophlan)
  - [ETE Toolkit](#etetoolkit)
- [viewer](#viewer) 可視化ツール
Dendroscope3
Tree viewer
IcyTree
  - [figtree](#figtree)
  - [iTOL](#itol)
  - [SeaView](#seaview)
  - [annotree](#annotree)
- [gene loss](#gene-loss) 遺伝子ロス
  - [Notung](#notung)
  - [count](#count)
  - [DupliPHY](#dupliPHY)
- [](#)
- [HyPhy](#hyphy): Hypothesis testing using Phylogenies
- [MEGA](#mega)
- [timetree](#timetree)
- [treefinder](#treefinder)

----------
## unclassified

http://yukke.hateblo.jp/entry/2015/10/05/120924
ランダムな塩基配列をつくる - yukke::note

https://git.scicore.unibas.ch/TBRU/Treemmer
Treemmer 
Python tool to reduce size and redundancy of phylogenetic datasets

3:55 PM · Sep 17, 2019
https://twitter.com/level3defless/status/1173852867712565248
Koichi Higashi on Twitter: "すごく久々に系統解析やってるけど、ModelTest-NGがすごく使いやすいし速い。ProtTestの改良版。DNAに関してはGTR+I+Gにしとけばいいモデル選択いらない、みたいな話が最近あったけど、一応DNAにも対応してる。 https://t.co/bggA8Is0Kt" / Twitter

----------
## featuring

http://fish-evol.com/link.html
系統解析リンク集 - 井上 潤

https://sites.google.com/view/enter-the-fungi/phylogenetic-analysis
系統推定における結果はいつも仮説

http://www.tezuru-mozuru.com/?cat=200
系統解析 – チームてづるもづる

- 多重配列アライメントと系統樹 [Multiple Alignment and Phylogenetic trees](https://github.com/haruosuz/r4bioinfo/blob/master/R_Avril_Coghlan/README.md#multiple-alignment-and-phylogenetic-trees)
- https://github.com/haruosuz/DS4GD/blob/master/2018giga/CaseStudy.md

http://d.hatena.ne.jp/haruosuz/20080813
系統解析 - Haruo Suzuki / Bioinformatics

https://ja.wikipedia.org/wiki/非加重結合法
非加重結合法（Unweighted Pair Group Method with Arithmetic mean、UPGMAと略す)


----------
## treefinder

https://www.treefinder.de/

https://en.wikipedia.org/wiki/Treefinder

2009 年 12 月 17 日　改訂
http://www.fish-evol.org/Treefinder_JGI.html
井上 潤：Treefinder
Teefinder は最尤法による解析を高速に行うソフトウェアです．系統樹探索にも様々な機能が装備されています．

3:50 PM · Jul 17, 2020
https://twitter.com/iNut/status/1284017692706406401
Ⓝ on Twitter: "treefinder, もっとやばいページがあった… https://t.co/7ArmKVhvH6" / Twitter
これだけ沢山citeされる優れたソフトウェアを作って無償で公開しているのに、自分は全く儲からないし(おそらく)リスペクトもされなかったというのが背景にあるのかもしれない… もしそうだとしたらなんて悲しい話なんだ…
開発者のインタビューがあった
これによるとTreefinderを開発して多くの人が便利に使ってくれたにも関わらず誰もまともな給料で雇おうとせず結局無職になってしまったということである 「移民の研究者やエンジニアで研究所を一杯にしているが、俺1人で作ったソフトウェアの方がずっと優れているし使われている」と

12:25 PM · Jul 17, 2020
https://twitter.com/leeswijzer/status/1283965910722781185
MINAKA Nobuhiro on Twitter: "オープンアクセス誌に掲載したからソフトウェアともども “リトラクト” になったということですか．かつて南アフリカ共和国がアパルトヘイトを敷いていた頃， J. Felsenstein が PHYLIP を「南アでは使用不許可」にしていたことをふと思い出しました． https://t.co/Ml8eEtwmIb" / Twitter

11:31 AM · Jul 17, 2020·
https://twitter.com/lambtani____/status/1283952516112068608
らむ on Twitter: "TREEFINDER (2004) の掲載が取り下げられていた https://t.co/GXuTipzCz0" / Twitter
著者インタビューを読んでみると切ない。本人曰く、給料が毎月減らされていって、2004年からは2015年の時点で無職だったそうな。ライセンス変更のおもな理由は、アメリカとアカデミアのシステムへのプロテスト。
2015-10-07
https://www.homolog.us/blogs/distraction/2015/10/07/interview-with-gangolf-jobb-the-author-of-treefinder/
Interview with Gangolf Jobb, the Author of Treefinder


9:54 AM · Jul 17, 2020
https://twitter.com/fukunagaTsu/status/1283928034852999170
福永　津嵩 on Twitter: "6位の"TREEFINDER: a powerful graphical analysis environment for molecular phylogenetics. "とか捏造する要素どこにあるん・・？と思ったら、まさかの「ソフトウェアライセンスを変更して全ての研究者が無料で利用可能じゃなくなったのでjournal policyに反するから撤回」だった。" / Twitter
https://twitter.com/fukunagaTsu/status/1283931088054661120
なんかもう少し調べたらもっと政治的にヤバい問題だった(http://treefinder.de)。これを知らなかったのは恥。

10:09 AM · Jan 27, 2016
https://twitter.com/ka_ka_xyz/status/692152312605888513
Ka-Ka on Twitter: ""米国の帝国主義に反対だから、米国の科学者には、2015年2月1日からツリーファインダー（Treefinder）の使用を認めないと宣言" なんかこー、色々とロックだ（こなみかん） / “「思想」：ガンゴルフ・ジョブ（Gangol…” https://t.co/kr6Ha9lQtA" / Twitter
https://haklak.com/page_Gangolf_Jobb.html
ガンゴルフ・ジョブ（Gangolf Jobb） | 白楽の研究者倫理
特殊事件「思想」：ガンゴルフ・ジョブ（Gangolf Jobb）（ドイツ）


----------

## updates

### 2020

### 2019


2019年12月2日月曜日
https://evotools.blogspot.com/2019/12/beast2.html
系統解析備忘録: BEAST2による分岐年代推定①

https://www.ncbi.nlm.nih.gov/pubmed/31791235
BMC Evol Biol. 2019 Dec 2;19(1):219. doi: 10.1186/s12862-019-1541-x.
PhySpeTree: an automated pipeline for reconstructing phylogenetic species trees.
- Python
(https://github.com/yangfangs/physpetools)


2019年10月21日に更新
https://qiita.com/kaizen_nagoya/items/150646f72c55a36f8c39
遺伝子解析、遺伝子機能解析 - Qiita


2019/10/19
https://kimbio.info/mafft→raxml→figtreeで遺伝子の系統樹を作成する-ubuntu19-04
MAFFT→RAxML→FigTreeで遺伝子の系統樹を作成する - Ubuntu19.04 - Kim Biology & Informatics

2019年09月25日
https://qiita.com/MaedaTaro_Umiushi/items/d3e04cf4e2f6e0588406
ggtreeを使ってRで系統樹を扱う

https://twitter.com/art_poon/status/1188654334436872192
Art Poon on Twitter: "For my #BioInformatics class, I wrote a #d3js interactive #dataviz to teach my students the difference between an unrooted and rooted phylogeny. This displays a simplified version of the @sabeti_lab's Ebola virus phylogeny - root-to-tip regression is next! https://t.co/COTdboVyfb" / Twitter
12:10 PM · Oct 28, 2019


### 2018

https://doi.org/10.7875/togotv.2018.093
2018-04-03 MAFFT・RAxML・FigTreeを組み合わせて分子系統解析を行う

### 2017

2017年05月26日
https://qiita.com/okuman/items/3dd1cd1292940442fcd0
ETE Toolkitを使ってPythonで色々な形の系統樹を書く

https://www.ncbi.nlm.nih.gov/pubmed/28174903
Bioinformatics. 2017 Jun 15;33(12):1886-1888. doi: 10.1093/bioinformatics/btx063.
Phyx: phylogenetic tools for unix.

### 2015

2015/08/31
http://www.kenkyuu2.net/cgi-biotech2012/biotechforum.cgi?mode=viewer;Code=4381
BioTechnicalフォーラム [16SrRNAによる系統解析]

August 6, 2013
http://yuifu.github.io/pplacer-tutorial/
pplacerの使い方 – Haruka Ozaki, Ph.D. – Computational biolology & Bioinformatics
pplacerはメタゲノムデータ中にどのような種が多いかを可視化・比較するツールです．

2008年11月 4日，11日
http://lbm.ab.a.u-tokyo.ac.jp/~omori/phylogeny/txt/phylogeny_zikken.html
2008年度生物測定学応用実験
分子系統樹の作成
東京大学大学院農学生命科学研究科　大森宏

----------
## ortholog

----------
### SwiftOrtho

https://pubmed.ncbi.nlm.nih.gov/31648300/
Gigascience
. 2019 Oct 1;8(10):giz118. doi: 10.1093/gigascience/giz118.
SwiftOrtho: A fast, memory-efficient, multiple genome orthology classifier
Xiao Hu 1, Iddo Friedberg 1
https://academic.oup.com/gigascience/article/8/10/giz118/5606727
While the proper inference of homology type involves tracing gene history using phylogenetic trees [2], several proxy methods have been developed over the years. The most common method to infer orthologs by proxy is reciprocal best hits (RBH) [3, 4]. Briefly, RBH states the following: when 2 proteins that are encoded by 2 genes, each in a different genome, find each other as the best-scoring match among all homologs, they are considered to be orthologs [3, 4].

http://kazumaxneo.hatenablog.com/entry/2019/04/13/073000
オルソログとパラログを小メモリ使用量で高速探索する SwiftOrtho - macでインフォマティクス
オルソログを推論する最も一般的な方法は、Reciprocal Best Hit （相互ベストヒット）またはRBHである[ref.2、3]。簡単に言うと、RBHは次のように述べられている。異なる２ゲノムの２つの遺伝子によってコードされている2つのタンパク質が互いに最良のスコアリングマッチとして見つかると、それらはオルソログと見なされる[ref.2、3]。

----------
### JustOrthologs
https://github.com/ridgelab/JustOrthologs/

https://www.ncbi.nlm.nih.gov/pubmed/30084941
Bioinformatics. 2019 Feb 15;35(4):546-552. doi: 10.1093/bioinformatics/bty669.
JustOrthologs: a fast, accurate and user-friendly ortholog identification algorithm.
Miller JB1, Pickett BD1, Ridge PG1.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6378933/

http://kazumaxneo.hatenablog.com/entry/2019/03/29/073000
高速なオルソログ推論ツール JustOrthologs - macでインフォマティクス

----------
### ORTHOSCOPE

動画
2019-12-07
https://doi.org/10.7875/togotv.2019.194
分岐年代のベイズ推定 @ 分子系統樹推定法:理論と応用 ワークショップ
0:00 - 15:00 / 1:04:11
オーソグループ

2019 年 1 月 10 日　改訂
http://www.fish-evol.org/orthoscope_ji.html
ORTHOSCOPE は遺伝子系統樹を推定して，オーソログを判定するウェブツールです．以下の解析が可能です：

1. 未知 (あるいは既知) の遺伝子配列の機能を推定する．
2. オーソログの配列を，他の種から得る．
3. オーソログが他の種に存在する確かめる．

解析には，脊椎動物を中心とした左右相称動物 350 種以上のゲノムデータ (アミノ酸配列と DNA 配列) をデータベースとして自由に選べます．

----------
### OrthoFinder

http://www.stevekellylab.com/software/orthofinder

https://github.com/davidemms/OrthoFinder

https://davidemms.github.io/
OrthoFinder | OrthoFinder Tutorials

https://www.ncbi.nlm.nih.gov/pubmed/31727128
Genome Biol. 2019 Nov 14;20(1):238. doi: 10.1186/s13059-019-1832-y.
OrthoFinder: phylogenetic orthology inference for comparative genomics.
Emms DM1, Kelly S2.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6857279/
Fig. 1
Right-hand side: Reciprocal best hits (RBH) based on gene similarity scores that are monotonic with branch length and the orthology relationships inferred from these scores using standard heuristics (orthologs inferred using RBHs and co-orthology identified from within species hits better than closest RBH [8, 16]). 

43. Emms D, Kelly S: Supplemental dataset for: OrthoFinder2: fast and accurate phylogenomic orthology analysis from gene sequences. https://doi.org/10.5281/zenodo.1481147 2019.

動画
Aug 3, 2020
https://www.youtube.com/watch?v=L6eXJAE5J7g
VirtualPhyloComp2020 day 2 David Emms - YouTube
https://sites.google.com/view/phylocompgenomics2020/schedule
OrthoFinder: Building a Fully Phylogenetic Orthology Analysis

3:51 AM · Jul 16, 2020
https://twitter.com/David__Emms/status/1283474268701982720
David Emms on Twitter: "There's a new version of OrthoFinder out! It uses the gene trees it already infers to infer a set of orthogroups at each phylogenetic level within the species tree. This increases accuracy substantially &amp; also lets you add outgroups to your analysis: https://t.co/ogbupnnbxx https://t.co/Th3uZOCHqW" / Twitter

Mar 9
https://github.com/davidemms/OrthoFinder/issues/355
No support value in SpeciesTree_rooted.txt · Issue #355 · davidemms/OrthoFinder


2018 年 11 月 9 日　改訂
井上 潤
http://www.fish-evol.org/orthofinder_ji.html
Orthofinder (githab) はオーソログを推定するプログラムです．配列類似性 all-in-all 比較の結果を用いた MCL 解析によるグルーピングから，オーソログをオーソグループ (orthogroup) として推定します．
オーソロジーは遺伝子系統樹によって推定するもので，配列類似性は予想にすぎない，

https://www.hobochuritsu.com/entry/2019/04/20/223105
全自動でシングルコピー遺伝子の連結系統樹推定(OrthoFinder, MAFFT, trimAL, IQ-TREE) - ほぼ中立ブログ

https://www.hobochuritsu.com/entry/2018/10/24/204801
OrthoFinderでFastTreeを使おうとしたらエラーが出た - ほぼ中立ブログ
オーソログ推定プログラム「OrthoFinder」は、推定したオーソロググループ配列を使用してそのまま系統樹作成まで行うことができます。

2019/03/06
https://qiita.com/MaedaTaro_Umiushi/items/d4004d3fb219a4f991e8
orthofinder + prequal+ mafft + iq-treeでゲノム規模のデータから系統樹を作る - Qiita

2018年07月27日
https://qiita.com/MaedaTaro_Umiushi/items/7c8cee435347eeee1cf5
orthofinder + mafft + trimal + iq-treeでゲノム規模のデータから系統樹を作る - Qiita

http://kazumaxneo.hatenablog.com/entry/2017/08/01/201224
OrthoFinderでオルソロググループを探索する - macでインフォマティクス

2017/2/22
https://qiita.com/okuman/items/c7ef9588e990a670d3ee
OrthoFinderを用いたOrthologous解析 - Qiita
OrthoFinderでは、MCL (markov cluster algorithm)を用いてオーソログを推定します。
このOrthoGroupにはオーソログだけでなく、パラログも含まれてしまう

2016年03月12日
https://qiita.com/NariseT/items/e2c90d0235316f8878d8
OrthoFinder の使い方 - Qiita

----------
## alignment
アライメント

http://kazumaxneo.hatenablog.com/archive/category/multiple%20sequence%20alignment%20%28MSA%29

http://kazumaxneo.hatenablog.com/entry/2017/09/09/014350
コード領域のアミノ酸配列を考えてマルチプルアライメントを行うMUCSE - macでインフォマティクス

https://www.fifthdimension.jp/wiki.cgi?page=%A5%BF%A5%F3%A5%D1%A5%AF%A5%B3%A1%BC%A5%C9%CE%CE%B0%E8%B1%F6%B4%F0%C7%DB%CE%F3%A4%CE%A5%DE%A5%EB%A5%C1%A5%D7%A5%EB%A5%A2%A5%E9%A5%A4%A5%E1%A5%F3%A5%C8
タンパクコード領域塩基配列のマルチプルアライメント - Life is fifthdimension.
最終更新時間：2007年03月17日 05時57分52秒

### mafft

https://mafft.cbrc.jp/alignment/software/
MAFFT - a multiple sequence alignment program

Fasta format.  example1 (LSU rRNA), example2 (protein)

Manual (v6.240)
https://mafft.cbrc.jp/alignment/software/manual/manual.html

Tips (not yet included in the manual) for large alignment, ncRNA alignment, profile alignment, etc.
https://mafft.cbrc.jp/alignment/software/tips0.html
How to get a guide tree or a rough clustering
How to give a user-defined guide tree

https://mafft.cbrc.jp/alignment/software/anysymbol.html
Ambiguous nucleotides (r, y, w, s, k, m, d, v, h, b; IUPAC-IUB codes) can be used and are scored as:
```
score(r,a) = ( score(a,a) + score(g,a) ) / 2
```

https://github.com/DomBennett/om..mafft
Run mafft through outsider in R
```
#> There are 10 ambiguous characters.
#>     1 / 13
#> done.
```

3:17 PM · Oct 21, 2019
https://twitter.com/chasewnelson/status/1186164467622498305
Chase W. Nelson on Twitter: "@MinionLab @AprilWei001 The #MAFFT output for the same data was (1) faster and (2) makes actual sense. Thanks again! https://t.co/8bR2nJt1t1" / Twitter

12:36 PM · Sep 28, 2019
https://twitter.com/sighex/status/1177789066097487872
工樂樹洋
"MAFFT開発秘話。私が4回生で宮田研に加わった時、まず手動で多重アラインメントする訓練から始まりました。研究室内部で使われていたそのエディタに、後にMAFFTの主軸となるアルゴリズムが間もなく入りました。Xcedと呼ばれた、メンバーしか知らないエディタです。

http://kazumaxneo.hatenablog.com/entry/2017/10/18/000312
マルチプルアライメントを行うMAFFT - macでインフォマティクス

http://kazumaxneo.hatenablog.com/entry/2018/07/20/212444
web上でマルチプルアライメントを実行し分子系統樹を出力する MAFFT online service - macでインフォマティクス

----------
### gap

https://doi.org/10.7875/togotv.2019.193
2019-12-06 MEGA X を用いた分子系統解析 @ 分子系統樹推定法:理論と応用 ワークショップ
41:40 / 52:32
Gapが入るところは捨てる。
Gapが入らないところだけ使う。

http://www.tezuru-mozuru.com/?tag=mega
- Gaps/Missing Data Treatment：ギャップの扱いの設定です．Complete deletionとすると，一つでもギャップがあるサイト（列）を解析からのぞけます．
- Gaps/Missing Data Treatment：ギャップやミッシングデータの取り扱いが選べます．Complete deletionで，ギャップが一つでもある列は解析殻除きます．Partial Deletionで，比較する配列ごとにギャップの扱いを決めます．Use all siteでギャップもミッシングデータも全て扱います．

https://github.com/haruosuz/r4bioinfo/blob/master/R_Avril_Coghlan/README.md#discarding-very-poorly-conserved-regions-from-an-alignment
アラインメントから保存度の低い領域を破棄する
Trimming a multiple sequence alignment by discarding columns with too many gaps.
多重配列アライメントからギャップの多い列を破棄する

----------
### Gblocks

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
### trimAl

http://trimal.cgenomics.org

https://pubmed.ncbi.nlm.nih.gov/19505945/
Bioinformatics
. 2009 Aug 1;25(15):1972-3. doi: 10.1093/bioinformatics/btp348. Epub 2009 Jun 8.
trimAl: a tool for automated alignment trimming in large-scale phylogenetic analyses
Salvador Capella-Gutiérrez 1, José M Silla-Martínez, Toni Gabaldón
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2712344/
In most scenarios (90%), trimAl outperformed Gblocks v0.91b with default parameters. 

http://www.fish-evol.org/trimAl_ji.html
trimAl - JI
2016 年 3 月 31日　改訂
井上 潤

https://www.fifthdimension.jp/documents/molphytextbook/molphytextbook.ja.html
1.5.3 整列の信頼できない座位
偽遺伝子や遺伝子間領域、イントロン、rRNA/tRNAのloop領域などの欠失や挿入の多い配列では、整列の信頼性が低くなってしまいます。誤って整列された座位は、系統樹推定の際のノイズとなってしまうため、除去した方がよいと言われています(Talavera and Castresana, 2007)。これまでのところ、そのような処理が研究者の経験と勘でなされることが多かったのですが、近年になって自動的に行ってくれるソフトウェアが登場してきました。それがGblocks (Castresana, 2000)・trimAl (Capella-Gutiérrez et al., 2009)・Aliscore (Misof and Misof, 2009)・BMGE (Criscuolo and Gribaldo, 2010)です。ここではtrimAlを用いて整列の信頼できない座位をトリミングする手順を説明します。

https://www.fifthdimension.jp/wiki.cgi?page=%CA%AC%BB%D2%B0%E4%C5%C1%B3%D8%B4%D8%CF%A2
分子遺伝学関連 - Life is fifthdimension.
 Gblocks
　multiple sequence alignmentからalignmentの信頼性の低い座位を探し出して除去するためのソフト。
 trimAl
　Gblocksを発展させてパラメータ自動設定機能を充実させたようなもの。


----------
## tree

21 Nov 2017
https://twitter.com/RokasLab/status/933007398398251009
RokasLab on Twitter: "Interested on how fast ML phylogenetic programs (RAxML/ExaML, PhyML, IQ-TREE, &FastTree) perform on state-of-the-art empirical phylogenomic… https://t.co/tRfWRSZawe"
https://www.ncbi.nlm.nih.gov/pubmed/29177474
Mol Biol Evol. 2018 Feb 1;35(2):486-503. doi: 10.1093/molbev/msx302.
Evaluating Fast Maximum Likelihood-Based Phylogenetic Programs Using Empirical Phylogenomic Data Sets.
Zhou X1,2, Shen XX3, Hittinger CT4, Rokas A3.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5850867/

### ezTree
https://github.com/yuwwu/ezTree

https://www.ncbi.nlm.nih.gov/pubmed/29363425
BMC Genomics. 2018 Jan 19;19(Suppl 1):921. doi: 10.1186/s12864-017-4327-9.
ezTree: an automated pipeline for identifying phylogenetic marker genes and inferring evolutionary relationships among uncultivated prokaryotic draft genomes.
Wu YW1.

http://kazumaxneo.hatenablog.com/entry/2018/09/12/221645
phylogenetic marker genesを検出し、marker genes全てを使って系統比較する自動化されたパイプライン ezTree - macでインフォマティクス

### bcgTree

https://www.ncbi.nlm.nih.gov/pubmed/27603265
Genome. 2016 Oct;59(10):783-791. Epub 2016 May 11.
bcgTree: automatized phylogenetic tree building from bacterial core genomes.
Ankenbrand MJ1,1, Keller A1,1.
http://www.nrcresearchpress.com/doi/full/10.1139/gen-2015-0175?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%3dpubmed
The pipeline automatically extracts 107 essential single-copy core genes, found in a majority of bacteria, using hidden Markov models and performs a partitioned maximum-likelihood analysis. 

https://github.com/molbiodiv/bcgTree
Automatically calculate phylogenetic trees from bacterial core genes

See this file for instructions on how to reproduce results from our article.
https://github.com/molbiodiv/bcgTree/blob/master/reproduce_results.org

### PhyloPhlAn

https://huttenhower.sph.harvard.edu/phylophlan

https://www.ncbi.nlm.nih.gov/pubmed/23942190
Nat Commun. 2013;4:2304. doi: 10.1038/ncomms3304.
PhyloPhlAn is a new method for improved phylogenetic and taxonomic placement of microbes.
Segata N1, Börnigen D, Morgan XC, Huttenhower C.

https://github.com/alvaralmstedt/Tutorials/wiki/Creating-bacterial-phylogenetic-trees-with-PhyloPhlAn
Creating bacterial phylogenetic trees with PhyloPhlAn
alvaralmstedt edited this page on Aug 13, 2015

https://jpn.bioconus.com/phylophlan-is-new-method-795397
フィロフランは、微生物の系統発生学的および分類学的配置を改善するための新しい方法です。 自然通信 - コミュニケーション - 2019

http://kazumaxneo.hatenablog.com/entry/2018/09/12/221645
phylogenetic marker genesを検出し、marker genes全てを使って系統樹を作成する自動化パイプライン ezTree - macでインフォマティクス
PhyloPhlAn (Segata et al,. 2014) も簡単に紹介しています。

http://kazumaxneo.hatenablog.com/entry/2017/05/22/164017
メタゲノム解析ツール - macでインフォマティクス
使ってみて便利だったツールを紹介する。
PhyloPhlAn Segata et al. (2014)
ランにはFasttreeが必要。

### etetoolkit

http://etetoolkit.org/

http://etetoolkit.org/download/

http://etetoolkit.org/cookbook/
ETE Cookbook

2019年12月11日に更新
バイオインフォマティクス Advent Calendar 2019 11日目
https://qiita.com/aical/items/2231198d3d75e72bee39
誰にも教えたくない超カンタン分子系統樹作成術 - Qiita
ETE Toolkitを使った超簡便な分子系統樹作成法を紹介します。

https://www.hobochuritsu.com/entry/2018/11/08/223813
ETE Toolkitでノードに通し番号を付ける - ほぼ中立ブログ

2017年05月26日に更新
https://qiita.com/okuman/items/3dd1cd1292940442fcd0
ETE Toolkitを使ってPythonで色々な形の系統樹を書く - Qiita

### iqtree
http://www.iqtree.org/
IQ-TREE: Efficient phylogenomic software by maximum likelihood

http://www.iqtree.org/doc/Quickstart

9:33 PM · Nov 20, 2020
https://twitter.com/kfuku0502/status/1329764837681926145
Kenji Fukushima on Twitter: "iqtreeのsemi-empirical codon modelって、複数ヌクレオチド置換を許容した経験モデルに単一置換を仮定したメカニスティックモデルをかけたりしたら複数置換のマスが全部ゼロになってすっかすかのモデルにならない？それともomegaとかkappaで経験モデルを再調整するってこと？" / Twitter
手元のデータで試してみたらAIC/BICと尤度はsemi-empirical modelで改善するな。ということは後者かな？でも経験モデルってそもそもomegaやkappaが反映された上であのマトリックスになっているはずだから、それをどう再調整するんだろう。
この論文か。
https://academic.oup.com/mbe/article/29/1/271/1749642
違うっぽいな。iqtreeではこの論文の前半で説明されているピュアな経験モデルがECMK07で、同一論文の後半でomegaやkappaを入れているのをsemi-empirical modelの記法でECMK07_GYとして表現しているのか？
https://academic.oup.com/mbe/article/24/7/1464/986344
式６に書いてあった。単純にomegaとkappa（とコドン平衡頻度）を経験モデルのexchangeabilityに乗算してるっぽいな。上の疑問は残るけど、作法としてはそれでいいらしい。
経験モデルのomegaはメカニスティックモデルのそれとは単純比較できないと説明してあるな。
それを反映してかiqtreeのlogファイルにはomegaではなくomega_Eとして出力されている。

http://kazumaxneo.hatenablog.com/entry/2020/06/07/235834
IQ-TREE をwebで使える W-IQ-TREE - macでインフォマティクス
既にIQ-TREE2も発表（pubmed）されており、condaを使って導入できるバージョンも２になっていますが、2020年6月現在、web版はstable versionの1.6です。注意して下さい。

https://pubmed.ncbi.nlm.nih.gov/32011700/
Mol Biol Evol
. 2020 May 1;37(5):1530-1534. doi: 10.1093/molbev/msaa015.
IQ-TREE 2: New Models and Efficient Methods for Phylogenetic Inference in the Genomic Era
Bui Quang Minh 1 2, Heiko A Schmidt 3, Olga Chernomor 3, Dominik Schrempf 3 4, Michael D Woodhams 5, Arndt von Haeseler 3 6, Robert Lanfear 2

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

2020年01月09日に更新
https://qiita.com/YF_bio/items/40344f77e13f5da0ad07
RAxML-NGの使い方 - Qiita

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

## viewer

http://dendroscope.org/
Dendroscope3
An interactive viewer for rooted phylogenetic trees and networks

http://etetoolkit.org/treeview/
Tree viewer - Online visualization of phylogenetic trees (newick) and alignments.

http://kazumaxneo.hatenablog.com/entry/2018/10/09/111845
webで動作する高速で軽量な分子系統樹可視化ツール IcyTree - macでインフォマティクス
PhyML（Guindon and Gascuel、2003）やBEAST（Bouckaert et al、2014）のような他のパッケージは、図形出力を生成せず、代わりにFigTree（http://tree.bio.ed.ac.jp  link）やDendroscope（Huson and Scornavacca、2012 link）などの特殊な系統発生可視化ツールに依存している。

----------
### FigTree
http://tree.bio.ed.ac.uk/software/figtree/

http://www.fish-evol.org/FigTree.html
FigTree
2018 年 5 月 9 日　改訂
井上 潤
FigTree は newick 形式で作成された系統樹を graphical に表示するプログラムです．

https://sites.google.com/view/enter-the-fungi/phylogenetic-analysis/figtree-の使い方
FigTree の使い方

----------
### iTOL


5:40 AM · Jul 16, 2020
https://twitter.com/kmoooooog/status/1283501696417554432
itol有料化か。全然払ってもいい。
https://itol.embl.de/pricing.cgi

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
### SeaView

https://www.ncbi.nlm.nih.gov/pubmed/19854763
Mol Biol Evol. 2010 Feb;27(2):221-4. doi: 10.1093/molbev/msp259. Epub 2009 Oct 23.
SeaView version 4: A multiplatform graphical user interface for sequence alignment and phylogenetic tree building.
Gouy M, Guindon S, Gascuel O.

https://www.mybiosoftware.com/seaview-4-2-12-sequence-alignment-phylogenetic-tree-building.html
SeaView 4.7 - Sequence Alignment and Phylogenetic Tree Building

Dec 9, 2014
https://www.youtube.com/watch?v=-XfF8sJaZ-c
Exercise 3 Seaview to visually align sequences - YouTube


http://www2.tba.t-com.ne.jp/nakada/takashi/phylogeny/seaview2.html
SeaView 使用法
SeaView を用いたアラインメント編集
作成：仲田崇志
更新：2008年03月10日

----------

### annotree

https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkz246/5432638
AnnoTree: visualization and exploration of a functionally annotated microbial tree of life | Nucleic Acids Research | Oxford Academic

https://twitter.com/strnr/status/1117782170645483520
AnnoTree: visualization and exploration of a functionally annotated microbial tree of life
Paper https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkz246/5432638 …
App http://annotree.uwaterloo.ca/ 
Code https://bitbucket.org/account/user/doxeylabcrew/projects/AN …
Docs https://annotree-docs.readthedocs.io/en/latest/ 
Data http://gtdb.ecogenomic.org/downloads 
9:30 AM - 15 Apr 2019
![](https://pbs.twimg.com/media/D4Mo9PSXoAEYnZ1.jpg)

----------
## gene loss
### Notung

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
### DupliPHY

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
### Count

http://www.iro.umontreal.ca/~csuros/gene_content/count.html
Count: analysis of gene content evolution

https://www.ncbi.nlm.nih.gov/pubmed/20551134
Bioinformatics. 2010 Aug 1;26(15):1910-2. doi: 10.1093/bioinformatics/btq315. Epub 2010 Jun 15.
Count: evolutionary analysis of phylogenetic profiles with parsimony and likelihood.
Csurös M1.

----------

----------
## HyPhy

https://github.com/haruosuz/mgsa/tree/master/hyphy

Jun 16, 2020
https://www.youtube.com/watch?v=fgNrPbOTpxE
Download, install, and run HYPHY in under 10 Minutes! A quick intro to our software - YouTube

Oct 4, 2013
https://www.youtube.com/watch?v=4gcQ6CCTRIY
Introduction to HyPhy: Hypothesis testing using Phylogenies - YouTube

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

動画
https://twitter.com/hashtag/ws222?f=live
https://doi.org/10.7875/togotv.2019.193
2019-12-06 MEGA X を用いた分子系統解析 @ 分子系統樹推定法:理論と応用 ワークショップ

2018/01/20
https://ultrabem-branch3.com/informatics/bioinformatics/tree_make_mega_ml
系統樹の作り方: MEGA で最尤法を使う

動画
https://doi.org/10.7875/togotv.2017.106
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
## timetree
http://www.timetree.org/

https://twitter.com/copypasteusa/status/621805347880108032
Bacteria Versus Archaea. 4290.0 Million Years Ago. Molecular Time Estimates. http://timetree.org/search/pairwise/2/2157? #SPARQLthon
 · Jul 16, 2015
ArchaeaとBacteriaの分岐年代が42億年前となっていてウケる。

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












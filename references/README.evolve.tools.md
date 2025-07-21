
Last Update: 2020-07

----------

# evolve.tools
進化系統解析ツール

## Table of Contents
- [unclassified](#unclassified)
- [updates](#updates)
[2023](#2023)

[2019](#2019)
[2018](#2018)
[2017](#2017)
- [ortholog](#ortholog)
  - [JustOrthologs](JustOrthologs)
  - [OrthoFinder](#orthofinder)
- [alignment](#alignment) アライメント、編集
  - [clustal-omega](#clustal-omega)
  - [macse](#macse)
  - [mafft](#mafft)
  - [gap](#gap)
  - [Gblocks](#gblocks)
  - [trimAl](#trimal)
- [tree](#tree) 系統樹
  - [root_digger](#root_digger)
  - [IQ-Tree](#iqtree)
  - [FastTree](#fasttree)
  - [RAxML](#raxml)
  - [phyml](#phyml)
  - [bcgTree](#bcgTree)
  - [phylophlan](#phylophlan)
  - [etetoolkit](#etetoolkit)
- [viewer](#viewer) 可視化ツール
Dendroscope3
Tree viewer
IcyTree
  - [figtree](#figtree)
  - [iTOL](#itol)
  - [SeaView](#seaview)
- [gene loss](#gene-loss) 遺伝子ロス
  - [Notung](#notung)
  - [count](#count)
  - [DupliPHY](#dupliPHY)
- [](#)
- [MEGA](#mega)
- [physpetools](#physpetools)
- [HyPhy](#hyphy): Hypothesis testing using Phylogenies
- [TreeBASE](#treebase)
- [timetree](#timetree)
- [jlsteenwyk](#jlsteenwyk)

----------

----------
## jlsteenwyk

https://x.com/jlsteenwyk

https://jlsteenwyk.com/tutorials/phylogenomics_made_easy.html
Five-step phylogenomics, from proteomes to species tree

----------
### ClipKIT

https://github.com/JLSteenwyk/ClipKIT
https://jlsteenwyk.com/ClipKIT/

2020-12-02
https://pubmed.ncbi.nlm.nih.gov/33264284/
PLoS Biol
. 2020 Dec 2;18(12):e3001007. doi: 10.1371/journal.pbio.3001007. eCollection 2020 Dec.
ClipKIT: A multiple sequence alignment trimming software for accurate phylogenomic inference
Jacob L Steenwyk 1, Thomas J Buida 3rd 2, Yuanning Li 1, Xing-Xing Shen 3, Antonis Rokas 1
https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001007
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7735675/

https://jlsteenwyk.com/ClipKIT/advanced/index.html#codon
Trims codon-based alignments. If one position in a codon should be trimmed, the whole codon will be trimmed. To conduct codon-based trimming, use the -co/\-\-codon argument.

----------
### BioKIT

https://github.com/JLSteenwyk/BioKIT
online documentation.
https://jlsteenwyk.com/BioKIT/
Quick Start — biokit documentation

2022-07-04
https://pubmed.ncbi.nlm.nih.gov/35536198/
Genetics
. 2022 Jul 4;221(3):iyac079. doi: 10.1093/genetics/iyac079.
BioKIT: a versatile toolkit for processing and analyzing diverse types of sequence data
Jacob L Steenwyk 1 2, Thomas J Buida 3, Carla Gonçalves 1 2 4 5, Dayna C Goltz 6, Grace Morales 7, Matthew E Mead 1 2, Abigail L LaBella 1 2, Christina M Chavez 1 2, Jonathan E Schmitz 7, Maria Hadjifrangiskou 2 7, Yuanning Li 1, Antonis Rokas 1 2
https://academic.oup.com/genetics/article-abstract/221/3/iyac079/6583183

----------
### PhyKIT

https://github.com/JLSteenwyk/PhyKIT
online documentation.
https://jlsteenwyk.com/PhyKIT/
https://jlsteenwyk.com/PhyKIT/tutorials/index.html

https://www.preprints.org/manuscript/202404.1514/v1
PhyKIT: A Multitool for Phylogenomics

2021-08-25
https://pubmed.ncbi.nlm.nih.gov/33560364/
Bioinformatics
. 2021 Aug 25;37(16):2325-2331. doi: 10.1093/bioinformatics/btab096.
PhyKIT: a broadly applicable UNIX shell toolkit for processing and analyzing phylogenomic data
Jacob L Steenwyk 1, Thomas J Buida 2, Abigail L Labella 1, Yuanning Li 1, Xing-Xing Shen 3, Antonis Rokas 1
https://academic.oup.com/bioinformatics/article/37/16/2325/6131675
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8388027/

----------
## phyx

https://github.com/FePhyFoFum/phyx

https://github.com/FePhyFoFum/phyx/releases
Oct 22, 2024

2017-06-15
https://pubmed.ncbi.nlm.nih.gov/28174903/
Bioinformatics
. 2017 Jun 15;33(12):1886-1888. doi: 10.1093/bioinformatics/btx063.
Phyx: phylogenetic tools for unix
Joseph W Brown 1, Joseph F Walker 1, Stephen A Smith 1
https://academic.oup.com/bioinformatics/article/33/12/1886/2975328?login=false
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5870855/

----------
## newick_utils

https://anaconda.org/bioconda/newick_utils
The Newick Utilities are a suite of Unix shell tools for processing phylogenetic trees. We distribute the package under the BSD License. Functions include re-rooting, extracting subtrees, trimming, pruning, condensing, drawing (ASCII graphics or SVG).

9 years ago
https://github.com/tjunier/newick_utils

https://gensoft.pasteur.fr/docs/newick-utils/1.6/nwutils_tutorial.pdf
Version 1.6.0 – October 27, 2011

2010-07-01
https://pubmed.ncbi.nlm.nih.gov/20472542/
Bioinformatics
. 2010 Jul 1;26(13):1669-70. doi: 10.1093/bioinformatics/btq243. Epub 2010 May 13.
The Newick utilities: high-throughput phylogenetic tree processing in the UNIX shell
Thomas Junier 1, Evgeny M Zdobnov
https://academic.oup.com/bioinformatics/article/26/13/1669/200713
https://pmc.ncbi.nlm.nih.gov/articles/PMC2887050/


----------
## HyPhy

New
https://github.com/haruosuz/evolve/tree/master/tools/hyphy

Old
https://github.com/haruosuz/mgsa/tree/master/hyphy

----------
### TreeBASE
https://treebase.org/
TreeBASE is a repository of phylogenetic information, specifically user-submitted phylogenetic trees and the data used to generate them. TreeBASE accepts all kinds of phylogenetic data (e.g., trees of species, trees of populations, trees of genes) representing all biotic taxa.

https://treebase.org/treebase-web/urlAPI.html
Programmatic Data Access
In addition to the web interface, TreeBASE can be accessed programmatically through a stateless web service interface and URL architecture. This interface can deliver data in several different formats, including NEWICK, NEXUS, JSON, NeXML.

https://ja.wikipedia.org/wiki/TreeBASE
TreeBASE (トゥリーベイス) [1]は、「Scientific journal（英語版） 」誌に掲載された系統学のデータのリポジトリである。TreeBASE使用上の系統学の研究における研究データとは、分類群の一組やその一組の分類群に関するメタデータおよび分類群間での進化的関係を最もよく説明する為に推論されている系統樹について、（例えば、形質進化の変化の回数が最小になるように、系統推定を行う方法や多重整列などを）比較している結果や報告などを収集または生成されて得られる。

2011 年 1 月 31 日　改訂
井上 潤
https://fish-evol.org/TreeBase_JI.html
TreeBASE は系統解析の論文で用いられたアライメントデータ等を保存しているデータベースです．

https://pubmed.ncbi.nlm.nih.gov/19426482/
BMC Evol Biol
. 2009 May 8:9:93. doi: 10.1186/1471-2148-9-93.
Improved data retrieval from TreeBASE via taxonomic and linguistic data enrichment
Nadia Anwar 1, Ela Hunt
https://bmcecolevol.biomedcentral.com/articles/10.1186/1471-2148-9-93
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2685121/

https://pubmed.ncbi.nlm.nih.gov/17511869/
BMC Bioinformatics
. 2007 May 18:8:158. doi: 10.1186/1471-2105-8-158.
TBMap: a taxonomic perspective on the phylogenetic database TreeBASE
Roderic D M Page 1
https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-8-158
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1885449/

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
### OrthoFinder

http://www.stevekellylab.com/software/orthofinder

https://github.com/davidemms/OrthoFinder

https://github.com/davidemms/OrthoFinder/blob/master/OrthoFinder-manual.pdf

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
## physpetools

https://github.com/yangfangs/physpetools
PhySpeTree: an automated pipeline for reconstructing phylogenetic species trees

12:00 PM · Dec 15, 2019
https://twitter.com/fiddler_K/status/1206046415211728896
(1) Kawai_Yusuke on Twitter: "［メモ］あとでちょっと使ってみる。種名を入れたら自動で系統樹を推定するソフト/PhySpeTree: an automated pipeline for reconstructing phylogenetic species trees https://t.co/Nnk2ysKCSV" / Twitter

https://pubmed.ncbi.nlm.nih.gov/31791235/
BMC Evol Biol
. 2019 Dec 2;19(1):219. doi: 10.1186/s12862-019-1541-x.
PhySpeTree: an automated pipeline for reconstructing phylogenetic species trees
Yang Fang 1, Chengcheng Liu 2, Jiangyi Lin 3, Xufeng Li 1, Kambiz N Alavian 4 5, Yi Yang 6, Yulong Niu 7
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6889546/
https://bmcevolbiol.biomedcentral.com/articles/10.1186/s12862-019-1541-x
Sequence alignment and tree reconstruction
PhySpeTree integrates various tools for multiple sequence alignment and tree reconstruction.
MUSCLE [21], MAFFT [22], and Clustal [22]
RAxML
IQ-TREE [26] and FastTree [27]




----------
## command-line

ETE tools


### BuddySuite
https://pubmed.ncbi.nlm.nih.gov/28333216/
Mol Biol Evol
. 2017 Jun 1;34(6):1543-1546. doi: 10.1093/molbev/msx089.
BuddySuite: Command-Line Toolkits for Manipulating Sequences, Alignments, and Phylogenetic Trees
Stephen R Bond 1, Karl E Keat 1, Sofia N Barreira 1, Andreas D Baxevanis 1
https://academic.oup.com/mbe/article/34/6/1543/3049544
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5850830/
Documentation for each BuddySuite tool, including usage examples, is available at http://tiny.cc/buddysuite_wiki. All software is open source and freely available through http://research.nhgri.nih.gov/software/BuddySuite.

### phyx

https://github.com/FePhyFoFum/phyx

https://pubmed.ncbi.nlm.nih.gov/28174903/
Bioinformatics
. 2017 Jun 15;33(12):1886-1888. doi: 10.1093/bioinformatics/btx063.
Phyx: phylogenetic tools for unix
Joseph W Brown 1, Joseph F Walker 1, Stephen A Smith 1
https://academic.oup.com/bioinformatics/article/33/12/1886/2975328
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5870855/


### phylommand

https://github.com/RybergGroup/phylommand
Phylommand (Phylogenetics on the command line) is a software package for creating, manipulating, and/or getting statistics from trees or working with pairwise alignments. 

22 Dec 2016
https://doi.org/10.12688/f1000research.10446.1
Phylommand - a command line software package for phylogenetics [version 1; peer review: 2 approved with reservations]


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


http://www.fish-evol.org/
井上 潤のウェブサイト

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

## updates

### 2023

https://pubmed.ncbi.nlm.nih.gov/36799928/
Genome Biol Evol
. 2023 Mar 3;15(3):evad026. doi: 10.1093/gbe/evad026.
OrthoPhy: A Program to Construct Ortholog Data Sets Using Taxonomic Information
Tomoaki Watanabe 1, Akinori Kure 2, Tokumasa Horiike 3
https://academic.oup.com/gbe/article/15/3/evad026/7044703
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9991595/
Homologs are genes derived from a common ancestor, and orthologs and paralogs are homologs derived from speciation and gene duplication, respectively. Homologs derived from horizontal gene transfer are called xenologs. In addition to speciation, paralogs and xenologs go through gene duplication or horizontal gene transfer; thus, their phylogenetic relationships do not reflect those of the species (Koonin 2005).


https://pubmed.ncbi.nlm.nih.gov/32886787/
Mol Biol Evol
. 2021 Jan 23;38(2):727-734. doi: 10.1093/molbev/msaa224.
CoreCruncher: Fast and Robust Construction of Core Genomes in Large Prokaryotic Data Sets
Connor D Harris 1, Ellis L Torrance 1, Kasie Raymann 1, Louis-Marie Bobay 1
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7826169/
CoreCruncher does not compute all pairwise genome comparisons and uses a heuristic based on the distributions of identity scores to classify sequences as orthologs or paralogs/xenologs. Although it is much faster than current methods, our results indicate that our approach is more conservative than other tools and less sensitive to the presence of paralogs and xenologs.


----------

### 2021


### 2021-05-17

https://kazumaxneo.hatenablog.com/entry/2020/10/27/204402
タンパク質をコードする遺伝子配列の組換えイベントや正の選択下にある部位を見つける PoSeiDon - macでインフォマティクス
https://pubmed.ncbi.nlm.nih.gov/32735310/
Bioinformatics
. 2021 May 17;37(7):1018-1020. doi: 10.1093/bioinformatics/btaa695.
PoSeiDon: a Nextflow pipeline for the detection of evolutionary recombination events and positive selection
Martin Hölzer 1 2, Manja Marz 1 2 3
https://academic.oup.com/bioinformatics/article/37/7/1018/5879277
HyPhy GARD CODEML PAML

### 2021-02

1:01 AM · Feb 18, 2021
https://twitter.com/richardneher/status/1362069636381032448
Richard Neher on Twitter: "Do you find yourself in need of aligning 500k very similar sequences on a laptop? We (mostly @ivan_aksamentov) developed a reference aligner 'nextalign' that aligns 500k sequences in 30min using 8 cores and just a few GB of RAM. https://t.co/ElItsr2sWr https://t.co/GCBCbSyIkq" / Twitter

https://twitter.com/AineToole
4:29 AM · Feb 18, 2021
https://twitter.com/AineToole/status/1362122104796282880
Áine O'Toole on Twitter: "pangolin PSA 📢 We've just tagged a new release of pangolin (v2.3) that comes with an optional flag `--alignment`, so you can now easily output an alignment of your sequences along with the lineage report. https://t.co/0Cso0z8DPk" / Twitter

08 February 2021
https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btab093/6130791
FASTRAL: Improving scalability of phylogenomic analysis | Bioinformatics | Oxford Academic
ASTRAL is the current leading method for species tree estimation from phylogenomic datasets (i.e., hundreds to thousands of genes) that addresses gene tree discord resulting from incomplete lineage sorting (ILS). ASTRAL is statistically consistent under the multi-locus coalescent model (MSC), runs in polynomial time, and is able to run on large datasets.
ASTRALは、数百から数千の遺伝子を含む系統図データから種の木を推定するための現在の主要な手法です。
incomplete lineage sorting (ILS)に起因する遺伝子ツリーの不一致に対処する、
ASTRALは、multi-locus coalescent model (MSC)の下で統計的に一貫しており、
https://github.com/PayamDiba/FASTRAL

### 2020

### 2019


2019年12月2日月曜日
https://evotools.blogspot.com/2019/12/beast2.html
系統解析備忘録: BEAST2による分岐年代推定①

12:10 PM · Oct 28, 2019
https://twitter.com/art_poon/status/1188654334436872192
Art Poon on Twitter: "For my #BioInformatics class, I wrote a #d3js interactive #dataviz to teach my students the difference between an unrooted and rooted phylogeny. This displays a simplified version of the @sabeti_lab's Ebola virus phylogeny - root-to-tip regression is next! https://t.co/COTdboVyfb" / Twitter

2019年10月21日に更新
https://qiita.com/kaizen_nagoya/items/150646f72c55a36f8c39
遺伝子解析、遺伝子機能解析 - Qiita

2019/10/19
https://kimbio.info/mafft→raxml→figtreeで遺伝子の系統樹を作成する-ubuntu19-04
MAFFT→RAxML→FigTreeで遺伝子の系統樹を作成する - Ubuntu19.04 - Kim Biology & Informatics

2019/03/06
https://qiita.com/MaedaTaro_Umiushi/items/d4004d3fb219a4f991e8
orthofinder + prequal+ mafft + iq-treeでゲノム規模のデータから系統樹を作る - Qiita

### 2018

2018年07月27日
https://qiita.com/MaedaTaro_Umiushi/items/7c8cee435347eeee1cf5
orthofinder + mafft + trimal + iq-treeでゲノム規模のデータから系統樹を作る - Qiita

https://doi.org/10.7875/togotv.2018.093
2018-04-03 MAFFT・RAxML・FigTreeを組み合わせて分子系統解析を行う

### 2017

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
## alignment
アライメント



http://kazumaxneo.hatenablog.com/archive/category/multiple%20sequence%20alignment%20%28MSA%29

https://pubmed.ncbi.nlm.nih.gov/32797207/
Syst Biol
. 2021 Apr 15;70(3):440-462. doi: 10.1093/sysbio/syaa064.
Do Alignment and Trimming Methods Matter for Phylogenomic (UCE) Analyses?
Daniel M Portik 1 2, John J Wiens 1
https://academic.oup.com/sysbio/article-abstract/70/3/440/5892776?redirectedFrom=fulltext

https://pubmed.ncbi.nlm.nih.gov/26031838/
Syst Biol
. 2015 Sep;64(5):778-91. doi: 10.1093/sysbio/syv033. Epub 2015 Jun 1.
Current Methods for Automated Filtering of Multiple Sequence Alignments Frequently Worsen Single-Gene Phylogenetic Inference
Ge Tan 1, Matthieu Muffato 2, Christian Ledergerber 3, Javier Herrero 4, Nick Goldman 2, Manuel Gil 5, Christophe Dessimoz 6
https://academic.oup.com/sysbio/article/64/5/778/1685763
https://www.ncbi.nlm.nih.gov/labs/pmc/articles/PMC4538881/


https://pubmed.ncbi.nlm.nih.gov/17081313/
BMC Bioinformatics
. 2006 Nov 3;7:484. doi: 10.1186/1471-2105-7-484.
A statistical score for assessing the quality of multiple sequence alignments
Virpi Ahola 1, Tero Aittokallio, Mauno Vihinen, Esa Uusipaikka
https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-7-484
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1687212/
https://bio.tools/multidisp
MultiDisp
http://structure.bmc.lu.se/MultiDisp/index.html



https://molevol.mbl.edu/index.php/Alignment_tutorial
Alignment tutorial - MolEvol
This page was last edited on 2 August 2019, at 14:13.


http://www.gen-info.osaka-u.ac.jp/~uhmin/study/history.html
History of uhmin tools
2013年
4月5日
マルチプルアライメント Multiple sequence alignment
・アミノ酸の読み枠を考慮したアライメントが可能になりました。
tranalignを選択してコーディングフレームを入力すると、 アミノ酸に翻訳した後に mafft の自動モードでアライメントを行い、 アミノ酸アライメントの結果を元に塩基配列をアライメントします。
タンパクコード領域塩基配列のマルチプルアライメントのサイトを参考にさせてもらいました。感謝！


最終更新時間：2007年03月17日 05時57分52秒
https://www.fifthdimension.jp/wiki.cgi?page=%A5%BF%A5%F3%A5%D1%A5%AF%A5%B3%A1%BC%A5%C9%CE%CE%B0%E8%B1%F6%B4%F0%C7%DB%CE%F3%A4%CE%A5%DE%A5%EB%A5%C1%A5%D7%A5%EB%A5%A2%A5%E9%A5%A4%A5%E1%A5%F3%A5%C8
タンパクコード領域塩基配列のマルチプルアライメント - Life is fifthdimension.

アミノ酸配列を参照しての塩基配列アライメント
　EMBOSSのtranalignコマンドを用いて、アライメント済みアミノ酸配列をリファレンスとして塩基配列をアライメントします。これで翻訳後のアミノ酸配列の変化を最小化するような塩基配列のアライメントが完了します。

https://www.ncbi.nlm.nih.gov/pubmed/22936717
Mol Biol Evol. 2013 Jan;30(1):154-66. doi: 10.1093/molbev/mss210. Epub 2012 Aug 30.
Inferring the evolutionary history of IncP-1 plasmids despite incongruence among backbone gene trees.
Sen D1, Brown CJ, Top EM, Sullivan J.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3525142/
Nucleotide Sequence Alignments and Model Selection
The amino acid sequences of each gene were aligned with ClustalX (Thompson et al. 2002). Tranalign (Rice et al. 2000) was used to align the nucleotide sequences of each gene guided by the aligned amino acid sequences.

----------
### clustal-omega

https://kazumaxneo.hatenablog.com/entry/2020/07/30/073000
マルチプルシーケンスアラインメントを行う Clustal Omega - macでインフォマティクス

2017.04.09
https://bi.biopapyrus.jp/seq/alignment/software/clustal-omega.html
Clustal Omega

2015.03.16
https://doi.org/10.7875/togotv.2015.019
Clustal Omega を使ってマルチプルアラインメントを行う | TogoTV

----------
### macse
MACSE: Multiple Alignment of Coding SEquences

https://bioweb.supagro.inra.fr/macse/

https://bioweb.supagro.inra.fr/macse/index.php?menu=downloadTuto
Download documents related to MACSE v2.03:
Download the tutorial file: doc_MACSE_v2.03.pdf
https://bioweb.supagro.inra.fr/macse/doc/doc_MACSE_v2.03.pdf
In the output alignment produced by MACSE, frameshifts are indicated using '!'. 

http://mbb.univ-montp2.fr/macse
http://mbb.univ-montp2.fr/MBB/

http://kazumaxneo.hatenablog.com/entry/2017/09/09/014350
コード領域のアミノ酸配列を考えてマルチプルアライメントを行うMUCSE - macでインフォマティクス
2016年にversion2にアップデートされ、2018年夏にv2の論文が出ました。

https://pubmed.ncbi.nlm.nih.gov/30165589/
Mol Biol Evol
. 2018 Oct 1;35(10):2582-2584. doi: 10.1093/molbev/msy159.
MACSE v2: Toolkit for the Alignment of Coding Sequences Accounting for Frameshifts and Stop Codons
Vincent Ranwez 1, Emmanuel J P Douzery 2, Cédric Cambon 1 2, Nathalie Chantret 1, Frédéric Delsuc 2
https://academic.oup.com/mbe/article/35/10/2582/5079334
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6188553/

https://pubmed.ncbi.nlm.nih.gov/21949676/
PLoS One
. 2011;6(9):e22594. doi: 10.1371/journal.pone.0022594. Epub 2011 Sep 16.
MACSE: Multiple Alignment of Coding SEquences accounting for frameshifts and stop codons
Vincent Ranwez 1, Sébastien Harispe, Frédéric Delsuc, Emmanuel J P Douzery
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3174933/
https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0022594

----------
### translatorx
http://translatorx.co.uk

https://pubmed.ncbi.nlm.nih.gov/20435676/
Nucleic Acids Res
. 2010 Jul;38(Web Server issue):W7-13. doi: 10.1093/nar/gkq291. Epub 2010 Apr 30.
TranslatorX: multiple alignment of nucleotide sequences guided by amino acid translations
Federico Abascal 1, Rafael Zardoya, Maximilian J Telford
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2896173/
https://academic.oup.com/nar/article/38/suppl_2/W7/1094709
Figure 1.
Example illustrating the different performance of the direct and back-translated nucleotide alignments (multiple alignments were built with Muscle with default parameters).

----------
### mafft

https://mafft.cbrc.jp/alignment/software/
MAFFT - a multiple sequence alignment program

Fasta format.  example1 (LSU rRNA), example2 (protein)

Manual (v6.240)
https://mafft.cbrc.jp/alignment/software/manual/manual.html
This manual does not cover all the features of the latest version.
See also tips and changelog. (Feb. 2011)

Tips (not yet included in the manual) for large alignment, ncRNA alignment, profile alignment, etc.
https://mafft.cbrc.jp/alignment/software/tips0.html
- How to get a guide tree or a rough clustering
- How to give a user-defined guide tree
- 
- Codon-based alignment or DNA alignment based on translated protein sequences

https://mafft.cbrc.jp/alignment/software/anysymbol.html
Ambiguous nucleotides (r, y, w, s, k, m, d, v, h, b; IUPAC-IUB codes) can be used and are scored as:
```
score(r,a) = ( score(a,a) + score(g,a) ) / 2
```

https://mafft.cbrc.jp/alignment/software/algorithms/algorithms.html
MAFFT ver.7 - a multiple sequence alignment program
```
Algorithms and parameters (unfinished)
(a) FFT-NS-1, FFT-NS-2 — Progressive methods
(b) FFT-NS-i, NW-NS-i — Iterative refinement method
(c) L-INS-i, E-INS-i, G-INS-i — Iterative refinement methods using WSP and consistency scores
```
For pairwise alignment, three different types of algorithms are implemented, global alignment (Needleman-Wunsch), local alignment (Smith-Waterman) with affine gap costs (Gotoh) and local alignment with generalized affine gap costs (Altschul). The differences in the accuracy values among these methods are small for the currently available benchmarks, as shown here. However, each of them has different characteristics, according to the algorithm in the pairwise alignment stage:


https://mafft.cbrc.jp/alignment/software/manual/manual.html
Accuracy-oriented methods:

*L-INS-i (probably most accurate; recommended for <200 sequences; iterative refinement method incorporating local pairwise alignment information):
```
mafft --localpair --maxiterate 1000 input [> output]
linsi input [> output]
```

*G-INS-i (suitable for sequences of similar lengths; recommended for <200 sequences; iterative refinement method incorporating global pairwise alignment information):
```
mafft --globalpair --maxiterate 1000 input [> output]
ginsi input [> output]
```

*E-INS-i (suitable for sequences containing large unalignable regions; recommended for <200 sequences):
```
mafft --ep 0 --genafpair --maxiterate 1000 input [> output]
einsi input [> output]
```
For E-INS-i, the --ep 0 option is recommended to allow large gaps.


--genafpair
All pairwise alignments are computed with a local algorithm with the generalized affine gap cost (Altschul 1998). More accurate but slower than --6merpair. Suitable when large internal gaps are expected. Applicable to up to ~200 sequences. A combination with --maxiterate 1000 is recommended (E-INS-i). Default: off (6mer distance is used)


2006 年 44 巻 2 号 p. 102-108
https://www.jstage.jst.go.jp/article/kagakutoseibutsu1962/44/2/44_2_102/_article/-char/ja/
実践的マルチプルアラインメント
加藤 和貴, 隈 啓一
https://www.jstage.jst.go.jp/article/kagakutoseibutsu1962/44/2/44_2_102/_pdf/-char/ja
--globalpair と--localpair は通常のaffine gap
cost(15)を 用 い る が, --genafpair は generalized affine
gap cost(16)と いう, よ り複雑なギ ャップコス トを用い る. generalized affine gap cost は, ア ラ イ ン メ ン トを
作成することが無意味であるほど類似度の低い領域を含 んでいるときに有効であると考えて導入 したが, 有効性 を明確 に示すことはできていない. 


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

https://sci-tech.ksc.kwansei.ac.jp/~tohhiro/bioinfo18/bioinfo2018-2.pdf
藤 博幸
アフィン・ ギャップ・ペナルティ

2010/05/21
柏木 明博
https://sites.google.com/site/kashiwagiakihiro/Home/local-alignment-and-affine-gap-penalty
ローカルアライメントとアフィンギャップペナルティ
 また、Gap が連続したとき、連続した Gap も同じ値を使った線形 Gap Penalty 値を使用していましたが、
今回は、Gap が連続した時には、2 つ目以降の Gap には違う値、通常最初の Gap より小さな値を使用する
Affine Gap Penalty に対応します。


https://doi.org/10.7875/togotv.2019.193
2019-12-06 MEGA X を用いた分子系統解析 @ 分子系統樹推定法:理論と応用 ワークショップ
41:40 / 52:32
Gapが入るところは捨てる。
Gapが入らないところだけ使う。

http://www.tezuru-mozuru.com/?tag=mega
- Gaps/Missing Data Treatment：ギャップの扱いの設定です．Complete deletionとすると，一つでもギャップがあるサイト（列）を解析からのぞけます．
- Gaps/Missing Data Treatment：ギャップやミッシングデータの取り扱いが選べます．Complete deletionで，ギャップが一つでもある列は解析殻除きます．Partial Deletionで，比較する配列ごとにギャップの扱いを決めます．Use all siteでギャップもミッシングデータも全て扱います．


June 10, 2011
https://a-little-book-of-r-for-bioinformatics.readthedocs.io/en/latest/index.html
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
t. specifies the type of sequences in the current alignment. It can be Protein, DNA or Codons. In protein alignments, the 20 amino acid letters are used to calculate the degree of conservation of positions, and it is possible to invoke the use of a similarity matrix. In DNA and codon alignments, only A, C, G, T and U letters are considered (other symbols are allowed but do not count in the calculations). In codon alignments, selected blocks are made to contain only complete codons (if the alignment is really based on codons).

-t=	Type Of Sequence
(Protein, DNA, Codons)	p, d, c

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

http://trimal.cgenomics.org/getting_started_with_trimal_v1.2
```
   trimal -in example1 -out output1 -htmlout output1.html -gt 1
```
will remove all columns with any gap (equivalent to -nogaps option)


https://pubmed.ncbi.nlm.nih.gov/19505945/
Bioinformatics
. 2009 Aug 1;25(15):1972-3. doi: 10.1093/bioinformatics/btp348. Epub 2009 Jun 8.
trimAl: a tool for automated alignment trimming in large-scale phylogenetic analyses
Salvador Capella-Gutiérrez 1, José M Silla-Martínez, Toni Gabaldón
https://academic.oup.com/bioinformatics/article/25/15/1972/213148
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2712344/
In most scenarios (90%), trimAl outperformed Gblocks v0.91b with default parameters. 

http://www.fish-evol.org/trimAl_ji.html
trimAl - JI
2016 年 3 月 31日　改訂
井上 潤
以下のように，自動的に削除するサイトを選んでくれるオプション (-gappyout) もあります．より厳しく削る場合は -strict か -strictplus を選びます．

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
ETE Toolkit - Analysis and Visualization of (phylogenetic) trees


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

2017年05月26日
https://qiita.com/okuman/items/3dd1cd1292940442fcd0
ETE Toolkitを使ってPythonで色々な形の系統樹を書く - Qiita

### root_digger

https://github.com/computations/root_digger
RootDigger is a program that will, when given a MSA and an unrooted tree with branch lengths place a root on the given tree. For the foreseeable future, RootDigger will only support DNA data, as the method RootDigger uses is ineffective when using AA data.
RootDiggerは、MSAと、枝の長さが指定された根のない木が与えられると、与えられた木に根を張るプログラムです。RootDiggerが使用する方法はAAデータを使用する際には効果がないため、当面の間、RootDiggerはDNAデータのみをサポートする。

2021-05-01
https://pubmed.ncbi.nlm.nih.gov/33932975/
BMC Bioinformatics
. 2021 May 1;22(1):225. doi: 10.1186/s12859-021-03956-5.
Root Digger: a root placement program for phylogenetic trees
Ben Bettisworth 1, Alexandros Stamatakis 2 3
https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-03956-5
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8088003/

### iqtree

- http://www.iqtree.org/
IQ-TREE: Efficient phylogenomic software by maximum likelihood
- http://www.iqtree.org/doc/Quickstart
Getting Started
- http://www.iqtree.org/doc/Tutorial
Beginner's Tutorial
- http://www.iqtree.org/doc/Advanced-Tutorial
Advanced Tutorial
- http://www.iqtree.org/doc/Dating
Phylogenetic Dating
- http://www.iqtree.org/doc/Frequently-Asked-Questions
Frequently Asked Questions
- http://www.iqtree.org/doc/Substitution-Models
Substitution Models

http://www.iqtree.org/doc/
 IQ-TREE Tutorials and Manual in one PDF
http://www.iqtree.org/doc/iqtree-doc.pdf
IQ-TREE version 2.1.2: Tutorials and Manual
Phylogenomic software by maximum likelihood
http://www.iqtree.org
Bui Quang Minh, Rob Lanfear, Nhan-Trong Ly
Jana Trifinopoulos, Dominik Schrempf, Heiko A. Schmidt
November 1, 2021


https://pubmed.ncbi.nlm.nih.gov/32011700/
Mol Biol Evol
. 2020 May 1;37(5):1530-1534. doi: 10.1093/molbev/msaa015.
IQ-TREE 2: New Models and Efficient Methods for Phylogenetic Inference in the Genomic Era
Bui Quang Minh 1 2, Heiko A Schmidt 3, Olga Chernomor 3, Dominik Schrempf 3 4, Michael D Woodhams 5, Arndt von Haeseler 3 6, Robert Lanfear 2
https://academic.oup.com/mbe/article/37/5/1530/5721363
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7182206/


6:19 PM · May 6, 2020
https://twitter.com/RobLanfear/status/1257963198474403840
Rob Social Distancing Lanfear on Twitter: "Here's what I've been doing all day. If you're looking to estimate a single tree topology for SARS-CoV-2 sequences, it's very hard to beat Maximum Parsimony. rapidnj is also very good (not significantly different from MP) and *unbelievably* fast. https://t.co/QNKdnxORwC" / Twitter
Note that if you use IQ-TREE with the -fast option (or any option, actually), you will get a tree that's at least as good as the MP tree. That's because IQ-TREE always uses at least one MP tree as a starting tree and tries to improve it.

http://www.iqtree.org/doc/Tutorial#choosing-the-right-substitution-model

#### iqtree_ModelFinder

http://www.iqtree.org/ModelFinder/

https://pubmed.ncbi.nlm.nih.gov/28481363/
Nat Methods
. 2017 Jun;14(6):587-589. doi: 10.1038/nmeth.4285. Epub 2017 May 8.
ModelFinder: fast model selection for accurate phylogenetic estimates
Subha Kalyaanamoorthy 1 2, Bui Quang Minh 3, Thomas K F Wong 1 4, Arndt von Haeseler 3 5, Lars S Jermiin 1 4
https://www.nature.com/articles/nmeth.4285
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5453245/

#### iqtree_Rootstrap

Last update: Jun 7, 2024, Contributors: Minh Bui, Suha Naser
http://www.iqtree.org/doc/Rootstrap
Rooting phylogenies
http://www.iqtree.org/doc/Rootstrap#inferring-rooted-trees-without-outgroup

2022-06-16
https://pubmed.ncbi.nlm.nih.gov/34387349/
Syst Biol
. 2022 Jun 16;71(4):959-972. doi: 10.1093/sysbio/syab067.
Assessing Confidence in Root Placement on Phylogenies: An Empirical Study Using Nonreversible Models for Mammals
Suha Naser-Khdour 1, Bui Quang Minh 1 2, Robert Lanfear 1
https://academic.oup.com/sysbio/article/71/4/959/6350503
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9260635/

#### iqtree_Assessing-Phylogenetic-Assumptions

Last update: Mar 15, 2021, Contributors: Minh Bui
http://www.iqtree.org/doc/Assessing-Phylogenetic-Assumptions
Assessing Phylogenetic Assumptions

Tests of symmetry
IQ-TREE provides three matched-pairs tests of symmetry (Naser-Khdour et al., 2019) to test the two assumptions of stationarity and homogeneity. A simple analysis:

2019-12-01
https://pubmed.ncbi.nlm.nih.gov/31536115/
Genome Biol Evol
. 2019 Dec 1;11(12):3341-3352. doi: 10.1093/gbe/evz193.
The Prevalence and Impact of Model Violations in Phylogenetic Analysis
Suha Naser-Khdour 1, Bui Quang Minh 1 2, Wenqi Zhang 1, Eric A Stone 1, Robert Lanfear 1
https://academic.oup.com/gbe/article/11/12/3341/5571717
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6893154/
In phylogenetic inference, we commonly use models of substitution which assume that sequence evolution is stationary, reversible, and homogeneous (SRH).

#### iqtree_Concordance-Factor

Last update: May 27, 2024, Contributors: Minh Bui, Rob Lanfear, Trongnhan Uit
http://www.iqtree.org/doc/Concordance-Factor
Concordance Factor

HINT: See very nice tips on how to use and interpret concordance factors written by Rob Lanfear.
14 December 2018
https://www.robertlanfear.com/blog/files/concordance_factors.html
Calculating and interpreting gene- and site-concordance factors in phylogenomics | None | The Lanfear Lab @ANU

2020-09
https://pubmed.ncbi.nlm.nih.gov/32365179/
Mol Biol Evol
. 2020 Sep 1;37(9):2727-2733. doi: 10.1093/molbev/msaa106.
New Methods to Calculate Concordance Factors for Phylogenomic Datasets
Bui Quang Minh 1 2, Matthew W Hahn 3 4, Robert Lanfear 2
https://academic.oup.com/mbe/article/37/9/2727/5828940
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7475031/

#### iqtree_UFBoot

https://pubmed.ncbi.nlm.nih.gov/29077904/
Mol Biol Evol
. 2018 Feb 1;35(2):518-522. doi: 10.1093/molbev/msx281.
UFBoot2: Improving the Ultrafast Bootstrap Approximation
Diep Thi Hoang 1, Olga Chernomor 2, Arndt von Haeseler 2 3, Bui Quang Minh 2, Le Sy Vinh 1
https://academic.oup.com/mbe/article/35/2/518/4565479
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5850222/


#### iqtree_lang_ja

https://twitter.com/search?q=iqtree%20lang%3Aja&f=live

2023年08月07日
https://qiita.com/YF_bio/items/d952f54c8d570a6ea0cb
IQ-TREEで系統樹の最尤推定 #bioinformatics - Qiita

http://kazumaxneo.hatenablog.com/entry/2020/06/07/235834
IQ-TREE をwebで使える W-IQ-TREE - macでインフォマティクス
既にIQ-TREE2も発表（pubmed）されており、condaを使って導入できるバージョンも２になっていますが、2020年6月現在、web版はstable versionの1.6です。注意して下さい。

https://www.hobochuritsu.com/entry/2018/10/21/125017
IQ-Treeの使い方まとめ - ほぼ中立ブログ

2017年3月22日
http://www.tezuru-mozuru.com/?p=9927
iqtreeによる最尤法系統樹推定 – チームてづるもづる

----------
### QMaker

https://pubmed.ncbi.nlm.nih.gov/33616668/
Syst Biol
. 2021 Feb 22;syab010. doi: 10.1093/sysbio/syab010. Online ahead of print.
QMaker: Fast and accurate method to estimate empirical models of protein evolution
Bui Quang Minh 1 2, Cuong Cao Dang 3, Le Sy Vinh 3, Robert Lanfear 2
https://doi.org/10.1093/sysbio/syab010


Software implementation
We provided an implementation of QMaker as part of the IQ-TREE software version
2.0-rc1. The entire training stage for the Pfam dataset can be accomplished with just two
command lines. The first one is
iqtree -S ALN_DIR -nt 48

All data are available from the online supplementary material
(https://doi.org/10.6084/m9.figshare.9768101).


7:28 AM · Feb 23, 2021
https://twitter.com/RobLanfear/status/1363979095390912513
Rob Social Distancing Lanfear on Twitter: "Pleased to announce the birth of QMaker, which allows you to easily estimate amino-acid replacement matrices from your own data. Doing this work with @bq_minh, Cuong Cao Dang, and Le Sy Vinh threw up a few surprises, so here's a little  https://t.co/wWlFi5pHAf" / Twitter


https://www.biorxiv.org/content/10.1101/2020.02.20.958819v1
QMaker: Fast and accurate method to estimate empirical models of protein evolution | bioRxiv
https://www.biorxiv.org/content/10.1101/2020.02.20.958819v1.full


8:20 PM · Oct 8, 2020
https://twitter.com/kfuku0502/status/1314163771741556738
iqtreeで経験モデル作れる方法のプレプリント出てた気がするけどなんだったけ？から30分くらいかけてやっと辿り着いたのでメモ。QMakerだった。
でもこれアミノ酸配列限定か。コドンのを作りたいんだよな。ミトコンとかプラスチド用の経験的コドンモデルってどこかにないでしょうか？もし汎用的なのがあれば自前で作る必要ないんですが。

6:15 AM · Mar 15, 2020
https://twitter.com/kfuku0502/status/1238936843028254720
IQ-TREEでサポートされているらしい新しいアミノ酸置換モデルのプレプリント。大まかな系統ごとに経験的置換モデルを作っている。Fig. 2を見ると、なぜか植物で他の系統よりスコアがいい。





----------

### VeryFastTree
https://github.com/citiususc/veryfasttree.


7:50 AM · Mar 11, 2021
https://twitter.com/RobLanfear/status/1369782808558772226
VeryFastTree takes twice as long to do SPR moves as FastTree. Go figure! (Supposed to be the same codebase...)


Dec 1, 2020
https://twitter.com/kfuku0502/status/1333425581963292672
系統推定界のスピード狂、FastTree2が更なる並列化を含むカリッカリのチューニングを経てVeryFastTreeへ進化。331k個の16S rRNA配列の系統推定が4.5 hで終わる。
https://pubmed.ncbi.nlm.nih.gov/32573652/
Bioinformatics
. 2020 Nov 1;36(17):4658-4659. doi: 10.1093/bioinformatics/btaa582.
Very Fast Tree: speeding up the estimation of phylogenies for large alignments through parallelization and vectorization strategies
César Piñeiro 1, José M Abuín 1, Juan C Pichel 1

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
### phyml

http://www.atgc-montpellier.fr/phyml/usersguide.php
PhyML 3.0: new algorithms, methods and utilities

http://www.atgc-montpellier.fr/models/index.php?model=lg
LG: An Improved, General Amino-Acid Replacement Matrix

http://www.atgc-montpellier.fr/phyml/alrt/
A fast implementation of aLRT in PhyML.
"Approximate likelihood ratio test for branchs: A fast, accurate and powerful alternative."

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3548315/
Evolution of Conjugation and Type IV Secretion Systems
We performed the phylogenetic inference as mentioned earlier and additionally with PhyML 3.0 (Gascuel et al. 2010) under the LG model and with the bioNJ starting tree to get aLRT support values.

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

https://itol.embl.de/
iTOL: Interactive Tree Of Life

https://pubmed.ncbi.nlm.nih.gov/38613393/
Nucleic Acids Res
. 2024 Jul 5;52(W1):W78-W82. doi: 10.1093/nar/gkae268.
Interactive Tree of Life (iTOL) v6: recent updates to the phylogenetic tree display and annotation tool
Ivica Letunic 1, Peer Bork 2 3
https://pmc.ncbi.nlm.nih.gov/articles/PMC11223838/

https://pubmed.ncbi.nlm.nih.gov/27095192/
Nucleic Acids Res
. 2016 Jul 8;44(W1):W242-5. doi: 10.1093/nar/gkw290. Epub 2016 Apr 19.
Interactive tree of life (iTOL) v3: an online tool for the display and annotation of phylogenetic and other trees
Ivica Letunic 1, Peer Bork 2

https://kazumaxneo.hatenablog.com/entry/2020/07/02/100000
インタラクティブなオンラインの系統樹ツール Interactive Tree Of Life (iTOL) v4 - macでインフォマティクス
引用

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
## MEGA
MEGA: Molecular Evolutionary Genetics Analysis software

- https://www.megasoftware.net/

Documentation
[Online Manual](https://www.megasoftware.net/web_help)
First Time User

[walkthrough tutorial](https://www.megasoftware.net/web_help_10/Introduction.htm)
Introduction

1. [Mega Basics](https://www.megasoftware.net/web_help_10/Part_I_Getting_Started/A_Walk_Through_MEGA/MEGA_Basics.htm)
2. [Aligning Sequences](https://www.megasoftware.net/web_help_10/Part_I_Getting_Started/A_Walk_Through_MEGA/Aligning_Sequences.htm)
3. [Estimating Evolutionary Distances](https://www.megasoftware.net/web_help_10/Part_I_Getting_Started/A_Walk_Through_MEGA/Estimating_Evolutionary_Distances.htm)
4. [Building Trees from Sequence Data](https://www.megasoftware.net/web_help_10/Part_I_Getting_Started/A_Walk_Through_MEGA/Building_Trees_From_Sequence_Data.htm)
5. [Testing Tree Reliability](https://www.megasoftware.net/web_help_10/Part_I_Getting_Started/A_Walk_Through_MEGA/Testing_Tree_Reliability.htm)

Site Links
[Videos](https://www.megasoftware.net/videos)
Instructional Videos

### TUTORIALS

#### KUMAR LAB VIDEOS

Molecular Dating with MEGA

Choosing and Acquiring Sequences Part 1
https://www.youtube.com/watch?v=raaOgtvMJWw
2018/10/09

Choosing and Acquiring Sequences Part 2
https://www.youtube.com/watch?v=cVdmH7nNboE
2018/10/09

Reconstructing Ancestral Sequences
https://www.youtube.com/watch?v=djju9WFMvn0
2018/10/09

Relative Rate Framework for Efficient, Reliable, and Relaxed Clock Dating in MEGA

Inferring Selection with MEGA

MEGA X CC For Analysis Pipelines

Tree Inference with MEGA
https://www.youtube.com/watch?v=_ch8YIPvR-M
2019/08/01
This is presentation that took place at SMBE 2018 in Japan about a protocol on how to reconstruct phylogenetic trees with MEGA 10.

Bootstrap with MEGA
https://www.youtube.com/watch?v=qTmfQxT9HJc
2019/08/01
This is presentation that took place at SMBE 2018 in Japan about a protocol on how to bootstrap trees with MEGA 10.

#### MEGA X

Align Sequences then Compute Substitution Matrix, Compute Pairwise distance matrix, Construct ML Tree, and Find Gene Duplication
https://www.youtube.com/watch?v=m3qwVttzsKA
How to use MEGA software for evolutionary studies of HSP
2018/07/18

Build a Mega File from Multiple Fasta Files, then Construct a Neighbor Joining Tree
https://www.youtube.com/watch?v=hlgB3aRyE_8
How to use Molecular evolutionary Genetic Analysis (MEGA) software
2018/07/31

### MEGA_Tamura

7:10 PM · Apr 26, 2021
https://twitter.com/fiddler_K/status/1386623833897984003
［メモ］MEGA11がリリースされてる。機械学習で進化速度の自己相関をテストする方法やベイズ法で進化確率(EP)を推定する方法が追加されてるよう/MEGA11: Molecular Evolutionary Genetics Analysis version 11

https://pubmed.ncbi.nlm.nih.gov/33892491/
Mol Biol Evol
. 2021 Apr 23;msab120. doi: 10.1093/molbev/msab120. Online ahead of print.
MEGA11: Molecular Evolutionary Genetics Analysis version 11
Koichiro Tamura 1 2, Glen Stecher 3, Sudhir Kumar 3 4 5
https://academic.oup.com/mbe/advance-article/doi/10.1093/molbev/msab120/6248099

https://www.ncbi.nlm.nih.gov/pubmed/29722887
Mol Biol Evol. 2018 Jun 1;35(6):1547-1549. doi: 10.1093/molbev/msy096.
MEGA X: Molecular Evolutionary Genetics Analysis across Computing Platforms.
Kumar S1,2,3, Stecher G1, Li M1, Knyaz C1, Tamura K4,5.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5967553/

https://biosciencedbc.jp/blog/20200303-01.html
新型コロナウイルス（SARS-CoV-2）および新型コロナウイルス感染症（COVID-19）に関する研究データ・リソース - NBDC
DBCLSがNBDCとの共同研究の一環で運営する「統合TV」には、MEGAの最新バージョンを用いた分子系統樹の推定についての講義動画（日本語）が掲載されています。登壇者はMEGAの開発者である首都大学東京（東京都立大学）の田村教授です。

MEGA X を用いた分子系統解析 @ 分子系統樹推定法:理論と応用 ワークショップ | 統合TV
https://doi.org/10.7875/togotv.2019.193
https://twitter.com/hashtag/ws222?f=live

https://evolgen.biol.se.tmu.ac.jp/MEGA/default.html
MEGA3 チュートリアル（Actin gene coding region を例題として）
- 入力データの準備
- 配列データのアライメント
- 分子系統樹の作成

https://evolgen.biol.se.tmu.ac.jp/MEGA/data-mining.htm
入力データの準備
１．配列データのダウンロード
２．シーケンサーデータの入力
３．テキストデータの入力（AlignmentExplorerの基本操作法）
４．相同配列の検索

https://evolgen.biol.se.tmu.ac.jp/MEGA/align-protocol.htm
配列データのアライメント

https://evolgen.biol.se.tmu.ac.jp/MEGA/tree-protocol.htm
分子系統樹の作成
１．近隣結合法による系統樹の作成とブートストラップ・テスト
２．系統樹を基にした解析例
（１） 分子時計を用いた分岐年代の推定 （哺乳類 チトクロームｂ遺伝子の場合）
（２）分類群と分子系統との関連（人類集団のD-loop配列の場合）

### Janecka Genomics

2020/12/19
https://www.youtube.com/watch?v=xKS5qZwl1GY
Making a Phylogenetic Tree with Bootstrap Support Values in MEGA
This video shows the steps in MEGA for opening a multiple sequence alignment, determining the best sequence evolution model, reconstructing a maximum likelihood phylogenetic tree with bootstrap support values, and saving the tree in three different formats. 

2020/12/13
https://www.youtube.com/watch?v=Pq4Cy76zNew
Making a Multiple Sequence Alignment in MEGA
This video shows the steps of obtaining nucleotide gene sequences from NCBI, editing the downloaded fasta file, importing the sequences into MEGA, and building a multiple sequence alignment.

### MEGA_unclassified

2020/07/06
https://www.youtube.com/watch?v=8eTkVIdmHbg
Phylogenetic Analysis with MEGA X - YouTube
KENNETH FRANCIS RODRIGUES -
This video tutorial describes the application of MEGA X for the alignment and phylogenetic reconstruction using a single locus.


https://sites.google.com/view/enter-the-fungi/phylogenetic-analysis/alignment
Enter the FUNGI - Fasta の整理とMUSCLE/ MAFFT でのアライメント
メモ MEGA X インストールコマンド on Linux 

https://bio-and.info/post/DNA_Analysis/PhylogeneticTreeConstruct
系統樹の書き方（MEGAを使用した系統樹の書き方） - バイオとインフォまとめ -
①. MEGAのインストール
②. アミノ酸配列の準備
③. MEGAにアミノ酸配列を取り込み、マルチプルアライメント
④. 系統樹の作成



https://sci-tech.ksc.kwansei.ac.jp/~tohhiro/bioinfo18/bioinfo2018-4.pdf
バイオインフォマティクス第四回
得られたアラインメントを使ってMEGAで系統樹を作成
(1) MEGAを起動してmafftで作成したアラインメント䛾読み込み

デフォルトではOriginal Treeが表示されている
Bootstrap consensus treeのタブを選択

2018/01/20
https://ultrabem-branch3.com/informatics/bioinformatics/tree_make_mega_ml
系統樹の作り方: MEGA で最尤法を使う
MEGA では、系統樹は .mts という拡張子で保存される。
Original Tree と Bootstrap concensus tree という 2 つのタブがある。

動画
https://doi.org/10.7875/togotv.2017.106
2017-11-06 MEGA7を使って配列のアラインメント・系統解析を行う

http://www.tezuru-mozuru.com/?tag=mega
MEGA – チームてづるもづる
2017年3月24日
http://www.tezuru-mozuru.com/?p=9939
MEGAによる最尤法系統樹推定

----------

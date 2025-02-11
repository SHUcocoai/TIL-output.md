# ITパスポートの内容　

# コンピューターの簡単な役割  
・ハードウェア  
機械の集まりのようなもので機能はあるが自身で動作することはできないものである。例で言うとゲーム機の本体のこと。  
・ソフトウェア  
ハードウェアにこう動けと指示する文書が集まったものであり、プログラムとも言う。ハードウェアが動くには、ソフトウェアがないと動かない。ゲーム機のソフトがあたる。  
・パソコンにおけるハードウェア  
パソコンの箱状の機械がそれにあたる。ソフトウェアは、OSでありwindowsとかがそれにあたる。  

# ハードウェア内の5大装置  
・制御装置  
CPU(central processing unit 中央処理装置)の中にある制御をする装置であり、プログラムの命令を解釈しコンピューター全体の動作を制御する役割である。  
・演算装置  
CPUの中にある演算をする装置であり、四則演算やデータの演算処理をする機能である。  
・記憶装置  
　・主記憶装置  
  動作時に必要なプログラムやデータを一時的に保持する役割である。電源を落とすとデータが消える。メモリがそれにあたる。  
  ・補助記憶装置  
  動作時に必要なプログラムやデータを長期的に保持する機能である。電源を落としてもデータが保存された状態のままである。ハードディスクのCD-ROM、DVD-ROMである。  
・入力装置  
コンピューターにデータを入力するための装置である。マウス、キーボード、スキャナーのこと。  
・出力装置  
コンピューターのデータを出力するための装置である。ディスプレイやプリンタのこと。  

# CPU  
コンピューターの頭脳にあたり制御と演算をする部分である。  
・レジスタ  
CPUにある非常に高速な小容量の記憶回路のことである。CPU内で一時的に記憶する所。  
・クロック  
コンピューターを周期的な信号で動作を調節する時の信号のことである。１周期をチクタクとして周期が短いほど処理速度が速い。  
・クロック周期数  
クロックが１秒間に繰り返される回数のことである。  
・キャッシュメモリ  
メモリ(主記憶装置)とCPUの速度差によるロスをなくすために間に置かれる高速読み書きのできるメモリのことである。処理速度がCPUが速く、主記憶装置が遅いため。 

# 装置どうしのつながり  
1入力データが必ず主記憶装置を経由してから各装置に伝達される。  
2命令の際には制御装置から各装置に伝達がされる。  
・ハブ  
CPUと各装置を結ぶ回線のことである。  

# メモリ  
・RAM(Random Access Memory)
一時的にデータ保持するためのメモリであり、電源を切るとデータが消去される。揮発性メモリという性質である。  
 ・DRAM(Dynamic RAM 動的RAM)
 SRAMより読み書きが低速であり、安価で容量が大きい主記憶装置に使われるメモリである。記憶内容を保持のために定期的にリフレッシュ動作（再書き込み）が必要。  
 ・SRAM(Static RAM　静的RAM)  
 DRAMに比べ高速であり、高価で小容量なためキャッシュメモリに使われるメモリである。リフレッシュ動作はいらない。  
 
・ROM(Read Only Memory)  
読み込み専用のメモリであり、家電といった決まった動作を行うものに対して使われる。電源を切ってもデータが残り、不揮発性メモリという性質である。  
出荷時に動作に必要なデータがメモリに書き込んである。  
 ・マスクROM  
 読み込み専用のメモリ  
 ・PROM(Programmable ROM)  
 ユーザーの手で書き換えることができるROMである。  
 ・EPROM(Erable PROM  消去可能PROM)  
 紫外線によってデータを消去して書き換えることができるPROMである。  
 ・EEPROM(Erectricity EPROM)  
 電気的にデータを消去し書き換えることができるPROMである。  
 ・フラッシュメモリ  
 EEPROMの一種であり、データを全消去でなくブロック単位で消去して書き換えることができるPROMである。

 # 仮想記憶  
 ハードディスク(補助記憶装置)の一部をメモリ(主記憶装置)とみなすように主記憶装置の扱える容量を増やす技術のことである。  
 ・スワップアウト  
 メモリで操作に必要ないプログラムやデータをハードディスクに一時的に移動し、メモリの空きを作ることである。  
 ・スワップイン  
 ハードディスクに移動していたプログラムやデータをメモリに呼び戻すことである。  
 ・スワッピング  
 仮想記憶のためにメモリとハードディスクで読み書きが発生することである。  

 # ハードディスク以外の補助記憶装置  
 ・リムーバルメディア  
 ディスクが回る駆動装置から記憶媒体を取り出すことができるものである。  
 ・光ディスク  
 レーザ光を使って読み書きを行うディスクメディアである。安価なためソフトウェア配布媒体として使われている。  
 ・光磁気ディスク(MO Magnet optical disk)  
 レーザー光と磁気を使い書き込みをする。読み出し時はレーザー光のみである。  
 ・磁気テープ  
 磁性体を塗ったテープを使い磁気によってデータの読み書きをするメディアである。低速だが大容量のためバックアップに使われる。  
 ・フラッシュメモリ  
 EEPROMの一種を補助記憶装置媒体に転用したものである。コンパクトで低価格でありSDカードやUSBメモリとして使用されている。  

 # SSD(Solid State Drive)  
 内部にディスクをもたないフラッシュメモリを記憶媒体として持つ装置である。省電力で衝撃に強く、ディスクでの読み書きを決める動作(シーク)や  
 ディスクの回転待ちの動作(サーチ)がいらないため高速に読み書きができる。  

 # 入力装置  
・トラックパッド  
ノートパソコンについているパット上で指を動かすことで移動情報を入力して位置を示す装置であり、マウスがわりに使う。  
・タッチパネル  
銀行ATMや駅の券売機で画面に触れて示す装置である。  
・タブレット  
絵を描くときに使う専用のペンで示す装置である。 
・ジョイスティック  
ゲームで使う  
・イメージスキャナ 
絵や写真を画像データとして読み取る装置であり、スキャンする装置のスキャナのこと。  
・キャプチャカード  
ビデオデッキの映像機器から映像デジタルデータとして読み取る装置である。 
・バーコードリーダ  
コンビニでビッとバーコードを読み取る装置のこと。  

# バーコード  
・JANコード  
一般の品物についているバーコードである商品識別コードであり、コードにある8桁から13桁の数字のタイプがある。  
・QRコード  
正方形状の情報が格納されているコードであり、格納できる情報量が多くiphoneのカメラ機能で読み込める。  
・RFID(Radio Frequency IDentification　無線周波数識別)  
光や電波を使って読み取りを行う非接触のスキャンシステムである。要は無線で読み取ること。例でグッズの商品にある四角の渦巻きのようなマークのリーダー。  

# 出力装置のディスプレイ画像の単位や装置の種類  
・解像度  
ディスプレイが表示される点のきめ細かさのことである。  

・CRTディスプレイ  
ブラウン管ディスプレイ  
・液晶ディスプレイ  
薄型ディスプレイであり、バックライトや外部の光を取り込むことで表示している。  
・有機ELディスプレイ  
有機化合物に電圧を加えることで発光するディスプレイのことである。  
・プラズマディスプレイ  
プラズマ放電で発光させるディスプレイである。高電圧のためパソコンには使われない。  

# 出力装置のプリンタ装置の種類と解像度  
・ドットインパクトプリンタ  
印字ヘッドにたくさんのピンがついていおり、インクリボンに打ち付けることで印字するプリンタである。  
・インクジェットプリンタ  
印字ノズルから用紙にインクを吹きつけて印刷するプリンタである。  
・レーザプリンタ  
レーザ光線を照射することで感光体上に１ページ分の印刷イメージを作成し、そこに引き寄せられて付着したトナーを紙に転写するプリンタである。  

・dpi(dot per inch)  
1インチあたりのドット数のことである。  
・CPS(character per second)  
1秒間に何文字印字できるかの印字速度である。ドットインパクトプリンタに使われる。  
・PPM(page per minute)  
１分間に何ページ印字できるかの印字速度である。レーザプリンタに使われる。  

# 3Dプリンタ  
３Dデータを使って立体物を造形する出力装置のことである。  
・熱溶解積層方式  
フィラメントという合成樹脂をノズルで溶かしながら一層ずつ積層して造形していく方式である。  
・光造形方式  
液体状の光硬化性樹脂を用いて一層ずつ積層する方式である。  

# 出入力インターフェース  
コンピューターを様々な周辺機器と繋ぐための規格である。  
・プラグアンドプレイ  
差し込めば使えるという意味でコンピューターに周辺機器を繋ぐことで自動的に設定が行われる仕組みである。  
・シリアルインターフェース  
直列で信号を１つずつ送る方式。  
・パラレルインターフェース  
並列で同時にまとめて信号を送る方式。  
現在は高速化を図るためにシリアルインターフェースが主流である。パラレルインターフェースだとまとめて同時に送るため１つでもずれが生じるのが致命傷になるから。  
・ホットプラグ  
電源を入れたまま抜き差しできる。  
・USB(Universal Serial Bus)  
パソコンと周辺機器を繋ぐための標準的なインターフェースである。  
・IEEE1394  
ハードディスクレコーダーやデジタルカメラなどに使われるインターフェースである。  
・IrDA(Infrared Date Association　赤外線データ協会)  
赤外線を使って無線通信を行う規格である。  
・Blue tooth  
2.4GHzの電波を使って無線通信を行う規格であり、ワイヤレスで行える。


## コンピューターの文字の表現  
文字コードとは各文字に番号をつけるように数値として割り当てたものである。コンピューターが処理をする際にその数値を情報として用いて表現している。
## 文字コード種類　　
・ASCII(アスキー)  
アメリカで定義された基本の文字コードである。文字はアルファベットと数字と記号であり、1文字7bitで表す。英語圏以外の言語や特殊な文字表現には不十分である。  
・EBCDIC(エビシディック)  
IBM社で定義された１文字を8bitで表す文字コードである。 大規模な基幹システムのコンピューターで使われている。 
・シフトJISコード  
ASCIIと混在して使える日本語文字コードである。ひらがな、カタカナ、漢字が使える。1文字の英数字で1Byte、全角文字を2Byteで表す。  
・EUC（イーユーシー）  
OSのUNIX上で使われる日本語文字コードである。英数字を1Byte、全角文字と半角カタカナを2Byte、補助漢字を3Byteで表す。  
・UNICODE(ユニコード)  
世界中の文字や記号を統一して使える文字コードである。使用する文字とエンコーディングによって1文字の容量が変わる。


## コンピューターでの画像、音声のデータ表現  
時計の針のように連続して変化する情報をアナログ情報といい、ある範囲を決まった桁数で区切り数値表現したものをデジタル情報という。
画像、音声データはデジタル情報に変換したものである。  
・画像データは、ビットマップ方式というドットの集まりで区切って表現したものであり、画像のドットをきめ細くする(解像度が高い)程滑らかになる。画像を表現するには、画像自体のドット数に合わせて色情報が必要であるため白黒なら1ドットにつき1bit、フルカラーなら1ドットにつき24bitの情報が含まれる。  
・音声データは、波形データをデジタル化して数値表現したものであり、時間ごとで区切って標本として表す標本化と標本化したものを何bitで表すかで段階を決めて当てはめ整数に表したものを量子化という。区切りの時間周期が短くビット数が多い方が原音に近くなる。


## 機器の制御
コンピューターがアナログ情報をセンサによって計測して電気信号に変換し、アクチュエータにより電気信号を物理動作に変換することで制御している。  
・温度センサや照度センサのように事象の計測をする装置をセンサといいセンサとコンピューター間でアナログ情報からデジタル情報に変換を行っている。 
・電気信号をモーターや電磁石を使って物理動作に変換する装置をアクチュエータといいコンピューターとアクチュエータの間でデジタル情報からアナログ情報に変換を行っている。  
制御方式  
・洗濯機のように給水から脱水まで決められた順序や条件に合わせて各段階の制御を進めていくものをシーケンス方式という。
・エアコンのように室温を設定した温度値に合わせていくように温度を定期的に測りながら調整して反映させて設定値に一致させていくものをフィードバック方式という。


## 補助記憶装置への保存
アプリケーションソフトで作られたデータはファイルという入れ物で補助記憶装置に保存されるものである。  
・テキスト形式とは、文字コード、改行、タブ、一部の特殊文字で作られるファイル形式である。  
・CSV形式とは、文字や数字をカンマで区切って一つのデータごとに改行することで表形式で保存できるファイル形式のことである。  
・PDFとは、文書データを電子化して表示できるファイル形式のことである。  

## 他のファイル形式　　
画像用ファイル形式  
・BMP（ビートマップ）  
圧縮せずそのまま保存できるファイル形式であるが、容量が大きい。  
・JPEG（ジェーペグ）  
写真の保存に適した画像圧縮形式でフルカラーで扱えるものであるが、不可逆圧縮（いくつか情報が欠ける状態）のため画質が劣化する場合がある。  
・GIF（ジフ）  
イラスト、アイコンの保存に適した画像圧縮形式で可逆圧縮のため画質が劣化しないが、カラーが256色の制限である。  
・PNG（ピング）  
フルカラーで可逆圧縮で画質劣化しないため万能である画像圧縮形式である。しかし、圧縮率がJPEGに劣っている。  

音声用ファイル形式  
・MP3（エムピースリー） 
音声を圧縮して保存するファイル形式である。　　
・MIDI（ミディ）  
デジタル楽器の演奏データを保存するファイル形式である。  

動画用ファイル形式  
・MPEG（エムペグ）  
動画を保存するファイル形式である。映像データや音声データの保存様式である。  


## ファイルの場所
・ファイルを束ねてしまう場所をディレクトリといい一番上の階層をルートディレクトリ、他のディレクトリの中にあるディレクトリをサブでディレクトリという。  
・現在作業しているディレクトリをカレントディレクトリといいカレントディレクトリを含んでいる上の階層のディレクトリを親ディレクトリという。  

## ファイルの示し方  
・ルートディレクトリからの経路を示すパスを絶対パスという。  
・カレントディレクトリからの経路を示すパスを相対パスという。  
・ルートディレクトリは/か¥で表し、次の階層との間は/か¥で区切って表す。カレントディレクトは.で表し、親ディレクトリは..で表す。  
 ※カレントディレクトリの先頭の./は省略できる。  
 絶対パス　ルートディレクトリからファイル３に行きたい時　　/ファイル1/ファイル2/ファイル3  
 相対パス　カレントディレクトリをファイル1にしてファイル３に行きたい時　　./ファイル2/ファイル3またはファイル2/ファイル3  
 カレントディレクトリのファイル1から親ディレクトリ（今回はルートディレクトリ）を経由してファイル1-1に行きたい時　　./../ファイル1-1または../ファイル1-1

 
 ## ハードディスク　の仕組み
内部にプラッタと呼ばれる金属の丸いディスクがあり、ディスク上でアクセスアームが移動して先端についている磁気ヘッドが指令を受けて磁化することで情報の読み書きを行なってる補助記憶装置である。  
・使い始めにフォーマット(初期化)をすることで金属ディスク上にデータ記録する領域が作られる。  
・その領域を扇状にわけたのをセクタといい最小単位を表す。  
・セクタを１周分にしたものをトラックといい、その同心円状のトラックを複数まとめたものをシリンダという。
・ハードディスクはセクタの最小単位で表すが、ソフトウェアのOSでは単位が小さすぎるため8セクタを1クラスタのようにクラスタという単位で表す。1クラスタで収まらない時、微量でも次の領域（次の1クラスタ内）に行ってしまう。次に新しいデータを読み込むときに前回の領域の残りが空いたままで次の領域に行くため無駄な領域ができる。  

## ハードディスクの処理時間  
データのアクセス時間 = シーク時間 + サーチ時間 + データ転送時間  
・シーク時間は、アクセスアームが目的のデータが書かれるトラック位置に移動する時間である。  
・サーチ時間は、ディスクの回転で書かれた目的データが磁気ヘッドの位置に来るまでの待つ時間である。  
・データ転送時間は、目的のデータが書かれたセクタから読み込む時間である。  

## ハードディスクの欠点  
フラグメンテンテーションとは、データファイルが保存される時にわかれて断片して保存されてしまうことである。ハードディスクにデータを書き込んだり消去したりを繰り返すことでディスク上で1つのデータが分散した領域で保存されてしまい、読み込む際に忙しなくアクセスアームを動かすことになりアクセス時間がかかりアクセス速度が落ちてしまう状態である。  
デフラグメンテーションとは、断片したデータを並べ直して連続したデータ領域に戻すことである。  

## 複数のハードディスク  
RAIDとは、複数のハードディスクを一つにまとめて運用する技術ディスクアレイの実装手段である。RAID0が高速化、RAID1とRAID5が信頼性という面で知られる。  
・RAID0は、2台以上のハードディスクを用いてデータを分散して保存するため高速化ができるRAIDである。だが、ハードディスクが片方でも故障するとデータは戻らない。  
・RAID1は、2代以上のハードディスクを用いて同じデータを保存していため片方のハードディスクが壊れても問題ない信頼性のあるRAIDである。  
・RAID5は、3台以上のハードディスクを用いてデータを分散して保存する時に１台分のパリティデータも別のディスクに分散して保存しているので、ハードディスクが1つ故障しても復元ができる。信頼性が高いRAIDである。

## OS
OSとはオペレーティングシステムといい、コンピューターにおけるメモリ管理、ファイルの管理、ハードウェアといった周辺機器の管理、動いて良いと指令を出してコンピューターを実行させるタスク管理といった基本的動作の土台となる基本ソフトウェアのことである。  
windows、MacOS、MS-DOS、UNIX、LINUXなど。 

## アプリケーションソフト
アプリケーションソフトとは、コンピューターで行う業務に必要な機能を与えて応用範囲を広げてくれる応用ソフトウェアのことである。  
・ワープロソフト  
文書を作成できるソフトウェアであり、表や図、写真を貼り付けたりできる。ex) word  
・表計算ソフト  
表のデータを集計、編集できるソフトウェアであり、表の数値を自動計算したり、グラフ化したりできる。ex)excel  
・プレゼンテーションソフト  
プレゼン用の資料で作りができるソフトウェアであり、スライド作成ができる。ex) powerpoint  
・webプラウザ  
webページ閲覧のためのソフトウェアである。ex) safari  google chrome  
・メールソフト  
電子メールの作成、送受信ができるソフトウェアである。ex) outlook

# ソフトウェアの区分  
・基本ソフトウェア  
OS、言語プロフェッサー
・応用ソフトウェア  
ワープロ、表計算といったアプリケーション  
・ミドルウェア  
基本ソフトウェアと応用ソフトウェアの橋渡しである。データベース管理ソフトウェア、開発支援ソフトウェア  

# RPA（ロボティックプロセスオートマトン)  
人手不足解消のためのソフトウェアの自動化のことであり、産業ロボットではなくコンピューターの中に閉じたソフトウェア的なロボット  
を示す。具体的に事務作業におけるデータ入力作業、定型文のメール送信など形が決まっている繰り返し作業においてはこのRPAの導入に  
より効率化できる。例外出るなど、形の決まっていない非定型の作業には向いていない。

# DRMS(データベース管理システム)  
データベースの定義や制御や操作の機能を持つミドルウェアのことである。  
・関係型  
データを表で管理する型である。データの内容次第で複数の表を関連づけることができることから関係データベースと呼ばれこの関係をリレーションシップと呼ぶ。  
そのためRDB(リレーショナルデータベース)とも言われる。  
ex)Ruby on Railsのモデル作成してマイグレーションファイルを複数作った後に表を関連づけができるので該当する。  
・階層型  
データを階層で管理する型である。  
・ネットワーク型  
データを網状に管理する型である。  

# 正規化  
データの内容に重複や矛盾が無いように表を分割したりすること。  
例として商品名の列が重複してしまう時、別の表を作成して商品名の表として分割しIDの列も作る。そのIDを参照して  
元の表に表示できるようにすることで商品名を変えるだけで重複の商品名を変更でき、重複が起こらない。  

# 関係演算  
表の中から特定の行や列を取り出したり、表と表をくっつけたりすること。  
・選択  
表の特定の条件の行のみを取り出す演算である。  
・射影  
表の特定の条件の列のみを取り出す演算である。  
・結合  
共通の列を持ってるいる表と表どうしをくっつける演算である。  

# ビュー表  
関係演算で作られる様々な仮想の表として表したものをビュー表と呼ばれる。  

# キー 
表を特定したり表どうしを関連づけるときに必要となる鍵情報のことである。
・主キー  
主キーは行を特定する鍵であり、ID番号がそれに該当する。複数の列を組み合わせた鍵は複合キーという。  
・外部キー  
表と表どうしを繋ぎ合わせる(関連づける)時の鍵であり、他の表の主キーを参照している。  

# 排他制御  
データベースの内容を勝手に読み書きしたり、消したりしないようにロックすることである。  
・共有制御  
各ユーザーがデータベースからの読み込みはできるが書き込みはできないロック方法である。  
・専有制御  
他ユーザーがデータベースからの読み書きはできないロック方法である。

# トランザクション  
データベースでの一連の処理の流れをまとめたものである。 

# コミット  
正常にトランザクション処理が完了した後にデータベースに反映するという更新の確定処理のことである。

# データベースの障害回復  
データベースは、定期的にバックアップファイルを作成してバックアップを行い、バックアップ後の更新としてジャーナルというログファイルに書かれ  
更新前の状態、更新後の状態を逐一記録して管理をしている。  
障害が起きた時にこれらのファイルを使って障害回復処理としてロールバック、ロールフォワードを行なっている。  
・ロールバック  
障害が起きた時にやりかけの処理を取り消すことである。更新前ジャーナルを取得して処理が始まる前の状態に戻す。  
ex トランザクション処理の途中で障害が起きた時  
・ロールフォワード  
障害が起きた時に処理をやり直すことである。直前のバックアップを復元して更新後ジャーナルを取得し障害の起こる直前に戻す。  
ex 物理的に壊れた時  

# トランザクションで必須ACID特性   
・Atomicity（原子性）  
トランザクションの処理結果は一部だけが実行ではなく、すべて実行されるか実行されないで終了すること。  
・Cosistency（一貫性）  
矛盾があってはいけないこと。  
・Isolation（隔離性）  
トランザクション処理を複数で実行、順番で実行で処理結果が一致すること。  
・Durability（耐久性）  
トランザクションの更新結果が障害が起きても消えないように復旧の保証があること。

# ネットワーク交換方式  
・回線交換方式  
送信元から送信先まで交換機を繋いで固定する方式  
・パケット交換方式  
通信データをパケットという単位に分割して交換機で宛先に合わせて適切な回線送る方式   

# 拠点間をつなぐ電気通信業者の通信サービスを用いた通信方式  
・専用線  
セキュリティが高く専用回線で結ぶサービスであるが、費用が高い。  
・フレームリレー方式  
パケット交換方式を元に誤り制御を簡略化して高速化した方式  
・ATM交換方式  
データ転送の単位を固定長のセルとすることで高速化を図った方式  
・広域イーサネット  
イーサネット技術を用いて拠点間の接続をする方式である。一般の機器で使えるのでコストがかからない高速な  
近年のサービスである。  

# イーサネットアクセス制御方式  
CSMA/CD方式  
Carrier Sence 他にデータを送っている者がいない場合にデータの送信をする。  
Collision Detection 同時に送信して衝突(コリジョン)が起きたら待機して再度送信する。  
Multiple Access 複数のコンピューターで共有ができる。

# プロトコル  
ネットワークを通じてコンピューター同士のやり取りの約束事のことである。プロトコルを７階層に分けたものをOSI基本参照モデルという。

# NIC  
コンピューターをネットワークに接続するための拡張カードのことである。LANボードともいう。  
NICなどのネットワーク機器にはMACアドレスという製造段階でつけられてた番号があり重複しない一意のものである。

# リピータ  
物理層の中継機能を提供する装置のことである。LANの間にリピータを設けることで送られた信号を整形して送ってくれるので歪まなくなる。  
不要なパケットと一緒に流してしまうため流すだけ流して受け取り側に一任されている。無条件にデータが流される範囲をセグメントという。  
この範囲内にコンピューターが大量に繋がれているとパケットの衝突が起きやすくなり回線の効率が悪くなる。

# ブリッジ  
データリンク層の中継機能を提供する装置である。セグメント間の中継として流れてきたパケットのMACアドレス情報を記憶し、橋渡しするパケット  
だけ中継し他方のセグメントに送る。CSMA/CD方式従って送るためパケットの衝突が抑制されてネットワークの利用効率が上がる。  

# ハブ  
LANケーブルの接続口を複数持つ装置である。リピーターを束ねたリピーターハブとブリッジを複数束ねたスイッチングハブがある。

# ルーター
ネットワーク層の中継機能を提供する装置である。異なるネットワークであるLAN同士の中継し、流れてきたパケットのIPアドレスを確認して
経路表(ルーティングテーブル)と合わせて最適な経路に転送する(ルーティング)。

# ゲートウェイ  
トランスポート層以上の層で異なるネットワーク間同士での差異のあるプロトコルの交換により接続を促すための中継機能を提供する装置である。  
インターネット電子メールと携帯メールはゲートウェイによるそれぞれ違うプロトコルの変換によってやり取りできる。

# TCP/IP  
IPは、複数のネットワークを繋いでその上にパケットが流れる仕組みを規定している土台のこと。TCPは、正しくデータが送られたことを保証する仕組み  
のことである。この技術は標準のものであり、企業内のLANに転用したものをイントラネットという。

# IPアドレス  
IPアドレスとは、TCP/IPのネットワークに繋がっているコンピューターやネットワーク機器の管理にネットワークの住所みたいな番号で表したものである。
・グローバルIPアドレス  
どのネットワークか示したものであり、一意にするために地域ごとにNIC(Network Information Center)という民間の非営利機関に管理されたインターネット  
世界で使用されるIPアドレスのことである。外のネットワークとやり取りに必要である。  
・プライベートIPアドレス  
どのコンピューターか示したものであり、システム管理者が割り当てが自由にできる企業内LANで使用できるIPアドレスのことである。

# IPアドレスの構成  
IPアドレスは、ネットワークアドレスとホストアドレスで構成され、◯◯◯.◯◯◯.◯.◯のように数字で表されるものである。使用するネットワークの規模によってクラスA,B,C  
で分かれ、32ビットの内ネットワークアドレスに割り振れるビット数によってホスト数が変わる。

# サブネットマスク  
サブネットマスクとは、TCP/IPネットワークなどを複数の小さいネットワークに分割することであり、IPアドレスのビット列で表す。一つのネットワークに多くのホストを  
まとめると通信効率が悪くなることもあるので分割することもある。

# DHCP  
IPアドレスの割り当てなどのネットワークの設定作業の自動化ができるプロトコルであり、LANに繋ぐコンピューターの数が多くなった時に手間が省ける自動設定の最適の仕組みである。

# NATとIPマスカレード  
NATはグローバルIPアドレスとプライベートIPアドレスを1対1で結び変換を行う技術である。IPマスカレードは、グローバルIPアドレスに複数のプライベートIPアドレスを1対多で結び  
変換を行う技術であり、変換時にポート番号も書き換えるので一つのグローバルIPアドレスで複数のコンピューターが同時にインターネットに接続できる。

# DNS　　
DNSはドメイン名とIPアドレスを関連づけて管理しているシステムである。DNSサーバーに対してwww.◯◯.co.jpのIPアドレス、IPアドレスが◯◯のドメイン名と問い合わせると対応した  
ものが返ってくる。

# IP6
IPアドレスを128ビットの数値で表現する後継規格である。IPアドレスを無限に近い状態で割り当てれるため多くのIoTデバイスが繋がる大量のIPアドレスが必要な時代に対応できます。

# プロトコルとサービス  
ネットワークサービスはプロトコルの処理サーバーで提供している。  
・HTTP  
webプラウザを用いてHTMLで記述した文書の受信など、webページの転送に利用するプロトコルである。  
・FTP  
インターネット上のサーバーにファイルアップロードやサーバーからファイルダウンロードをするファイル転送サービスに利用するプロトコルである。  
・Telnet  
他のコンピューターにログインして遠隔操作する際に使用するプロトコルである。  
・SMTP  
電子メールの送信やサーバー間での送受信で利用されるメールの配送部分のプロトコルである。  
・POP  
受信したメールを取り出すときに利用するメールの受信部分のプロトコルである。  
・NTP  
コンピューターの時刻合わせに利用されるプロトコルである。  


# ポート番号  
どのサーバープログラム(通信相手)の宛先である接続口を示した番号のことである。０〜65,535。  
IPアドレスでパケットの宛先のコンピューターを識別し、ポート番号でコンピューター内のサーバープログラムの宛先を特定できる。

# IETF  
インターネット技術を標準化を推進する任意団体のことである。RFCという名前で文書化され公開されている。  

# WWW  
world wide web の略でインターネットで蜘蛛の巣に例えたドキュメント間をリンクが張り巡らされている網目状の構造であるサービス名のことである。

# URLの形式  
http://www.◯◯.co.jp/app/index.html  
http:→プロトコル名  
www.◯◯.co.jp→ドメイン名  
app→ディレクトリ名  
index.html→ファイル名  
httpというプロトコルを使用して◯◯.co.jpというネットワークのwwwというwebサーバが公開するappディレクトリ下のindex.htmlファイルをやり取りするという意味。

# SEO(Seach Engine Optimnization)  
検索エンジンがwebサイトのクセを分析し、最適化によるサイト構成が行われ検索結果が上位のサイトが表示されるようになる取り組みのことである。検索エンジンの最適化。  
この検索結果の上位に詐欺サイトや不正なサイトが表示されるように悪用した攻撃手法をSEOポイズニングという。

# CGM(Consumer Generated Media)  
消費者により生成されたメディアという意味であり、レシピ投稿サイトやブログ、SNSのことである。

# MIME(Multipurpose Internet Mail Extensions)
インターネットで電子メールで多様なファイル形式を扱えるようにした規格である。電子メールで本文に画像や音声など添付するときに使われる。

# メールアドレスの形式  
hrjej@jooo.co.jp  
hrjej→ユーザー名 名前にあたる 
jooo.co.jp→ドメイン名　住所にあたる

# メールの宛先  
TO：送信したい相手のメールアドレスを記載してる宛先  
CC:TOの○○アドレス宛の内容をコピーで送り、確認してほしい方へのアドレスを記載する所。  
BCC:TOとCC宛の方に伏せた状態でコピーを送る確認だけして欲しい方のアドレスを記載する所。  
同報メール:複数の宛先に同じメールをまとめて送信したい時のやり方。

# SMTP  
電子メール送信のためのプロトコルであり、ポストから相手の郵便受けに届けるまでの役割である。  
SMTPサーバーは、送信されたメールアドレスを受け付け宛先のアドレスを見て相手のメールサーバーにメールを配送する役割である。

# POP  
電子メールを受信するために使用されるプロトコルであり、郵便受けからメールを取り出す役割である。  
POPサーバーは、POPに対応したサーバーであり、POPクライアント(電子メールなど)から受信メールをくださいと要求された時にその　　
ユーザーのメールボックスからメールを取り出して渡す役割である。

# IMAP  
POPと同じ電子メールを受信する時に使用されるプロトコルである。POPとの違いは、メールの実態をサーバー上に実態を残したまま管理する  
ことができる役割である。  

# MIME  
電子メールのASCII文字以外に画像データや複数バイト文字のファイルを添付を行えるようにした拡張規格のことである。  

# 電子メールのメッセージ形式  
・テキスト形式:文字だけで使用  
・HTML方式:HTMLで作成され、タグを使うことで装飾や画像の埋め込みができる。  

# 機種依存文字  
特定のコンピューターでしか表示できない文字のことである。文字化けが起こる時はそれにあたる。半角カナはなりやすい。

# ビックデータ  
情報通信技術の高度化により蓄積していく膨大なデータのこと。  
・Variety(多様性)：整形された構造化データだけでなく非構造のデータである画像や音声、動画など。  
・Velocity(頻度)：高頻度で変わり取得するデータ  
・Volume(量)：膨大な量  
データマイニング  
大量のデータを統計的、数学的手法で分析して法則や因果関係を見つけ出す技術のことである。

# 機械学習  
AIを実現するための中核技術のことである。  
学習方法が３つある。  
・教師がいる学習法  
データと正解をセットで与えたり、誤りを指摘する方法である。  
・教師がいない方法  
データのみを与えてたくさんのデータから法則性を導き、データの集約や分類したりする方法である。  
・強化学習  
個々の行動を点数化し、最も高い点数になる方を選択する学習方法である。  

# 深層学習（ディープランニング）  
機械学習を発展させたもので、人間の脳神経回路のモデルに多くのデータを解析させ特徴を抽出し自動的に学習することである。  

# ISMS(情報セキュリティマネジメントシステム)  
組織が情報資産を適切に管理し、守る仕組みのことである。  
・ISMS適合性評価制度  
組織で構築されたISMSが規格に基づいて適切に構築・運用されているか証明するための制度である。  

# 情報セキュリティ七要素   
・機密性  許可したもののみアクセスできるようにして情報漏洩しない
・完全性  書き換えられないように完全
・可用性　使いたい時に情報資産が使える  
上記三つで安全性や利便性のバランスをとっている。  
・真正性　エンティティの主張通り正しい  
・責任追跡性  いつ何がどこで起きたか追跡できる  
・否認防止　エンティティの主張による事象や説明  
・信頼性

# セキュリティポリシー  
組織の経営者が企業としてセキュリティの取り組みを明文化し、従業員や関連する外部関係者に周知、徹底をするものである。  
構造  
・基本方針・対策基準・実施手順  

# 情報セキュリティの目的  
情報資産をリスクから守ること  
リスクとは、組織の情報資産の脆弱性を突き、脅威をより損害を受ける可能性のことである。  

# リスクマネジメント  
全社的に業務の一環として不確定要素を予測して分析し、事前に対策を講じることである。  
・リスクマネジメントのプロセス
リスク基準の制定→リスク特定→リスク分析→リスク評価→リスク対策

# リスク対策  
・リスクコントロール  
損害の発生防止や発生した損害の拡大防止をすること  
・リスクファイナンシング  
損害に対する補填としての財務的な備えのこと    

# リスク受容基準  
組織でリスクに対応するべきか否かを判断するための基準のことである。全部対応は難しいため。  

# 不正のトライアングル  
不正が起こりうる条件を提唱したものであり、機会、動機やプレッシャー、姿勢や正当化が揃った時に不正が起こるということ。  
ex) 不正が起こりそうな環境であったり、ノルマによるプレッシャー、不正の自己解釈による正当化など。  

# JPCERT/CC(コーディネーションセンター)  
インターネットを介して不正な侵入や妨害といったインシデントに中立的な立場で対応する非営利団体のことである。  
・CSIRTマニュアル  
JPCERT/CCによる組織的に情報セキュリティ問題に取り組む体制を支援するための資料のことである。  

# 個人情報保護法  
事業者が適切に個人情報を扱うルールを定めたものであり、消費者が不利益を受けないようにする。  

# プライバシーマーク制度  
適切に個人情報の保護の整備ができている事業者の認定制度のことである。  

# ソーシャルエンジニアリング  
コンピューターのシステムとは関係なところで人の心理的不注意を利用して情報資産を盗む行為のことである。  パスワード覗く、なりすまして聞き出したり  

# 不正アクセスの手法  
・パスワードリスト攻撃  
どこからか入手したIDとパスワードを別のサイトでログインに使用する手法。  
・ブルートフォース攻撃  
特定のIDに対して使える文字列のパスワードを片っ端から試す手法。 
・リバースブルートフォース攻撃  
ブルートフォース攻撃の逆で特定のパスワードに対して使える文字列のIDを片っ端から試す手法。　　
・レインボー攻撃  
ハッシュ値から元の文字列のパスワードを解析する手法。ハッシュ値とは、サーバーにおいてパスワードをハッシュ化して変換された文字列のこと。  
・SQLインジェクション  
データベースに問い合わせる時に入力値に悪意のある問い合わせやSQl文を埋め込むことにより入力値の条件を変えたりしてしまいデータの不正取得や改ざん  
する手法。  
・DNSキャッシュポイズニング  
webサイトにおける使用したデータを一時保持するキャッシュ機能を悪用してキャッシュを改ざんでドメインを変え偽装サイトに誘導する手法のことである。  
・DOS攻撃  
電子メールやリクエストを大量に送りサービスを提供不可にする手法のこと。  
・DDOS攻撃  
DOS攻撃を複数のパソコンで行う手法のことである。  
・フィッシング攻撃  
金融機関などを装って偽サイトに誘導し不正に暗証番号や個人情報を取得する手法のことである。  

# CAPTCHE  
機械による自動入力での不正ログインを防止するためにコンピューターに読めない文字を入力することで人間が入力していると判断するための技術のことである。  
チケットの買い占めが機械による自動入力の不正ログインにあたる。

# コンピュータウイルス  
・狭義のウイルス  
プログラムに寄生して機能させなくする。  
・マクロウイルス  
マクロ機能を悪用したものであり、表計算ソフトやワープロソフトに寄生する感染手法である。  
・ワーム  
自身で複製をして生成してネットワークを介してコンピューター間で感染を広げる手法であり、容易に作成できることから種類が多い。  
・トロイの木馬  
適性なプログラムであるかのように見せかけユーザーに実行を促し、裏で不正なデータコピーや処理を行う手法。  

# マルウェア  
コンピューターウイルスを含む悪意あるソフトウェアの全般を表すこと。  
・スパイウェア  
情報収集を目的としたプログラムであり、コンピューターのユーザーの個人情報を収集して外部に送信すること。  
・ボット  
感染した第三者のコンピューターをボット作成者の指示通りに動かすようにするもののこと。  
・ランサムウェア  
暗号化などでファイルを使えなくした上でファイルを元に戻すことと引き換えに身代金を要求するマルウェアである。

# ウイルス定義ファイル  
ウイルス対策ソフトで多種多様のウイルスを検知するために必要な既知ウイルスの特徴が書かれているファイルのことである。  
・ビヘイビア法  
ウイルス定義ファイルだけでは検知できない時に使用し、実行中のプログラムを監視して不審な動きがないか検査する手法のことである。

# ファイヤウォール  
LANの外と中を区切る壁のことである。  
・パケットフィルタリング  
パケットのヘッダー情報の送信元や宛先のIPアドレスを見て通過の有無を判定する機能である。どのサービスは通過されるか決めている。  
・アプリケーションゲートウェイ  
LANの中と外の間に位置していて外部とやり取りを代行して行うサーバー機能であり、プロキシサーバーともいう。外部からは、プロキシサーバーしか  
見えないためLAN内部のコンピューターへの不正アクセスを防ぐことができる。  
・ペネトレーションテスト  
既知の手法で実際に攻撃を行い、セキュリティホールや設定ミスの脆弱性の有無を確認するテストのことである。侵入されることでどうなるかと検証になる。  
・DMZ　　
非武装地帯という意味であり、外部から社内ネットワークに侵入させないために隔離的に設けた中間的な領域のことである。

# 通信経路における危険と対処  
・主な危険例３つ
盗聴　改ざん　なりすまし  
・暗号化  
データを第三者にわからないように変換すること。  
・復号  
暗号化されたデータを元に戻すこと。  
・鍵  
暗号化、復号に使われるデータのこと。  
・共通鍵暗号方式  
データの送信側(暗号化する側)と受信側(復号する側)が同じ鍵を使う暗号方式である。鍵が第三者にわかってしまうと意味がないので秘密にしないといけないことから  
秘密鍵暗号方式ともいう。  
・公開鍵暗号方式  
公開鍵というものがある。送信側と受信側で使われる鍵が異なる方式である。受信側が公開鍵と秘密鍵を用意し、送信側に暗号化にはこの鍵を使うようにと公開鍵を渡す。  
受信側は秘密鍵を用いて復号を行う。  
・デジタル署名  
暗号化されたデータが途中で改ざんされていないか、誰からの送信か確認できるように署名や捺印できる機能のことである。  
・デジタル署名における公開鍵暗号方式の役割  
誰の署名か検証して署名として機能するために公開鍵暗号方式が使われている。  
秘密鍵が自分しか知らないものなので自分の証明に使用でき、署名の作成に使えることから署名鍵と呼ばれる。  
公開鍵が誰でも使用できるものなのでペアとなる鍵の証明に使用でき、署名の検証に使えわれることから検証鍵と呼ばれる。  
・デジタルダイジェスト  
デジタルデータをハッシュ化して固定長のビット列というハッシュ値にすることである。ハッシュ値にしてから署名鍵で署名化することで公開鍵暗号方式データそのままでやるより  
処理が早い。  

# 認証局（CA　Certificate Authority）  
公開鍵でなりすましていない本人であると証明する機構のことである。  

# 公開鍵基盤  
認証局と公開鍵暗号技術を用いて安全な通信を保証する仕組みのことである。 

# 暗号化プロトコル  
通信の危険に対して暗号化技術を用いてどの手順で暗号通信をするか定めたものである。  
・SSL(Secure Sockets Layer)  
お互いの認証とデータの暗号化で安全な通信のやり取りに用いる代表的なプロトコルである。認証、データの暗号化。  
・TLS(Tlansport Layer Security)  
SSLの後継のセキュリティプロトコルである。認証、改ざん検知、暗号化通信。
・HTTPS  
サーバーとクライアントでやり取りするプロトコルであるHTTPにSSLの暗号化通信を付加したプロトコルのことである。  

# VPN  
ネットワークに仮想的専用線を作って拠点間を安全に接続する技術のことである。
・インターネットVPN　　
やり取りの接続口にそれぞれVPN装置を設置する。その装置が送信側で暗号化してからデータを送り、受け取り側は、暗号化を解除してから内部ネットワークに転送している。  
ここでIPsecという安全に通信を行えるプロトコルが使われる。  
※IPプロトコル(ネットワークからネットワークにパケットを運び相手に届けるプロトコル) + sec(暗号化や認証機能を持たせる)。  

# ソフトウェアライフサイクル  
企画→要件定義→開発→運用→保守のプロセスを通して役割を終えて破棄するまでのサイクルのことである。  
・調達  
システムベンダーに発注することである。  
情報提供依頼(情報提供依頼書RFI)→提案依頼書(RFP)の作成と提出→提案書の受け取り→見積書の受け取り→システムベンダーの選定(複数依頼した中で一番条件が合うベンダー)  

# 開発の流れ  
要件定義→システム設計→プログラミング→テスト(検証)→導入・運用  
・要件定義  
お客様のヒアリングで何の機能が求められているか明らかにする工程である。  
機能要件はお客様から得られる要求事項のことであり、非機能要件は機能要件以外のことでシステム基盤側の要件のことである。  
・システム設計  
要件定義の内容をシステム仕様に落とし込む工程である。１から４の順で行う。  
 1外部設計  
利用者側から見える部分の設計であり、ユーザーインターフェイスで手で触れられる部分の設計のこと。  
 2内部設計  
利用者から見えない部分(開発者側の視点)の設計であり、外部設計を実現するための実装方法や物理データの設計を行う。  
 3プログラミング設計  
コーディングの基盤部分の設計であり、どのように作るかの視点である。  
・プログラミング  
プログラムをモジュール単位でプログラミング言語を用いて作成する工程である。  
・テスト  
プログラミングにミスがないか検証する工程である。1から４の順で行う。  
 1単体テスト  
モジュール単位で動作確認するテストである。  
 2結合テスト  
モジュールを結合した状態で動作確認するテストのことである。  
 3システムテスト  
システム全体を動かして動作確認をするテストである。  
 4運用テスト  
実際の運用と同じ条件下で動作確認をするテストである。  

# 開発手法  
・ウォーターフォールモデル  
１つの工程を完了させてから次へ順に進めていく手法である。管理しやすく大規模開発に向いているが確認が最終段階でしかできないため１つ前の工程に戻って直すことができない。  
・プロトタイピングモデル  
開発の初期段階で試作品を作成し利用者に確認してもらい開発側とのズレを防ぐ手法である。要件定義の次に試作品を見せる。試作品の段階で要望が増えたりするので大規模開発には  
向いていない。  
・スパイラルモデル  
システムを複数のサブモデルに分割してそれぞれのシステムごとに開発を進めていく手法である。個々の開発はウォーターフォールモデルで行う。プロトタイプとして見せれる。  
・アジャイル  
スパイラルモデルの派生型で週単位のように短い反復単位で迅速に開発を行う手法の総称である。１つの反復で１つの機能を開発し反復が終わるたびに追加実装としてソフトウェアの  
リリースを行う。  
・アジャイルの代表的な手法であるXP  
少人数に適していて仕様変更に柔軟である。仕様変更を決めてから出なくて良い開発。開発のプラクティスがテスト駆動開発、ペアプログラミング、リファクタリング、ソースコード  
の共有所有、継続的インテグレーション、YAGNI  
・リバースエンジニアリング  
既存のソフトウェアの動作を解析してプログラムの仕様やソースコードをを導きだし、すでにあるソフトウェアで再利用して新規開発を助ける手法である。  
・フォワードエンジニアリング  
リバースエンジニアリングで得た仕様を元に新しいソフトウェアを開発する手法である。  
・マッシュアップ  
公開している複数のサービスを組み合わせて新しいサービスを作り出す手法である。webサービス構築でよく使われる。  

# 業務のモデル化  
・DFD(Date Flow Datagram)  
データの流れを図で表したもの。  
・E-R図  
実体と実体間の関連という概念で図に表したもの。実体がユーザーと投稿物なら実体間の関連が１対多で→で表したもの。  

# ユーザーインタフェース(UI) 
システムと利用者のやりとりを仲介する部分で人が触れる部分である。  
・CUI  
文字を入力することで命令を出す文字ベースの方式のインタフェースである。  
・GUI  
マウスの操作で命令できるグラフィカルなユーザーインタフェースのことである。  

# GUIの部品  
・メニューバー  
アプリケーション操作に必要な項目が書かれているメニューバー  
・ラジオボタン  
複数の選択肢から１つを選択させたい時のボタン
・プルダウンメニュー  
クリックすると下に垂れ下がるメニューである。
・チェックボックス  
特定の項目におけるオンオフや複数選択肢にチェックをつけないといけない時に使われるチェックをつける箱。
・テキストボックス  
文字の入力欄で短長方形上の箱である。  

# ユーザーインタフェースを使いやすくするための留意点  
・重要な部分を赤文字にするなど色づかいにルールを設ける。  
・入力は自然な流れで左から右、上から下のようにする。  
・入力ミスが出た時にエラーメッセージを出して原因や対処法をわかりやすく表示する。  
・画面ごとの入力パターンやレイアウトを共通化して見やすくする。  
・選択肢が多い場合、グループ分けや階層化して選択しやすくする。   
・不慣れな利用者のためにヘルプのようなガイダンス機能を設ける。  

# 帳票設計時の留意点  
・各帳票のレイアウトを共通化する。  
・関連する内容は、隣接する場所に配置する。  
・記載内容は最小限にして見やすくする。  

# コード設計  
一度決めると変更が困難なため先々を見越した上で桁数を決めたりしないといけない。
・何をコード化するのか  
・数字の規則はどのようにするのか  
・桁数はどうするか  

# チェックディジット  
誤入力判定をするためにコードに付加されている数字のことである。例えば全部で６桁なら一番右の桁数字が付加されたものになる。左の５桁の合計＝右の１桁のようにして  
付加数字としているのもある。  

# 他の入力ミス判定方法  
チェックディジット以外の方法  
・ニューメリックチェック  
数字しか使えないデータに扱えない文字が入っていないかチェックする方法。  
・シーケンスチェック  
対象のデータが一定の順序で並んでいるかチェックする方法。  
・リミットチェック  
データが適正な範囲内にあるかをチェックする方法。A<X<Bのイメージ。  
・フォーマットチェック  
データの形式が正しいかチェックする方法。日付の◯◯◯◯/◯◯/◯◯の形式になっているかなど。  
・照合チェック  
登録されているコードであるか照合する方法。  
・論理チェック  
売り上げ量と合計金額といった関係など、対となる値に矛盾が生じないかチェックする方法。  
・重複チェック  
同じコードが重複して登録されていないかチェックする方法。 

# テスト  
・単体テスト  
各モジュールごとに誤りがないか検証を行うテストである。  
・結合テスト  
モジュールを繋ぎ合わせて検証を行うテストであり、モジュール間のインタフェースが正常に機能している調べる。  
・システムテスト  
システム全体のテストをする。  

# 単体テストのモジュール検証の手法  
・ブラックボックステスト  
モジュール内部を意識しないで入力に対して出力が仕様通りに行われるか検証する手法。  
・ホワイトボックステスト  
逆にモジュールの内部構造が正しく作られているか検証する手法。  

# テストデータの決め事  
・同値分割  
それぞれの範囲を種類ごとに分けてそれぞれの範囲内から代表的数値を出してテストデータに用いること。  
・限界値分析  
それぞれの種類ごとに分けた範囲同士の境界面の値をテストデータに用いること。   

# 結合テストモジュール間のインタフェースを検証する手法  
・トップダウンテスト  
上位モジュールから下に検証を進める手法である。上位モジュールとは個々のモジュール用いて複雑な機能を持ったモジュールのこと。下位モジュールは、まだテストされていないために仮に  
スタブという名称でくっつけておく。  
・ボトムアップテスト  
逆に下位モジュールからテストしていく手法である。上位モジュールはまだテストがされていないのでドライブと呼ばれるモジュールをくっつける。  
・折衷テスト  
トップダウンテストとボトムアップテストを組み合わせてたテスト手法である。   
・ビックバンテスト  
全てのモジュールを一気に繋げてテストする手法である。  

# リグレッションテスト  
修正した箇所の修正内容によって今まで正常に機能していた箇所に悪影響を与えていないか確認するテストである。  

# バグ管理図  
縦軸が累積バグ件数、横軸がテスト項目消化件数で表した図である。信頼度成長曲線よりであるほど品質が高く、テストしっかりなされているものである。  

# マネジメント  
・PMBOK(Project Management Body of Knowledge プロジェクトマネジメントの知識体系)  
プロジェクトマネジメントの知識体系のことであり、国際的に標準とされている。  
・WBS(Work Breakdown Structure　作業分解構成図)  
プロジェクトに必要な作業や成果物を細かくタスク分けして階層化した図で表したものである。卵焼きを作るの次の階層は→材料用意、調理するの２つに分かれて次の階層として３つの目の階層に分かれていく。  

# 見積もり手法  
・プログラムステップ法  
ソースコードの桁数で開発コストを算出する手法である。  
・ファンクションポイント法  
利用者から見える部分の機能の数や難易度によって開発コストを算出する手法である。

# ITサービスマネジメント  
顧客の要求を満たすITサービスを効果的に提供できるように体系的に管理する手法である。  
・ITIL  
ITサービスを提供するにあたっての管理・運用規則といった最も効率的な方法が体系的にまとめられているガイドラインである。２つにまとめられている。    
 ・サービスサポート:ITサービスの日々の運用に関する作業をまとめたもの。 
 ・サービスデリバリー：長期的な視点でITサービスの計画や改善を図ること。  

# サービスレベルアグリーメント(SLA)  
サービスレベル合意書といい、利用者と提供者でどのようなサービスをどのような品質で提供するか事前に明文化したもの。  

# サービスレベルマネジメント  
設定目標の達成のためにPDCAサイクルを構築しサービス水準を維持・向上に努めること。  

# サービスサポートの１機能と５つの業務プロセス  
・サービスデスク(機能）  
利用者と提供者の窓口  
・インシデント管理  
発生したインシデントに対してできる限り迅速にサービス運用を回復してビジネスへの影響にを最小限にする。  
・問題管理  
インシデントの原因を特定して事業への悪影響を最小限にし再発防止をする。  
・構成管理  
構成管理データベースを用いてITサービスに必要な構成アイテムを把握し、各プロセスに効果的な情報を提供する。  
・変更管理  
変更に伴う影響を検証して評価し認可か却下を出す。  
・リリース管理  
承認が出たものを適切な場所、適切な時期にリリースする。  

# サービスデリバリー５つの業務プロセス  
・サービスレベル管理  
利用者と提供者でSLAを結び、PDCAサイクルでサービスの維持・向上を図る。モニタリング結果に応じてSLAやプロセスを見直す。  
・キャパシティ管理  
システムの容量や能力のキャパシティを管理し、最適なコストで現在や将来での需要をに満たすのを見越して備えること。  
・可用性管理  
利用者がサービス利用したい時利用できるようにITサービスの維持・管理をする。  
・ITサービス継続性管理  
顧客と合意したサービスの継続をあらゆる状況下でできるようにする。災害が起きた時など迅速に復旧をし事業継続のための計画立案や試験を行う。  
・ITサービス財務管理  
コスト予測と発生したコストの計算や課金管理を行う。  

# BCP（事業継続計画）  
災害で事業が停止してもできる限り迅速に復旧させるための方針や体制、手順を示した計画である。   
・復旧目標  
 ・目標復旧レベル　・目標復旧時間　・目標復旧時点  

# ファシリティマネジメント  
ITシステムの施設管理や改善をする取り組み  
・UPS  
停電対策で設置される機器で無停電電源装置、安全にデータを保存してシャットダウンをすることができる時間は確保できる。  

# ITガバナンス  
ITシステムを適切に管理・運用するための方法や体制のこと。  

# システム監査人  
独立していてシステムの監査を行う人のこと。  
監査計画の立案→予備調査→本調査→評価・結論の順で監査計画を行う。  

# 可監査性  
処理正当性や内部統制を監査やレビューできるシステムが設計・運用されていること。すぐに記録や資料を見せたりできるなど。

# 監査証跡  
システムの事象発生から最終結果の一連を時系列で追跡できる仕組みのこと。  
・監査証拠  
システム監査人が監査意見を実証するのに必要な証拠である。監査証跡で証拠を出す。  
保証意見と助言意見を言うことになっている。  
・フォローアップ  
システム監査人が改善指導することである。  

# プログラミング言語  
機械語を人間が読み取れるようにしたコンピューターに作業指示をする言葉のこと。  
・C言語  
OSやアプリケーションなど広範囲で用いられる言語である。ハードウェアに近いレベルで記述ができてしまう何でもありな柔軟性を持つ。  
・COBOL  
事務処理用で使われていた言語である。新しい開発では使われないが、汎用コンピューターの改修で使われることが多い。  
・Java  
Webサイトやネットワークを利用した大規模システムで使われる。C言語に似ていて特定の機種やOS、コンピューターの種類に依存しないJava仮想マシンという環境  
を用いて動かすことができる。  
・Basic  
初心者向けの古い言語である。簡便な記述で書いたらすぐに実行して動作確認ができるインタプリタ式であるので途中で動作確認しながら開発に向いている。  
・Javascript  
動的なWebコンテンツ作成に使われる言語である。インタプリタ方式で簡便な記述でWebページに組み込まれるスクリプト言語であり、クライアント側で動作する。  
・Python  
機械学習開発に強い言語である。インタプリタ方式のスクリプト言語で言語仕様がシンプルで学びやすく、AI開発需要が高くなり注目を浴びている。  

# 言語プロセッサー  
プログラミング言語から機械語に翻訳するといった作業プログラムの総称である。  

# 翻訳手法  
・インタプリタ方式  
ソースコードに書かれた内容を１つずつ逐一翻訳する方式である。動作確認をしながら開発できる。  
・コンパイラ方式  
ソースコードの内容を最初に全部翻訳する方式である。ソースコード全体をの解釈ができるので効率的に翻訳できる反面途中までの確認動作をすることができない。  

# オブジェクト指向プログラミング  
処理対象をオブジェクト概念で捉え部品かしていくことで全体を構成していく方法である。  
・オブジェクト  
データとデータの処理の記述（メソッド）をまとめたものである。  
・クラス  
オブジェクトの性質を抽象的に定義づけたものである。車というクラスみたいなもの。  
・変数  
プログラミングでの記述で一時的に使われる値を入れる場所のことで入れ物のようなものである。  
・代入  
変数に値を格納することである。  

# 構造化プログラミング  
プログラミングを機能単位の部品にわけて組み合わせ全体を作っていく考え方である。  
・制御構造  
　・順次構造:上から順に　・選択構造：分岐　・繰り返し構造：ある条件下の繰り返し  

# if文  
略  

# アルゴリズム  
効率的な手順や機能を満たすように考えた作業手順のことである。  
・フローチャート  
アルゴリズムをわかりやすく図にしたものである。  

# 代表的なアルゴリズム  
・探索のアルゴリズム  
複数のデータの中から目的のデータを探索するアルゴリズムである。  
二分探索法とは、昇順、降順で並んでる時に効率よく見つける探索できる方法である。  
・整列のアルゴリズム  
データを昇順降順に並び替えるアルゴリズムである。　　
バブルソートとは、例えば昇順なら４つ数字が並んでいたら一番左の数字と隣を比較して右の数字が小さければ入れ替える。その次に一個ずれて同じように  
比較して入れ替えるか確認をする作業を繰り返す。小さい順になって入れ替える必要がなくなったら終わり。  

# 配列  
メモリ上に連続した領域にデータを並べて管理すること。  
・添字  
配列の中の何番目のデータか指定しいる番号のこと。例書き方[1]。  

# リスト  
データとデータを数珠繋ぎにして管理したものである。  
・ポインタ  
メモリ上の位置を表す番号でリストのデータ１つごとにセットでついている。次のデータが保管されている位置を示している。このポインタを書き換えれば  
リストは繋ぎかえができる。  

# ツリー構造  
ツリー上に分岐して階層構造の中にデータを格納して管理している構造である。  
・節  
構造内の分岐している箇所のこと。  

# キュー  
データを格納した順に処理を行う先入先出の方式のデータ構造である。最初に車に乗った人が先に降りるみたいな。  

# スタック  
キューとは逆で最後にデータを格納した順に処理を行う後入れ先だし方式のデータ構造である。最後に乗った人が先に降りるみたいな。  

# コンピューターの働く形  
・集中処理  
セキュリティの確保や運用管理がしやすいが、システム拡張が大変でホストコンピューターが故障すると全体的に故障になってしまう形。  
・分散処理  
システム拡張がしやすく、どこか故障しても他に影響しないが、セキュリティの確保と運用管理が大変である形。  
・クライアントサーバーシステム  
上記２つの処理のいいとこ取りで基本分散処理の形。  

# クライアントサーバーサービス種類  
・シンクライアント  
サーバ側に依存度を高くしたクライアントサーバーサービスである。クライアント側が入力と表示部分のみ対応し、サーバー側が情報処理や保管をしている。  
・ピアツーピア  
ネットワーク上で強調動作するコンピューター同士が対等でやり取りするサーバーの一元的管理する立場がいらない分散型システムである。  

# オンライントランザクション処理  
要求に対してすぐに処理を行い、結果が反映されるものである。リアルタイムで反映が必要な場合。  

# バッチ処理  
リアルタイムで処理しなくてよくて一定期間ごとにまとめて処理を行うものである。  

# クラスタリングシステム  
複数のコンピューターをネットワークで結合し構築するシステムである。　　

# システムの処理能力を向上させるアプローチ  
・スケールアップ  
サーバーを性能が高いものに交換して処理能力向上を図る。  
・スケールアウト  
サーバーの台数を増やすことで処理能力向上を図る。  

# グリットコンピューティング  
インターネットなどのネットワーク上にある複数のプロセッサーに処理を分散して大規模な処理を行う方式である。  

# SOA（サービス指向アーキテクチャ）  
大きい１つのシステムにせず個々の機能をサービスという部品化をしてそれらを組み合わせてシステムを構築するという考え方である。  

# システムの性能指標  
・ベンチマークテスト  
性能測定用ソフトウェアを使ってシステムの各処理性能を数値化するものであり、傾向をつかむ目安である。  
・スループット  
単位時間あたりに処理できる仕事量を表している。スループットは、オペレーターの待ちや処理待ちで下がっていく。  
・レスポンスタイム  
コンピューターの一連の処理依頼をし終わってからそれに対する応答が始まるまでの時間のことである。  
・ターンアラウンドタイム  
コンピューターに依頼を始めてからそれに対する応答がし終わるまでの時間のことである。一連の全ての時間のこと。  
・デュアルシステム  
コストはかかるが２組の同じシステムを使って信頼性を高めるシステムであり、片方が故障したらもう片方で処理を継続できる。  
・ディプレックスシステム  
２組のシステムを使うが片方を通常運転でメインとして使い、もう片方はサブとして待機しているシステムである。メインが故障した時にサブが切り替わって動く。  
・ホットスタンバイ  
いつでも切り替われるようにサブがプログラムを起動して待機していてメインが故障した時にすぐに切り替われる。  
・コールドスタンバイ  
サブが切り替わりに入るまでに別の作業していたり電源オフの状態で待機していてメインが故障した時に切り替わり入る。切り替わりに時間がかかる。  

# 稼働率  
トラブルがない無事に使えていた期間を割合で表したものである。  
・平均故障間隔  
故障期間とは、故障が起きた期間と次の故障期間の間を表したもので要するに故障していない時間のことである。これらを平均して大体この間隔故障が起こる目安に使われる指標である。  
・平均修理時間   
修理に必要な時間で要するに稼働していない時間である。これらを平均して大体復旧するのにこのぐらいの時間がかかるという目安に使われる指標値である。  
・システムの稼働率  
システムが運転を始めてから全運転時間の中でどのくらい正常に運転できているか割合で表したものである。  
平均故障間隔/(平均故障間隔＋平均修理時間)  
・直列での稼働率 
稼働率A(システムA)と稼働率B(システムB)が直列でつながっているとする。　　
稼働率A×稼働率B  
・並列での稼働率  
稼働率A(システムA)と稼働率B(システムB)が平列でつながっているとする。  
故障率 = 1 - 稼働率　　全体の故障率 = 故障率A × 故障率B　　並列のシステムの稼働率 = 1 - 全体の故障率  

# フォールトトレラント  
壊れても大丈夫なように対策を図るという考え方である。  
・フォールセーフ  
故障した時に安全性が確保された形で壊れるように仕向けた方法である。ストーブが倒れたら消えるようになっているなど。  
・フォールソフト  
故障した時にシステム全体が停止しないように機能の一部を切り離して継続する方法である。  
・フールプルーフ  
不慣れな人が誤操作しないようにあらかじめ安全対策が組まれている方法である。電子レンジがあっけぱなしで動かないようになっているなど。  

# バスタブ曲線  
故障率を縦軸、使用した時間を横軸にして表したバスタブ状の曲線グラフである。  
・初期故障期間：製造物の欠陥などで高めの故障率から始まり時間が経つにつれて下がっていく。  
・偶発故障期間：故障率が一定で安定している期間。  
・摩耗故障期間：ライフサイクルの末期で製造物の寿命により故障率が上昇していく期間。  

# TCO  
初期コストと必要な運用維持コストをまとめたものである。初期コストが安く受注したが運用コストがかなりかかってしまう事例があったことから。  

# バックアップ  
定期的に行うこと。バックアップの媒体をわけること。業務処理中にしないこと。  
・フルバックアップ  
保存されている全部のデータをバックアップすること。  
・差分バックアップ  
前回のフルバックアップ以降から作成、変更されたファイルだけをバックアップすること。  
・増分バックアップ  
バックアップの種類に関わらず前回のバックアップ以外に作成、変更されたファイルだけをバックアップすること。  




用語  
・GPU(Graphics processing unit 画像処理装置)  
PC等で画像処理を専門とするハードウェア部品で動画再生や3Dレンダリングといった膨大な演算が必要な処理にCPUの補助演算装置として機能する。  
科学シュミレーションや機械学習でも利用。
・VGA(Video Graphics array)  
640×480ピクセルの画素数のディスプレイを表し、それにアナログRGB信号を出力するコネクタ(両サイドにピンがついた接続端子)を表す。
・LPWA(Low Power Wide Area)  
省電力・広範囲を特徴とする無線通信規格の総称である。
・MDM(Mobile Device Management)  
組織が従業員に貸与し、業務で使用しているスマートフォンを遠隔で一元管理する仕組みのこと。  
・SDN(software Defined Networking)  
ソフトウェア制御による動的で柔軟なネットワークを作り上げるための技術の総称のこと。  
・SFA(Sales Force Automation)
インターネットやモバイル端末のICT技術を使って営業活動を支援・効率化する仕組みのこと。
・トラックバック  
別の利用者のブログ記事へ(引用元)のリンクを貼ると、リンクが貼られた側(引用元)に通知がいく仕組みのこと。  
・RSS(Rich Site Summary)  
Webサイトの新着・更新情報を簡潔に配信する仕組みであり、登録したWebサイトの新規記事や更新情報などを配信するシステムのこと。
・DEI(Divercity多様性 Equity公平性 inclution包括性)  
人種や性別の違いからの価値観など全ての人々がフェアな扱いで尊重し方針決定に完全に参加できる仕組み。  
・クロスサイトスクリプティング(XSS)  
動的なwebページを生成するアプリケーションにセキュリティの不備を突いて悪質なスクリプトを混入させ攻撃者の仕掛けた操作を実行や  
別サイトを介してクッキーや個人情報を盗んだりすることである。  
・サーバ仮想化  
１台の物理サーバ上で複数のサーバOSを稼働させる技術である。  
・ブレードサーバ  
１枚の電子基盤にPCに必要なCPUなどの要素を何枚も搭載したサーバの集合体である。必要な分だけブレード上の基盤を差し込むため台数の増減が容易である。  
・スタンドアロン(Stand-alone)  
他のサーバと接触せずに利用でき、他の機器やリソースに依存せずに単独で動作ができる機能のこと。  
・OSS(Open Source Software)  
プログラムのソースが公開されていて無償で誰でも自由に改変、再配布が可能なソフトウェアのことである。  
・コーホート分析  
時代、年齢、世代に分けて分析するマーケティング用語である。  
・RFM分析  
最終購入日（Recency）、購入頻度（Frequency）、購入金額（Monetary）の3つの指標を評価して顧客をグループ分けする分析手法である。  
・3C分析  
顧客(Custmer)、競合(Compeitor)、自社(Company)の３つの観点から分析する手法である。
・ジョイントベンチャー
2社以上の」企業で共同出資して経営する合弁会社のことである。  
・エッジコンピューティング  
データセンタやクラウドで行っていた処理をデータを収集する端末（エッジ）や端末近くにおいたコンピューターなど、データの発生源の近くで処理を行う技術である。  
・SDK(Software Development Kit)  
開発者が特定のシステムに対応したソフトウェアを作成できるように開発ツールをワンセットにしたものである。  
・SGA(Selling and Generally Administractive expenses)  
損益計算で使用される販売費や一般管理費の略称である。  
・SGML(Standerd Generalized Markup Language)  
文書の電子化のためにできたものであり、XMLやHTMLの親にあたるものである。  
・UML(Unified Modeling Language 統一モデリング言語)  
ソフトウェアやシステム開発の時に要素間の関係を視覚的に表した図である。  
・DevOps(デブオプス)  
Development開発とOperations運用を合わせた造語であり、開発チームと運用チームが密接に連携して自動化ツールを活用して迅速かつスピーディーに開発をする手法である。  
・クラウドコンピューティング  
外部のサーバに自社のグループウェアを移動しインターネット経由でその機能を利用できる仕組みのことである。クラウドのこと。  
・TPM(Trusted Platform Module)  
セキュリティチップで暗号化などをチップの内部に記憶しているものである。外部からの衝撃に強い。  
・NFC(Near Field Communication)  
至近距離での無線通信を定めた国際標準規格であり、非接触型ICカードに基づいて開発された。  
・アウトバンドマーケティング  
見込み客に対して事業者側からアプローチをするためにダイレクトメールなど不特定多数にプッシュするマーケティング活動である。  
・インバウンドマーケティング  
SNSやブログなどインターネットメディアの発信に対して興味を持って訪れた見込み客を顧客として取り込もうとするマーケティング活動である。  
・ダイレクトマーケティング  
既存の顧客や見込み客に個別に行うマーケティング活動である。きめ細かい提案をしたりして反応を獲得する。  
・テレマーケティング  
オペレーターが電話で直接顧客と対話して販売促進を行う手法である。  
・CSR(Corporate Social Responsibility)  
環境や社会からの要請に対して責任を果たすことは企業価値向上に繋がる考え方であり、企業の社会的に責任という意味である。  
・KPI(Key Performance Indicator 主なパフォーマンス指標)  
目標達成のための活動の進捗や達成度合いを測定するための指標である。

 

 



  




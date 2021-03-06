Light.vn
========
  
![My image0](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ssA00.png)    

##紹介

Light.vn（ライト・ヴィエン）はビジュアルノベル系作品の製作の為に  
作られたエンジン、及びエディターでございます。  
    
  「全てのノベルが本来持っている "光" を引き出す事」を目標に、  

  Light.vn の「Light」はその為の製作の灯になれたら、と言う意味を込めて、  
 「vn」はVisual Novel（ヴィジュアルノベル）の略語として付けました。

[リリースページ](https://github.com/hsdk123/Light.vn/releases) : Light.vnの最新バージョンページ。  
  
製作者：hsdk(炯淳) (berserkd)　「同人活動支援中！」  
mail: daegon.dhsk at outlook.com    
twitter: www.twitter.com/daegon137  
  
[フィードバックページ](http://lightvn.net/bbs) : Light.vnのフィードバックページ。  
エンジンに関する疑問や機能追加の要望などありましたらここに気軽に書いてください。   
   
フィードバックはLight.vnの成長の原動力になります。    
バク発見、機能追加、スクリプト質問等は右の[「Issues」](https://github.com/hsdk123/Light.vn/issues)ページ、  
製作者のツイッター、或は上のフィードバックページへ気軽にご連絡ください。    
  
プロジェクト支援・参加等のより個人的なお問い合わせや  
ツイッターじゃ上手く伝わらない内容や感想に関しては上のメールアドレスでお願い致します。  
  
どんな些細な事でもエンジン成長に繋がります。  
迷わず、気軽に声を掛けてくださいー。

##製作趣旨・目標

* 誰でも容易くノベルを作られる「環境」を提供する事
* 慣れることでは無く、直感的にスクリプト作業、及びプロジェクト管理が出来るようにする事  
* ノベル製作・管理を伴う無駄な時間と労力消費を最小限にし、作品制作・完成に集中できるようにする事  

##主な特徴

#####エディタ－上のプロジェクト管理
  ノベルのタイトル、解像度、配布等を含むプロジュクト設定と管理が全てエディタ上で  
簡単に出来るようにしました。
  
#####エディタ－上のプレビュー 機能
スクリプト結果が作業しながら同時に反映されるプレビュー機能を提供し  
スクリプトの編集、管理、演出テスト等に掛かる時間と精神的労力を最小化しました。  
プレビューしたいスクリプト行をクリックするだけで画面に音楽等の結果が全て反映され、  
F5キーを押す事でその行からテストプレイが始まります。
  
#####全てのGUIが簡単にカスタマイジング可能  
  
ノベル上に使われるGUI（グラフィカル・ユーザ・インターフェース）  
：セーブ・ロード画面、メニュ－，選択肢等  
全てスクリプト上で簡単に編集出来て、ノベル作品がそれぞれ持つ  
独特な雰囲気を演出する事が可能になります。

#####3Dグラフィックカードの機能を積極的に活用  
  
エンジン内部で3Dグラフィックカードの機能を積極的に活用する事で  
フェードイン・アウト、cgやカメラ移動等の効果を実行する際、  
滑らかな演出を保証し、製作者の意図をより充実に反映します。
  
#####全コマンドの日本語化    
目が遠くなる英語を排除し、コマンドを全て日本語化する事で  
スクリプト内容がもっと直感的に、軽く入られるようにしました。   

#####各コマンドの簡略化  
それぞれのコマンドの表限度を上げる事で使用を簡略化し、   
基本的なテキスト、イメージ演出等に必要な時間を最小限にして、  
より高度・繊細な演出や作品独特の雰囲気を形成するに必要な作業等  
もっと時間投資の甲斐がある作業に集中できるようにしました。
  
##対応OS  
  
#####Light.exe (ノベルアプリケーション）  

WindowsXP, Windows7, Windows8 (Vistaは理論上可能、現在未確認）  

Light.vnが成長するに連れ、以下の順でOS追加支援予定：  
Mac, モバイル（IOS, Android）

#####LightEditor.exe （エディター）
  
エディターは現在.Net 4.0 Fullを必要とするため以下のOSに限定されます：  
WindowsXP Service Pack 3 以上, Windows7, Windows8  (Vistaは理論上可能、現在未確認） 
  
##対応グラフィックドライバ  
  
OpenGL2.1以上を支援するグラフィックドライバの搭載を必要とします。         
  
現在使用中の環境が支援しているOpenGLバージョンはプログラムの起動後、  
フォルダー内に生成されるdebug.txtで確認できます。  
  
##使用ライセンス    
  
Light.vnの使用、及び製作ノベル作品の配布は全て完全無料で、      
ソフトで作られた作品の著作権も製作者様に帰属します。  
ノベル好きの開発者が単により多くのノベル作品を楽しみたくて作っています。  
  
只、ツールの利用によって損害・不利益等が  
発生した場合でも、こちらは一切の責任を負えません。    
   
(もしノベルの完成・公開後、こちらにリンクや余裕があればパッケージの一つを  
送っていただければ有難くプレイさせて頂きます)   
   
##ファイルに関して
  
###メインファイル  

#####Light.exe    
  
 ノベルアプリケーション。  
他に何かをダウンロードする必要は無く、プロジェクトフォルダー内で単独で起動します。　　

#####LightEditor.exe
  
  エディター。  
  スクリプト編集、テストプレイ、プロジェクト配布等の機能を装備。
  
  注）Light.vnのエディターであるLightEditor.exeは.Net 4.0 fullを必要とします。  
(WinXP Service Pack 3 以上の環境で動作）  
ＰＣに既にインストールされている場合も多いですが、  
もしエディター起動時問題が
発生した場合は以下で.Net 4.0 Fullをダウンロードしてください。  
www.microsoft.com/en-us/download/details.aspx?id=17851  
      
###サブファイル    

#####Commands.xml  
  
  Light.vn上で使ってる日本語命令、及びエディター上のコマンド目録に表示される各コマンド情報が含まれております。  
  言い換えれば、このファイルを修正する事でLight.vnが使う命令語も、LightEditor.exe(エディター）上のコマンド情報目録に表示される各命令語の情報を変えることが出来ます。  
  
  例えば、`「背景」`という命令名はシンプル過ぎて`「背景イメージ」`と言う命令名にしたければCommands.xml を開けて、` <Command cmd="bg" name="背景" > `を` <Command cmd="bg" name="背景イメージ" > `に修正する事でこれからLight.vnはスクリプト上で`「背景イメージ」`キーワードを読むたびに背景イメージファイルを表示します。  
  
  エディター上で表示される各コマンド情報も又同じように修正できます。  
  例えば背景命令の情報が足りない、或いはこう言い換えた方がもっと分かり易い、等と思う部分があったらCommands.xmlを開け   
  `<explanation lang="Jap" syntax="背景 [名前] [ファイル名]" 
                 details="//ex. 背景 bg1 scenery.png ...">`の`「details=」`部分を変えればエディター上で反映されます。

#####Strings(Editor).xml  
  
  エディターのテキスト目録。エディター上に表示されるあらゆるテキスト，  
例えばエディター下のFPS情報テキスト  
   `（FPS ( アップデート: {0} , render: {1} )）  `
等が入っています。  
  このファイルを修正すればエディター上で表示されるテキストが変わります。  
  
##スクリーンショット  
  
#####Light.exe (ノベルアプリケーション）

![My image1](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ssA01.png)  
  
![My image2](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ssA02.png)  
  
#####LightEditor.exe （エディター）  

![My image3](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ssE00.png)  
  
![My image4](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ssE01.png)
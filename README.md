##2015/5/22 文字コードをUTF8に変更済

# OSS-Project1

このプロジェクトは、『Linuxコマンド一覧作成する』プロジェクトです。

書式パターンは、以下の通りです。

========================================================================================================
【書式パターン】
１．Linuxコマンドを表記

２．コマンド処理の説明文を上記

３．パラメータ・オプション名と説明文を表記

４．上記３を使った実例コマンドを表記

ex.)
hostname

[書式]hostname [-adfisy] [ホスト名]

 →ホスト名、ドメイン名、IPアドレス等のホスト情報を表示します。

[パラメータ]

-a	ホストの別名 (alias) があれば表示します。

-d	DNSドメイン名を表示します。

-f	FQDNを表示します。

-i	IPアドレスを表示します。

-s	最初のドットまでの短いホスト名を表示します。

-y	NISドメイン名を表示します。

ホスト名	変更するホスト名を指定します。

ex.）　># hostname

　　　>#　newhost
　　　

========================================================================================================


プロジェクトの対応フローは以下の通りです。

■各メンバーごとにそれぞれのコマンドを追加(必須)

■実際に仮想環境でコマンドを実行して、実行結果を表示される(任意)

■メンバーが追加した『Linuxコマンド』に対して、実例パターンをを追加・修正する(必須)

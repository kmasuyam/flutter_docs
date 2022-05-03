###########################
A tour of the Dart language
###########################

このページでは、すでに他の言語でのプログラミングを知っていることを前提に、変数や演算子からクラスやライブラリに至るまで、Dartの主要な各機能の使い方を説明します。より簡単で完全ではない言語の紹介は、 `言語サンプルページ <https://dart.dev/samples>`_ をご覧ください。

Dartのコア・ライブラリについては、 `ライブラリ・ツアー <https://dart.dev/guides/libraries/library-tour>`_ をご覧ください。言語機能の詳細については、 `Dartの言語仕様書 <https://dart.dev/guides/language/spec>`_ を参照してください。


.. note::
	Dartのほとんどの言語機能は、DartPadを使用して遊ぶことができます ( `詳しくはこちら <https://dart.dev/tools/dartpad>`_)。 `DartPadを開く <https://dartpad.dev/?>`_

	このページでは、いくつかの例を表示するために埋め込まれたDartPadを使用しています。DartPadの代わりに空のボックスが表示される場合は、`DartPadのトラブルシューティングページ <https://dart.dev/tools/dartpad/troubleshoot>`_に進んでください。


====================
A basic Dart program
====================
以下のコードでは、Dartの最も基本的な機能を多く使用しています。

.. code-block:: dart
	// Define a function.
	void printInteger(int aNumber) {
	  print('The number is $aNumber.'); // Print to console.
	}

	// This is where the app starts executing.
	void main() {
	  var number = 42; // Declare and initialize a variable.
	  printInteger(number); // Call a function.
	}


ここでは、すべての（あるいはほとんどすべての）Dartアプリに適用される、このプログラムの使用方法を説明します。

``// This is a comment.``
1行のコメント。Dartは複数行のコメントや文書コメントもサポートしています。詳しくは、`コメント <https://dart.dev/guides/language/language-tour#comments>`_をご覧ください。

``void``
決して使用されない値を示す特殊な型です。``printInteger()``や``main()``のように、明示的に値を返さない関数はvoid戻り値型を持ちます。

``int``
整数を示すもう一つの型。さらに`組み込みの型 <https://dart.dev/guides/language/language-tour#built-in-types>`_として、``String``、``List``、``bool``があります。

``42``
数値リテラル。数値リテラルはコンパイル時定数の一種です。

``print()``
出力を表示するのに便利な方法です。

``'...'`` or ``"..."``
文字列リテラルです。

``$variableName`` or ``${expression}``
文字列補間：変数や式の文字列を文字列リテラルの中に入れること。詳しくは、`文字列 <https://dart.dev/guides/language/language-tour#strings>`_を参照してください。

``main()``
アプリの実行を開始する、特別で必須のトップレベル関数です。詳しくは、`main()関数 <https://dart.dev/guides/language/language-tour#the-main-function>`_を参照してください。

``var``
型を指定せずに変数を宣言する方法。この変数の型（int）は初期値（42）によって決定されます。


.. note::
	このサイトのコードは、`Dartスタイルガイド <https://dart.dev/guides/language/effective-dart/style>`_の規約に従っています。



=================
Impotant concepts
=================




*************
ヘッダーテスト2
*************

=============
ヘッダーテスト3
=============

-------------
ヘッダーテスト4
-------------


ENGLISH 
----------
Additional Information

- Using attribute selectors

You’ll notice that I’ve included attribute selectors for <abbr> and <dfn>. This way, the style will only appear if there is a title attribute on the element. This is primarily for accessibility. I think it’s safe to assume all readers (no matter what device they’re using) know what HTML stands for. I do still use the <abbr> element to make sure screen readers read the text as H-T-M-L rather than struggling to pronounce “HTML”.

- What's that bit about mark?

<mark> is a new element introduced in HTML 5 used to (you guessed it) mark text in a document. According to the spec: “The mark element represents a run of text in one document marked or highlighted for reference purposes, due to its relevance in another context.”. I anticipate it will be used for highlighting phrases in search results and other similar purposes. I’ll post more on <mark> soon.

- Where are all those application elements?

Application elements is a term I’ve loosely used to describe elements like menu, etc. These elements are more likely found in web apps than web sites. I left these out since, at the time of writing, browsers implement barely any of what was “Web Applications 1.0”. Also, this stylesheet is intended primarily for authors serving their pages as text/html, not XML.

日本語
--------

一部、直訳ではなく意訳した部分がございます。原文と表現が異なることがございますので、ご了承ください。この本日本語訳には、翻訳上の誤りがある可能性があります。したがって、内容について一切保証をするものではありません。正確さを求める場合には、必ず各記事の原文を参照してください。

属性セレクタの利用

私が <abbr> と <dfn> 向けに属性セレクタを入れたことに気づいただろうか。これは、単に、title 属性があれば表示されるようなスタイルが欲しいからに過ぎない。この理由は、第一に、アクセシビリティのためだ。それは、私たちの読者みんな（利用しているデバイスに関係なく）が、HTML とは何なのかを知っていると想定しても問題がないからだ。しかし、私たちは、それでもなお、<abbr> を入れる必要があるのだ。スクリーンリーダに、"HTML" をどうにかして発音させるのではなく、H-T-M-L と確実に読んでもらえるようにするためだ。

mark って何？

<mark> は HTML5 に導入された新要素だ。ドキュメントのテキストをマークするのに使う。仕様では、<mark> について "mark 要素は、他のコンテキストとの関連性に起因して、参照を目的にマークまたはハイライトされる、あるドキュメントの中の一連のテキストを表します。" と説明している。	この要素は、検索結果でフレーズをハイライトするために使われると、私は予想してる。

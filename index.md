<!--
# Welcome!
-->
テストハンドブックへようこそ !

<!--
This group exists to raise the quality of the WordPress experience through testing.
-->
テストチームは、テストを通じて WordPress 体験の質を高めるために存在しています。

<!--
We practice monitoring important [flows](https://make.wordpress.org/test/glossary/). Bugs and bad experiences encountered while on flow patrol are [kibbled](https://make.wordpress.org/test/glossary/) and [ticketed](https://make.wordpress.org/core/handbook/reporting-bugs/). Continuous integration means it’s especially important to encourages use of our own software as we develop it and increase awareness for what our users are experiencing day to day.
-->
私たちは、重要な[フロー](https://make.wordpress.org/test/glossary/)のモニタリングを実践しています。フローのパトロール中に遭遇したバグや悪い経験は、[kibble](https://make.wordpress.org/test/glossary/#Kibbling) や[チケット](https://make.wordpress.org/core/handbook/reporting-bugs/)として記録されます。継続的な統合とは、自分たちが開発したソフトウェアの使用を奨励し、ユーザーが日々経験していることへの認識を高めることが特に重要であることを意味しています。

<!--
*   Continuously exercise major flows. [Publishing a captioned gallery](https://make.wordpress.org/test/2015/04/22/publish-a-captioned-gallery-iphone-6-portrait/) starting from the logged-in front page, for example, is an important flow that exercises the toolbar, editor, media modal, and galleries. Regressions anywhere in this flow should be noticed and fixed promptly.
*   Continuously exercise flows through new features as they are developed.
*   Post [visual records](https://make.wordpress.org/test/glossary/) (vizrecs) of flows to [make/test](https://make.wordpress.org/test/). Show the flow. We must witness what we’re making every step of the way.
*   For features that replace or change existing ui, perform baseline visual records of major flows through the existing interface. These baselines can be used in [comparison vizrecs](https://make.wordpress.org/test/2015/02/12/press-this-copy-and-add-bookmarklet-macnchrome-4-2-alpha-31432/) as development proceeds.
*   Test patches and add screenshots to tickets. Screenshots of patched interfaces often do not make it on to tickets, particularly mobile screenshots. Use [#needs-screenshots](https://make.wordpress.org/core/handbook/contribute/trac/keywords/) to tag tickets that need screenshots. Making sure tickets have screenshots promotes [visual oxygen](https://make.wordpress.org/test/handbook/glossary/#visual-oxygen).
*   Post screenshots of bad, broken ui/ux in new features to the appropriate [feature channels](https://make.wordpress.org/core/features-as-plugins/) on Slack. Provide a visual heads up to feature teams.
*   Drop screenshots and vizrecs into ui/ux conversations in slack. So many conversations take place without reference to visuals or flow and often in complete ignorance of mobile.
*   [Create tickets](https://make.wordpress.org/core/handbook/reporting-bugs/) as needed. Crosslink tickets with any relevant vizrecs on [make/test](https://make.wordpress.org/test/). Always include screenshots in tickets. Awareness requires history. Record what the interface looks like now, before changes.
*   Share your experiences and frustrations on [make/test](https://make.wordpress.org/test/) and in [#core-test](https://wordpress.slack.com/archives/core-test/). Storyboard them with visual records.
*   Collect user experiences. Curate examples of real-life flow. Be an Alan Lomax of flow.
*   Do this with every device you have, particularly phones.
*   Be a critical part of a feature team.
-->
* <span style=", sans-serif">主要なフローを継続的に実行します。例えば、ログインしたフロントページから</span>[キャプション付きのギャラリーを公開](https://make.wordpress.org/test/2015/04/22/publish-a-captioned-gallery-iphone-6-portrait/)<span style=", sans-serif">することは、ツールバー、エディター、メディアモーダル、そしてギャラリーを動かす重要なフローです。このフローのどこかに不具合があれば、すぐに気づいて修正する必要があります。</span>
* 新機能が開発されるたびに、フローを継続的に鍛えていきます。
* [make/test](https://make.wordpress.org/test/) にフローの視覚的記録 (ビジュアルレコード) を投稿します。流れを見せます。自分たちが作っているものを一歩一歩目撃していくことが必要です。
* <span style=", sans-serif">既存の UI を置き換えたり変更したりする機能については、既存のインターフェイスにおける主要なフローをベースラインとして視覚的に記録します。これらのベースラインは、開発が進むにつれ、</span>[比較ビジュアル](https://make.wordpress.org/test/2015/02/12/press-this-copy-and-add-bookmarklet-macnchrome-4-2-alpha-31432/)<span style=", sans-serif">として使用することができます。</span>
* パッチをテストし、チケットにスクリーンショットを追加します。パッチを適用したインターフェースのスクリーンショットはチケットに反映されないことが多く、特にモバイル用のスクリーンショットはそうです。スクリーンショットが必要なチケットには [\#needs-screenshots](https://make.wordpress.org/core/handbook/contribute/trac/keywords/)&nbsp;をつけましょう。チケットにスクリーンショットがあることを確認することは、ビジュアル・オキシゲン ([視覚的に必須な「酸素」](https://make.wordpress.org/test/handbook/glossary/#visual-oxygen)) を促進します。
* <span style=", sans-serif">新機能の悪い、壊れた UI/UX のスクリーンショットを、Slack の適切な</span>[機能チャンネル](https://make.wordpress.org/core/features-as-plugins/)<span style=", sans-serif">に投稿します。機能チームに視覚的な警告を与えます。</span>
* <span style=", sans-serif">スラックでの UI/UX の会話にスクリーンショットやビジュアルレコードをドロップします。多くの会話は、ビジュアルやフローを参照せずに行われていますし、モバイルをまったく意識していないこともよくあります。</span>
* <span style=", sans-serif">必要に応じて</span>[チケットを作成](https://make.wordpress.org/core/handbook/reporting-bugs/)<span style=", sans-serif">します。チケットは </span>[make/test](https://make.wordpress.org/test/)<span style=", sans-serif"> の関連するビジュアルレコードとクロスリンクします。チケットには必ずスクリーンショットを添付してください。認識には履歴が必要です。変更前のインターフェースがどのように見えるかを記録しましょう。</span>
* <span style=", sans-serif">経験や不満を </span>[make/test](https://make.wordpress.org/test/)<span style=", sans-serif">&nbsp;や&nbsp;</span>[\#core-test](https://wordpress.slack.com/archives/core-test/)<span style=", sans-serif"> で共有しましょう。視覚的な記録でストーリーボード化しましょう。</span>
* ユーザーの体験を集め、現実のフローの例を収集します。フローの[アラン・ローマックス](https://ja.wikipedia.org/wiki/%E3%82%A2%E3%83%A9%E3%83%B3%E3%83%BB%E3%83%AD%E3%83%BC%E3%83%9E%E3%83%83%E3%82%AF%E3%82%B9)になります。
* 持っているすべての端末、特にスマートフォンでこれを実行します。
* 機能チームの重要な一部になります。

<!--
The easiest way to continuously test WordPress as it is developed is to set up a site to [automatically update to the latest nightly build](https://make.wordpress.org/core/handbook/testing/beta/). After that, consult the [triage](https://make.wordpress.org/test/handbook/triage/) page.
-->
開発中の WordPress を継続的にテストする最も簡単な方法は、[最新のナイトリービルドに自動的にアップデート](https://make.wordpress.org/core/handbook/testing/beta/)するようにサイトを設定することです。その後、[トリアージのページ](https://make.wordpress.org/test/handbook/triage/)を参照してください。

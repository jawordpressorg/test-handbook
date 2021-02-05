<!--
# How to Test FSE
-->
# FSE テストのやり方

<!--
**Overview**
-->
**概要**

<!--
Full Site Editing (FSE) is a major focus of [Gutenberg’s Phase Two](https://github.com/WordPress/gutenberg/issues/13113) work and [for 2021 goals.](https://make.wordpress.org/updates/2021/01/21/big-picture-goals-2021/) The [Full Site Editing Outreach Program](https://make.wordpress.org/test/handbook/full-site-editing-outreach-experiment/) was created as an experiment to get feedback early and often from the community about this feature. While [calls for testing](https://make.wordpress.org/test/tag/fse-testing-call/) are shared as frequently as possible, there are times when there isn’t an active call for testing but that doesn’t mean you can’t help test this feature. This guide aims to give you everything you need to start testing Full Site Editing. 
-->
Full Site Editing (FSE) は、[Gutenberg のフェーズ2](https://github.com/WordPress/gutenberg/issues/13113) と [2021年のゴールにむけて](https://make.wordpress.org/updates/2021/01/21/big-picture-goals-2021/) における主眼です。[Full Site Editing アウトリーチプログラム](https://make.wordpress.org/test/handbook/full-site-editing-outreach-experiment/) は、この機能に関するコミュニティからのフィードバックを早期かつ頻繁に得るための実験として作成されました。[テストへの協力募集](https://make.wordpress.org/test/tag/fse-testing-call/)は可能な限り頻繁に共有されています、アクティブなテストの呼びかけがない場合もありますが、この機能のテストを手伝うことができないわけではありません。このガイドは、Full Site Editing のテストを開始するために必要なすべてを提供することを目的としています。

<!--
**What’s the minimum viable product (MVP)?**
-->
**実用最小限の製品（MVP）とは何でしょうか？**

<!--
Currently, the minimum viable product is defined as building a site using the Twenty Twenty-One block theme with Full Site Editing without needing to alter code. You can read more about this MVP and the timeline [here](https://make.wordpress.org/core/2021/02/01/full-site-editing-and-themes-where-things-are/). 
-->
目下のところ、実用最小限の製品とは Twenty Twenty-One ブロックテーマ でコードを変更することなく Full Site Editing を使ってサイト構築をすることと定義されます。このMVPについて詳しくは[ココ](https://make.wordpress.org/core/2021/02/01/full-site-editing-and-themes-where-things-are/)のタイムラインで読むことができます。

<!--
**Why should I help test Full Site Editing?** 
-->
**どうして Full Site Editing のテストを助けなければいけないのですか?**

<!--
Following open source philosophy, “given enough eyeballs, all bugs are shallow”. For this feature to be a success for as many people as possible across as many situations as possible, it’s important to get this work to people early to improve future iterations. Think of this as a great way to help create the future of WordPress!
-->
オープンソースの哲学である「十分な目ん玉があれば、全てのバグは洗い出される」に従います。この機能をできるだけ多くの人に、できるだけ多くの状況に渡って成功させるために、将来のイテレーションを改善するために、この活動を早い段階で人々に届けることが重要です。WordPress の未来を創るための一助になると思ってください!

<!--
**Step 1: Setup your site**
-->
**ステップ 1: サイトを用意する**

<!--
Before you can begin to test, you need to have a site that can allow you to use this experimental feature. Please do not test on a production site. You can [follow these instructions](https://make.wordpress.org/core/handbook/tutorials/installing-wordpress-locally/) to set up a local install or you can use a [tool like this to set up a development site](https://localwp.com/). 
-->
テストを始める前に、この実験的な機能を使用できるサイトを持っている必要があります。リリースされているサイトでテストしないでください。[こちらの指示に従って](https://make.wordpress.org/core/handbook/tutorials/installing-wordpress-locally/)ローカルインストールをセットアップしてください。もしくは[このような開発用サイトをセットアップするツール](https://localwp.com/)を使用してください。


Before you can begin to test, you need to have a site that can allow you to use this experimental feature. Please do not test on a production site. You can [follow these instructions](https://make.wordpress.org/core/handbook/tutorials/installing-wordpress-locally/) to set up a local install or you can use a [tool like this to set up a development site](https://localwp.com/). 
Before you can begin to test, you need to have a site that can allow you to use this experimental feature. Please do not test on a production site. You can [follow these instructions](https://make.wordpress.org/core/handbook/tutorials/installing-wordpress-locally/) to set up a local install or you can use a [tool like this to set up a development site](https://localwp.com/). 

*   Use the latest version of WordPress or at least WordPress 5.6+ (downloadable [here](https://wordpress.org/download/)).
*   Use the [TT1 Blocks Theme](https://wordpress.org/themes/tt1-blocks/). This is the block version of the Twenty Twenty-One theme. 
*   Use the latest version of Gutenberg or at least Gutenberg 9.6+ ([latest version](https://github.com/WordPress/gutenberg/releases/)). 

Once you have all of these items in place, you should now see a navigation item titled “Site Editor (beta)”. Here’s a screenshot of what you should see:

![](https://lh3.googleusercontent.com/RHp-P8Vy9FCzPl8X70pbCzaSRZO5iufRuJ6FlcJJJu-Fa4LHGpEMk6ZcRx65FoI-GXLp7mG03XaZ7wFbcnu4BTJxb-fOUqk_IgbmEeQ3haB6hmDrgsuncGonSB-Y6rLfJL02qQXC)

If you don’t see that in your WordPress admin, you aren’t properly using the Site Editing experiment. If you need help, please ask in the [#fse-outreach-experiment](https://make.wordpress.org/test/tag/fse-outreach-experiment/) channel in [WordPress.org slack](https://make.wordpress.org/chat/). 

**Step 2: Explore and test different features**

While you’re welcome to test any aspect of the experience, it sometimes can help to know where to start. Here are some options below inspired by the [Site Editing Milestones](https://github.com/WordPress/gutenberg/issues/24551) to help you get started.

Anyone:

*   Follow instructions for [former calls for testing](https://make.wordpress.org/test/tag/fse-testing-call/).
*   Use different Full Site Editing specific blocks like the Posts Lists Block, Site Title Block, Template Part Block, Site Logo Block, Navigation Block, and more. 
*   Explore Global Styles ([screenshot](https://cloudup.com/cLvEKBIZ3LO) of where to find this option). Try changing settings for blocks globally. 
*   Edit Templates like the 404 Page Template or Single Page Template. 
*   Explore the various browsing options between your content and Templates.
*   Try building a site. 
*   Try using a Theme other than TT1 from the [theme experiments repository](https://github.com/WordPress/theme-experiments#instructions).

Theme authors:

*   Try the Query Block and see how you might be able to use it for future Theme building. [Here’s a short video](https://cloudup.com/cPKHAvWp3MN) walking through how to get started.
*   [Get familiar with Global Styles](https://developer.wordpress.org/block-editor/developers/themes/theme-json/). 
*   Create [Block Templates](https://developer.wordpress.org/block-editor/developers/block-api/block-templates/), [Block Patterns](https://developer.wordpress.org/block-editor/developers/block-api/block-patterns/), and [Block Style Variations](https://developer.wordpress.org/block-editor/developers/filters/block-filters/#block-style-variations).
*   Test and/or explore themes from the [theme experiments repository](https://github.com/WordPress/theme-experiments#instructions).
*   [Review this series of posts](https://themeshaper.com/tag/full-site-editing/) to help expand your knowledge of block theming.
*   [Build your own block theme](https://developer.wordpress.org/block-editor/tutorials/block-based-themes/) and review [current documentation](https://developer.wordpress.org/block-editor/developers/themes/).

Plugin authors: Create a Block by [following this tutorial](https://developer.wordpress.org/block-editor/tutorials/create-block/). If your current plugins impact [Navigation](https://github.com/WordPress/gutenberg/projects/31) or [Widgets](https://github.com/WordPress/gutenberg/projects/27), review the respective projects underway to add block functionality to those experiences. Both of those projects help pave the way to Full Site Editing.

**Step 3: Share feedback**

For feedback that relates to the TT1 theme, please open issues in the [Theme Experiment’s GitHub repository](https://github.com/WordPress/theme-experiments/issues).

For feedback that relates to the Full Site Editing experience, please open issues on [Gutenberg’s GitHub repository](https://github.com/WordPress/gutenberg/issues/).

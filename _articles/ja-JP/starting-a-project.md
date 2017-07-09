---
locale: ja-JP
title: オープンソースプロジェクトを立ち上げる
description: オープンソースの世界への理解を深め、自分のプロジェクトを立ち上げる準備をする
class: 入門者
toc:
  the-what-and-why-of-open-source: "The what and why of open source"
  should-i-launch-my-own-open-source-project: "Should I launch my own open source project?"
  launching-your-own-open-source-project: "Launching your own open source project"
  naming-and-branding-your-project: "Naming and branding your project"
  your-pre-launch-checklist: "Your pre-launch checklist"
order: 2
image: /assets/images/cards/beginner.png

locale: en-US
title: Starting an Open Source Project
description: Learn more about the world of open source and get ready to launch your own project.
class: beginners
---

## オープンソースとは何か、なぜオープンソースなのか
## The "what" and "why" of open source

あなたはオープンソースで何かを始めようと考えていますか？おめでとうございます！世界中の人々はあなたの貢献を歓迎しています。ではオープンソースとは何なのか、なぜ人々はオープンソースでやるのかについて話しましょう。
So you're thinking about getting started with open source? Congratulations! The world appreciates your contribution. Let's talk about what open source is and why people do it.

### オープンソースとは何を意味するのか？
### What does "open source" mean?

#TODO:set correct link url
あるプロジェクトがオープンソースであるということは、そのプロジェクトが「あらゆる目的で、だれでも閲覧できる、利用できる、修正できる、再配布できる」ことを意味します。それらの許可は[オープンソースライセンス](h)によって決められています。
When a project is open source, that means **anybody can view, use, modify, and distribute your project for any purpose.** These permissions are enforced through [an open source license](https://opensource.org/licenses).

オープンソースの魅力は、アイディアを急速に拡散させ、ソフトウェアを採用する障壁を低くすることにある。
Open source is powerful because it lowers the barriers to adoption, allowing ideas to spread quickly.

オープンソースのはたらきを理解するには、こんな想像をしてみよう。友人から持ち寄りのパーティーに誘われ、あなたはチェリーパイを持参したとする。
To understand how it works, imagine your friend is having a potluck, and you bring a cherry pie.

* みんながチェリーパイを食べる (利用)
* チェリーパイは大好評！みんなはあなたにどのようにして作ったのかパイのレシピを尋ねる (閲覧)
* パティシエである友人アレックスが、砂糖を少なくしたらもっと美味しくなるのではないかと提案する (修正)
* 別の友人リサが、アレックスの考案したレシピを来週のディナーで利用してもよいかと尋ねる (再配布)
* Everybody tries the pie (_use_)
* The pie is a hit! They ask you for the recipe, which you provide (_view_)
* One friend, Alex, who's a pastry chef, suggests reducing the sugar (_modify_)
* Another friend, Lisa, asks to use it for a dinner next week (_distribute_)

それに対して、ソースコードを公開しないプロセスを例えるなら、レストランでチェリーパイを注文するようなものだ。あなたは代金を支払う必要があるし、レシピを知りたいと思ってもレストランは教えてくれないだろう。もしあなたがパイの作り方を正確にマネをして自分の看板で売ろうとすれば、おそらくレストランはあなたに対抗する行動を起こすだろう。
By comparison, a closed source process would be going to a restaurant and ordering a slice of cherry pie. You must pay a fee to eat the pie, and the restaurant probably won't give you their recipe. If you copied their pie exactly and sold it under your own name, the restaurant could take action against you.

### なぜ人々は作ったものをオープンソースにするのか
### Why do people open source their work?

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/1500684?v=3&s=460" class="pquote-avatar" alt="avatar">
  私がオープンソース上の共同作業を通じて得たもっとも価値のある経験は、私が直面した問題に、おなじく頭を抱えている他の開発者がいて、彼らと関係性を築けたことだ。
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["どうやってオープンソースを最高！と思えるようになったか"](https://medium.com/@kentcdodds/how-getting-into-open-source-has-been-awesome-for-me-8480cd756a80#.pjt9oqp4w)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/1500684?v=3&s=460" class="pquote-avatar" alt="avatar">
  One of the most rewarding experiences I get out of using and collaborating on open source comes from the relationships that I build with other developers facing many of the same problems I am.
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["How getting into Open Source has been awesome for me"](https://medium.com/@kentcdodds/how-getting-into-open-source-has-been-awesome-for-me-8480cd756a80#.pjt9oqp4w)
  </p>
</aside>

[たくさんの理由があるが](http://ben.balter.com/2015/11/23/why-open-source/) 、なぜ開発者や組織がオープンソースでプロジェクトを始めようと思うのか。それにはいくつかの例が挙げられる:
[There are many reasons](http://ben.balter.com/2015/11/23/why-open-source/) why a person or organization would want to open source a project. Some examples include:

* **共同作業:** オープンソースプロジェクトは世界中の誰からの変更も受け入れることができる。 [Exercism](https://github.com/exercism/)の例でいえば、350人を超えるコントリビュータをもつプログラミング訓練プラットフォームである。
* **Collaboration:** Open source projects can accept changes from anybody in the world. [Exercism](https://github.com/exercism/), for example, is a programming exercise platform with over 350 contributors.

* **採用し、加工する:** オープンソースプロジェクトは近しい目的を持つあらゆる人が使うことができる。別のものを作るために使うこともできる。[WordPress](https://github.com/WordPress)の例でいえば、[b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md)と呼ばれる既存プロジェクトのフォークとしてプロジェクトを始めることができる。
* **Adoption and remixing:** Open source projects can be used by anyone for nearly any purpose. People can even use it to build other things. [WordPress](https://github.com/WordPress), for example, started as a fork of an existing project called [b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md).

* **透明性:** あらゆる人がオープンソースプロジェクトのエラーや矛盾を検査できる。透明性は[ブルガリア](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a)や[アメリカ](https://sourcecode.cio.gov/)のような政治にとって重要である。また、銀行や医療など法的に規制された産業にも重要であるし、あるいは[Let's Encrypt](https://github.com/letsencrypt)のようなセキュリティソフトウェアにも重要である。.
* **Transparency:** Anyone can inspect an open source project for errors or inconsistencies. Transparency matters to governments like [Bulgaria](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a) or the [United States](https://sourcecode.cio.gov/), regulated industries like banking or healthcare, and security software like [Let's Encrypt](https://github.com/letsencrypt).

オープンソースはソフトウェア以外の分野でも重要である。あなたはデータセットから書籍へとあらゆるものをオープンソースにすることができる。[GitHub Explore](https://github.com/explore)を見れば、ソフトウェア以外のどのようなアイディアにオープンソースが用いられているか分かる。
Open source isn't just for software, either. You can open source everything from datasets to books. Check out [GitHub Explore](https://github.com/explore) for ideas on what else you can open source.

### オープンソースは「無料」を意味するか？
### Does open source mean "free of charge"?

オープンソースの最大の特徴のひとつは、コストをかけずに利用できることである。しかし、「無料」であることはオープンソースの本質的な価値から生じた副産物である。
One of open source's biggest draws is that it does not cost money. "Free of charge", however, is a byproduct of open source's overall value.

オープンソースライセンスは次のことを義務付ける。同じような目的をもつあらゆる人たちに利用、修正、共有できるようにすることだ。したがって、プロジェクト自体は無料になる傾向がある。なぜなら、もしプロジェクトを有料にしても、だれでも無料版のコピーを作れるため、その無料版を代わりに使うと思われるからだ。
Because [an open source license requires](https://opensource.org/osd-annotated) that 
anyone can use, modify, and share your project for nearly any purpose, 
projects themselves tend to be free of charge. 
If the project cost money to use, anyone could legally make a copy and use the free version instead.

その結果、ほとんどのオープンソースプロジェクトは自由であるが、「無料」であることはオープンソースの定義に含まれていない。オープンソースプロジェクトを間接的に課金することは可能であり、２つのライセンスを適用したり、利用できる機能に制限をかけるなどをして、オープンソースの公式的なルールを破らないことはできる。
As a result, most open source projects are free, but "free of charge" is not part of the open source definition. There are ways to charge for open source projects indirectly through dual licensing or limited features, while still complying with the official definition of open source.

## 私は自分でオープンソースプロジェクトを立ち上げるべきか？
## Should I launch my own open source project?

簡潔に答えるなら「その通り」だ。なぜなら、結果を求められるわけではないから。自分でオープンソースプロジェクトを立ち上げることで、それがどういうものか理解を深めることができる。
The short answer is yes, because no matter the outcome, launching your own project is a great way to learn how open source works.

もしあなたがこれまでオープンソースプロジェクトを立ち上げたことがないとすれば、他者がどう反応するだろう、あるいはだれも気づいてくれないのではないか、と心配しているかもしれない。もしそうだとすれば、心配する必要はない。あなたはひとりではないのだから！
If you've never open sourced a project before, you might be nervous about what people will say, or whether anyone will notice at all. If this sounds like you, you're not alone!

オープンソースワークは執筆業や絵画など、ほかの創造的な活動と似ている。あなたが作ったものを誰かに共有することは怖いかもしれないが、その気持ちとうまく付き合う最良の方法は、実際にやってみることだ。たとえ共有する相手がいなかったとしても。
Open source work is like any other creative activity, whether it's writing or painting. It can feel scary to share your work with the world, but the only way to get better is to practice - even if you don't have an audience.

もしあなたが確信できていないとしても、少しの時間をとって考えてみてほしい。あなたのゴールはどこにあるのか。
If you're not yet convinced, take a moment to think about what your goals might be.

### ゴールを設定する
### Setting your goals

ゴールを設定することは、自分が何をやろうとしているのか理解する助けになる。また、何をやらないのか、どういう部分で他者の助けが必要なのか知ることにもなる。自分自身に問いかけることから始めよう。なぜ私はこのプロジェクトをオープンソースにするのか？
Goals can help you figure out what to work on, what to say no to, and where you need help from others. Start by asking yourself,  _why am I open sourcing this project?_

その答えはひとつの絶対的な答えがあるわけではない。ひとつのプロジェクトに複数のゴールが存在することはありえるし、別のゴールをもったいくつかのプロジェクトがあるかもしれない。
There is no one right answer to this question. You may have multiple goals for a single project, or different projects with different goals.

あなたのゴールは自分が作ったものを見せびらかすことかもしれないし、他者からのコントリビュートを望まないかもしれないし、READMEにそう書きたいかもしれない。あるいは、他者からのコントリビュートを得たい、時間をかけてドキュメントを分かりやすくして興味を持ってくれた他者を歓迎したい、と考えるかもしれない。
If your only goal is to show off your work, you may not even want contributions, and even say so in your README. On the other hand, if you do want contributors, you'll invest time into clear documentation and making newcomers feel welcome.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/3520168?v=3&s=460" class="pquote-avatar" alt="avatar">
  ある時期に、私はUIAlertViewを自分でカスタマイズして使っていましたが、これをオープンソースにしようと決断しました。そして、よりダイナミックなものに修正して、GitHubにアップロードしました。また、開発者の人々に使ってもらうために、使い方を説明したドキュメントを初めて書きました。とても簡単なプロジェクトだったので、おそらく誰も使わなかったと思います。しかし、自分のプロジェクトをオープンソースで公開したことに、私は満足感を覚えました。
  <p markdown="1" class="pquote-credit">
— @mavris, ["独学のソフトウェア開発者: なぜオープンソースにすることは自分のためになるのか"](https://medium.com/rocknnull/self-taught-software-engineers-why-open-source-is-important-to-us-fe2a3473a576#.zhwo5krlq)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/3520168?v=3&s=460" class="pquote-avatar" alt="avatar">
  At some point I created a custom UIAlertView that I was using...and I decided to make it open source. So I modified it to be more dynamic and uploaded it to GitHub. I also wrote my first documentation explaining to other developers how to use it on their projects. Probably nobody ever used it because it was a simple project but I was feeling good about my contribution.
  <p markdown="1" class="pquote-credit">
— @mavris, ["Self-taught Software Developers: Why Open Source is important to us"](https://medium.com/rocknnull/self-taught-software-engineers-why-open-source-is-important-to-us-fe2a3473a576#.zhwo5krlq)
  </p>
</aside>

あなたのプロジェクトが成長するにつれて、そのコミュニティはあなたのコードだけではなく、ほかのタスクも必要になってくる。それは、イシューに返信すること、コードをレビューすること、プロジェクトの存在を広めることである。
As your project grows, your community may need more than just code from you. Responding to issues, reviewing code, and evangelizing your project are all important tasks in an open source project.

それらのコーディングしないタスクに、あなたはどれだけの時間を費やせば良いだろうか。それは、あなたのプロジェクトの大きさと範囲によって決まる。あなたはメンテナとなり、あなたを助けてくれる誰かを探す用意を進めるべきである。
While the amount of time you spend on non-coding tasks will depend on the size and scope of your project, you should be prepared as a maintainer to address them yourself or find someone to help you.

**もしあなたがオープンソースプロジェクトを運営する会社のメンバーだったら**、知っておかなければならないことがある。そのプロジェクトを成長させるためには、社内リソースが必要になるということだ。プロジェクト公開後のメンテナンスに誰が責任をもつのか明確化したり、これまであなたが担当していたタスクを社内メンバーにどう共有するか考えることになる。
**If you're part of a company open sourcing a project,** make sure your project has the internal resources it needs to thrive. You'll want to identify who's responsible for maintaining the project after launch, and how you'll share those tasks with your community.

プロジェクトを広めたり、メンテナンスするのには予算や人員が必要になるかもしれない。そうであるなら、上記の社内での話し合いは、できるだけ早めにやったほうが良い。
If you need a dedicated budget or staffing for promotion, operations and maintaining the project, start those conversations early.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1857993?v=3&s=460" class="pquote-avatar" alt="avatar">
  あなたがオープンソースプロジェクトを始めるにあたり、覚えておくべき重要なことがあります。それはプロジェクト管理プロセスをよく考えるということなのですが、あなたのプロジェクト周辺のコミュニティにいるコントリビュータの人々や彼らの技能について配慮するということです。恐れずにコントリビュータを巻き込みましょう。たとえ彼らがあなたに雇われていなかったとしても、それはプロジェクトの重要な側面に影響するわけではありません。特に彼らが頻繁にコントリビュートしてくれる人々であれば、なおさらです。
 <p markdown="1" class="pquote-credit">
— @captainsafia, ["プロジェクトをオープンソースにしたいんじゃない？そうでしょ？"](https://writing.safia.rocks/2016/12/06/so-you-wanna-open-source-a-project-eh/)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1857993?v=3&s=460" class="pquote-avatar" alt="avatar">
  As you begin to open source the project, it's important to make sure that your management processes take into consideration the contributions and abilities of the community around your project. Don't be afraid to involve contributors who are not employed in your business in key aspects of the project — especially if they are frequent contributors.
  <p markdown="1" class="pquote-credit">
— @captainsafia, ["So you wanna open source a project, eh?"](https://writing.safia.rocks/2016/12/06/so-you-wanna-open-source-a-project-eh/)
  </p>
</aside>

### 他のプロジェクトにコントリビュートする
### Contributing to other projects

もしあなたのゴールが、どのように他者と協働すればよいか学ぶこと、あるいはオープンソースがどのようにはたらくか理解することだとすれば、既存のプロジェクトに貢献してみるのはどうでしょうか。あなたがすでに利用していて愛着の湧くプロジェクトで始めるのが良いでしょう。プロジェクトにコントリビュートするというのは、誤字を直すことやドキュメントをアップデートするようなシンプルなことでも歓迎されます。
If your goal is to learn how to collaborate with others or understand how open source works, consider contributing to an existing project. Start with a project that you already use and love. Contributing to a project can be as simple as fixing typos or updating documentation.

コントリビュータとしてどのように始めればよいか分からない場合、[どうやってオープンソースに貢献するか](../how-to-contribute/)をチェックしてみてください。
If you're not sure how to get started as a contributor, check out our [How to Contribute to Open Source guide](../how-to-contribute/).

## 自分のオープンソースプロジェクトを立ち上げる
## Launching your own open source project

あなたが作ったものをオープンソースにするのに十分な時間というものは存在しません。あなたはアイディアをオープンソースにすることができるのです。その作業は実はすでに進行しているか、あるいは数年の間クローズドソースでいた後にオープンソースとなるのです。
There is no perfect time to open source your work. You can open source an idea, a work in progress, or after years of being closed source.

一般的にプロジェクトをオープンソース化するべき状況としては、あなたのプロジェクトを他者から見られて気持ち良いと思える場合か、フィードバックをもらいたいという場合です。
Generally speaking, you should open source your project when you feel comfortable having others view, and give feedback on, your work.

プロジェクトをオープンソース化するか決断する段階にいなかったとしても、あらゆるプロジェクトには以下のドキュメントが作成されているべきです。
No matter which stage you decide to open source your project, every project should include the following documentation:

* [Open source license](https://help.github.com/articles/open-source-licensing/#where-does-the-license-live-on-my-repository)
* [README](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
* [Contributing guidelines](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
* [Code of conduct](../code-of-conduct/)

メンテナとして、これらのコンポーネントは次のようなことについてあなたを助けてくれるでしょう。あなたが最終的にやりたいことを明確化すること、コントリビューションを管理すること、あなた自身を含むあらゆる人々の法的な権利を守ること、についてです。それらはあなたがより意義深い経験をするための大きな助けとなるでしょう。
As a maintainer, these components will help you communicate expectations, manage contributions, and protect everyone's legal rights (including your own). They significantly increase your chances of having a positive experience.

もしあなたのプロジェクトがGitHubにあるなら、それらのファイルをあなたのrootディレクトリに推奨されたファイル名にして設置すると良いでしょう。そうすれば、GitHubはそれを認識して自動的にあなたを購読している人々に知らせてくれるでしょう。
If your project is on GitHub, putting these files in your root directory with the recommended filenames will help GitHub recognize and automatically surface them to your readers.

### ライセンスを選ぶ
### Choosing a license

オープンソースライセンスは次のことを保証する。他者がそのプロジェクトを利用、複製、修正、そしてあなたのプロジェクトに貢献し返してくれる場合などに発生しうる、悪影響をなくしてくれる。法的に面倒な状況になることからも、あなたを守ってくれる。**あなたがオープンソースプロジェクトを立ち上げる場合には、必ずライセンスを含めなければならない。**
An open source license guarantees that others can use, copy, modify, and contribute back to your project without repercussions. It also protects you from sticky legal situations. **You must include a license when you launch an open source project.**

法律に関する仕事は楽しいものではありません。しかし、良いニュースがあるとすれば、あなたは既存のライセンスをあなたのプロジェクトにコピー&ペーストできることです。それは、ほんの短時間であなたのハードワークを守ることができる、ということです。
Legal work is no fun. The good news is that you can copy and paste an existing license into your repository. It will only take a minute to protect your hard work.

[MIT](https://choosealicense.com/licenses/mit/)、[Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)、[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)は、もっとも人気のあるオープンソースライセンスですが、[その他にのオプション](https://choosealicense.com)も選択することはできる。
[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) are the most popular open source licenses, but [there are other options](https://choosealicense.com) to choose from.

あなたが新しいプロジェクトをGitHub上で作成するなら、どのライセンスを選択するか選ぶオプションが表示されます。オープンソースライセンスを含めることは、あなたのGitHubプロジェクトをオープンソースにすることを意味します。
When you create a new project on GitHub, you are given the option to select a license. Including an open source license will make your GitHub project open source.

![ライセンスを選ぶ](/assets/images/starting-a-project/repository-license-picker.png)
![pick a license](/assets/images/starting-a-project/repository-license-picker.png)

その他に質問がある場合や、オープンソースプロジェクトの運営するうえでの法的な側面に興味があるなら、[こちらのページで案内しています](../legal/)。
If you have other questions or concerns around the legal aspects of managing an open source project, [we've got you covered](../legal/).

### READMEを書く
### Writing a README

READMEは、あなたのプロジェクトをどうやって使うのか説明するだけでなく、ほかにも意味があります。なぜあなたのプロジェクトが重要なのか、プロジェクト利用者がどんなことをできるようになるか、ということも説明します。
READMEs do more than explain how to use your project. They also explain why your project matters, and what your users can do with it.

あなたのREADMEについて、下記の質問に答えてみてください:
In your README, try to answer the following questions:

* このプロジェクトは何をやっているのか？
* なぜこのプロジェクトが役に立つのか？
* どうやって使い始めればよいのか？
* 詳しいヘルプを知りたくなったとき、どこを見ればよいか？
* What does this project do?
* Why is this project useful?
* How do I get started?
* Where can I get more help, if I need it?

READMEに関する他の質問についても答えることができます。たとえば、コントリビューションをどう扱うのか、プロジェクトのゴールはどう設定されているのか、ライセンスと帰属に関する情報、など。もしあなたがコントリビュータを受け入れたくない場合や、実用的な形としてまだ仕上がっていない場合には、それらの情報もREADMEに書いておきましょう。
You can use your README to answer other questions, like how you handle contributions, what the goals of the project are, and information about licenses and attribution. If you don't want to accept contributions, or your project is not yet ready for production, write this information down.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  良いドキュメンテーションが意味するものとは、より多くのユーザーがいて、より少ないサポートで、より多くのコントリビュータがいる、ということです。忘れてはいけないことは、そのドキュメントを読んでいる人たちは、あなたではないということです。プロジェクトに訪れてくれたその人たちは、あなたとは全く異なる経験をしてきた人々なのです。
  <p markdown="1" class="pquote-credit">
— @limedaring, ["あなたが書いた言葉をもっと読んでもらうために（動画）"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  Better documentation means more users, less support requests, and more contributors. (...) Remember that your readers aren't you. There are people who might come to a project who have completely different experiences.
  <p markdown="1" class="pquote-credit">
— @limedaring, ["Writing So Your Words Are Read (video)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

ときどき、READMEを書かないようにしている人々がいて、彼らはプロジェクトがまだ完成していないから、あるいはコントリビューションを望んでいないから、と思っているようです。しかし、それらの理由というのは、実はREADMEを書くにはとても良い機会なのです。
Sometimes, people avoid writing a README because they feel like the project is unfinished, or they don't want contributions. These are all very good reasons to write one.

もっとインスピレーションが必要ということであれば、@18Fの["READMEをより読みやすくする"](https://pages.18f.gov/open-source-guide/making-readmes-readable/)や、@PurpleBoothの[READMEテンプレート](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)を参照すれば、より理想的なREADMEを書けるでしょう。
For more inspiration, try using @18F's ["Making READMEs Readable"](https://pages.18f.gov/open-source-guide/making-readmes-readable/) or @PurpleBooth's [README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) to write a complete README.

READMEファイルをあなたのプロジェクトのrootディレクトリに置けば、GitHubは自動的にリポジトリのホームに表示してくれます。
When you include a README file in the root directory, GitHub will automatically display it on the repository homepage.

### コントリビュートのガイドラインを書く
### Writing your contributing guidelines

CNOTRIBUTINGファイルとは、あなたのプロジェクトを見ている人に、どうすればそのプロジェクトに参加できるのかを伝えるものです。たとえば、以下の情報を記載していたとして:
A CONTRIBUTING file tells your audience how to participate in your project. For example, you might include information on:

* どうやってバグリポートを提出するか（[イシューとプルリクエストのテンプレート](https://github.com/blog/2111-issue-and-pull-request-templates)を使ってください）
* どうやって新しい機能を提案するか
* どうやって環境設定を行いテストを行うか
* How to file a bug report (try using [issue and pull request templates](https://github.com/blog/2111-issue-and-pull-request-templates))
* How to suggest a new feature
* How to set up your environment and run tests

技術的な詳細に加えて、CONTRIBUTINGファイルはあなたがどんなことをコントリビュートしてほしいのか、ということを伝える機会として活用できます。たとえば:
In addition to technical details, a CONTRIBUTING file is an opportunity to communicate your expectations for contributions, such as:

* どのような種類のコントリビューションをあなたが求めているか
* あなたが考えているロードマップやビジョン
* どのような手段でコントリビュータはあなたに連絡を取るべきか（取るべきでないか）
* The types of contributions you're looking for
* Your roadmap or vision for the project
* How contributors should (or should not) get in touch with you

温かい心をもって、友好的な口調で、やってほしいコントリビューションを具体的に伝えること（たとえばドキュメンテーションを書くこと、ウェブサイトを作ること）で、これからの長い道のりの間、新しく参加してくれた人は、歓迎されているという気持ちでワクワクしながらプロジェクトに参加することができる。
Using a warm, friendly tone and offering specific suggestions for contributions (such as writing documentation, or making a website) can go a long way in making newcomers feel welcomed and excited to participate.

たとえば、[Active Admin](https://github.com/activeadmin/activeadmin/)は[コントリビューションのガイド](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) をこんな文章で書き始めている:
For example, [Active Admin](https://github.com/activeadmin/activeadmin/) starts [its contributing guide](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) with:

まずはじめに、感謝の気持ちを伝えたい。あなたがActive Adminへのコントリビュートを考えてくれていることに。あなたのような人々が、Active Adminをすばらしいツールにしてくれる。
> First off, thank you for considering contributing to Active Admin. It's people like you that make Active Admin such a great tool.

あなたのプロジェクトの最初期の段階では、CONTRIBUTINGファイルはシンプルなものだろう。あなたが常に説明すべきことだが、どうやってバグレポートを提出するか、技術的な必要条件（たとえばテスト）にどのようなものがあるか、ということをコントリビュータに伝えなければならない。
In the earliest stages of your project, your CONTRIBUTING file can be simple. You should always explain how to report bugs or file issues, and any technical requirements (like tests) to make a contribution.

プロジェクト開始からある程度の時期が経ったら、よくある質問をCONTRIBUTINGファイルに書くと良いでしょう。この情報を書くことで、何度も同じ内容の質問をされることを回避できます。
Over time, you might add other frequently asked questions to your CONTRIBUTING file. Writing down this information means fewer people will ask you the same questions over and over again.

CONTRIBUTINGファイルを書くことについてもっとヘルプが必要であれば、@nayafiaの[コントリビューションガイドのテンプレート](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) 、あるいは@mozillaの ["どうやってCONTRIBUTING.mdを書くか"](http://mozillascience.github.io/working-open-workshop/contributing/)が助けになるでしょう。
For more help with writing your CONTRIBUTING file, check out @nayafia's [contributing guide template](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) or @mozilla's ["How to Build a CONTRIBUTING.md"](http://mozillascience.github.io/working-open-workshop/contributing/).

リンクをREADMEからCONTRIBUTINGファイルに貼っておくことで、より多くの人びとに見てもらうことができます。もし[CONTRIBUTINGファイルをあなたのプロジェクトのリポジトリに置いたら](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)、GitHubは自動的にリンクをあなたのファイルに貼ってくれますが、それはコントリビュータがイシューを作成した時、あるいはプルリクエストを開いたときに貼られます。
Link to your CONTRIBUTING file from your README, so more people see it. If you [place the CONTRIBUTING file in your project's repository](https://help.github.com/articles/setting-guidelines-for-repository-contributors/), GitHub will automatically link to your file when a contributor creates an issue or opens a pull request.

![コントリビューションガイドライン](/assets/images/starting-a-project/Contributing-guidelines.jpg)
![contributing guidelines](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### Establishing a code of conduct

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/11214?v=3&s=460" class="pquote-avatar" alt="avatar">
  We’ve all had experiences where we faced what was probably abuse either as a maintainer trying to explain why something had to be a certain way, or as a user...asking a simple question. (...) A code of conduct becomes an easily referenced and linkable document that indicates that your team takes constructive discourse very seriously.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["Making Open Source a Happier Place"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f#.v4qhl7t7v)
  </p>
</aside>

Finally, a code of conduct helps set ground rules for behavior for your project's participants. This is especially valuable if you're launching an open source project for a community or company. A code of conduct empowers you to facilitate healthy, constructive community behavior, which will reduce your stress as a maintainer.

For more information, check out our [Code of Conduct guide](../code-of-conduct/).

In addition to communicating _how_ you expect participants to behave, a code of conduct also tends to describe who these expectations apply to, when they apply, and what to do if a violation occurs.

Much like open source licenses, there are also emerging standards for codes of conduct, so you don't have to write your own. The [Contributor Covenant](http://contributor-covenant.org/) is a drop-in code of conduct that is used by [over 40,000 open source projects](http://contributor-covenant.org/adopters/), including Kubernetes, Rails, and Swift. No matter which text you use, you should be prepared to enforce your code of conduct when necessary.

Paste the text directly into a CODE_OF_CONDUCT file in your repository. Keep the file in your project's root directory so it's easy to find, and link to it from your README.

## Naming and branding your project

Branding is more than a flashy logo or catchy project name. It's about how you talk about your project, and who you reach with your message.

### Choosing the right name

Pick a name that is easy to remember and, ideally, gives some idea of what the project does. For example:

* [Sentry](https://github.com/getsentry/sentry) monitors apps for crash reporting
* [Thin](https://github.com/macournoyer/thin) is a fast and simple Ruby web server

If you're building upon an existing project, using their name as a prefix can help clarify what your project does (ex. [node-fetch](https://github.com/bitinn/node-fetch) brings `window.fetch` to Node.js).

Consider clarity above all. Puns are fun, but remember that some jokes might not translate to other cultures or people with different experiences from you. Some of your potential users might be company employees: you don't want to make them uncomfortable when they have to explain your project at work!

### Avoiding name conflicts

Check for open source projects with a similar name, especially if you share the same language or ecosystem. If your name overlaps with a popular existing project, you might confuse your audience.

If you want a website, Twitter handle, or other properties to represent your project, make sure you can get the names you want. Ideally, [reserve those names now](https://instantdomainsearch.com/) for peace of mind, even if you don't intend to use them just yet.

Make sure that your project's name doesn't infringe upon any trademarks. A company might ask you to take down your project later on, or even take legal action against you. It's just not worth the risk.

You can check the [WIPO Global Brand Database](http://www.wipo.int/branddb/en/) for trademark conflicts. If you're at a company, this is one of the things your [legal team can help you with](../legal/).

Finally, do a quick Google search for your project name. Will people be able to easily find your project? Does something else appear in the search results that you wouldn't want them to see?

### How you write (and code) affects your brand, too!

Throughout the life of your project, you'll do a lot of writing: READMEs, tutorials, community documents, responding to issues, maybe even newsletters and mailing lists.

Whether it's official documentation or a casual email, your writing style is part of your project's brand. Consider how you might come across to your audience and whether that is the tone you wish to convey.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/11321?v=3&s=460" class="pquote-avatar" alt="avatar">
  I tried to be involved with every thread on the mailing list, and showing exemplary behaviour, being nice to people, taking their issues seriously and trying to be helpful overall. After a while, people stuck around not to only ask questions, but to help with the answering as well, and to my complete delight, they mimicked my style.
  <p markdown="1" class="pquote-credit">
— @janl on [CouchDB](https://github.com/apache/couchdb), ["Sustainable Open Source"](http://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

Using warm, inclusive language (such as "them", even when referring to the single person) can go a long way in making your project feel welcoming to new contributors. Stick to simple language, as many of your readers may not be native English speakers.

Beyond how you write words, your coding style may also become part of your project's brand. [Angular](https://github.com/johnpapa/angular-styleguide) and [jQuery](http://contribute.jquery.org/style-guide/js/) are two examples of projects with rigorous coding styles and guidelines.

It isn't necessary to write a style guide for your project when you're just starting out, and you may find that you enjoy incorporating different coding styles into your project anyway. But you should anticipate how your writing and coding style might attract or discourage different types of people. The earliest stages of your project are your opportunity to set the precedent you wish to see.

## Your pre-launch checklist

Ready to open source your project? Here's a checklist to help. Check all the boxes? You're ready to go! [Click "publish"](https://help.github.com/articles/making-a-private-repository-public/) and pat yourself on the back.

**Documentation**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox1" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox1" class="overflow-hidden d-block text-normal">
    Project has a LICENSE file with an open source license
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    Project has basic documentation (README, CONTRIBUTING, CODE_OF_CONDUCT)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    The name is easy to remember, gives some idea of what the project does, and does not conflict with an existing project or infringe on trademarks
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    The issue queue is up-to-date, with issues clearly organized and labeled
  </label>
</div>

**Code**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    Project uses consistent code conventions and clear function/method/variable names
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    The code is clearly commented, documenting intentions and edge cases
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    There are no sensitive materials in the revision history, issues, or pull requests (ex. passwords or other non-public information)
  </label>
</div>

**People**

If you're an individual:

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  You've talked to the legal department and/or understand the IP and open source policies of your company (if you're an employee somewhere)
  </label>
</div>

If you're a company or organization:

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    You've talked to your legal department
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    You have a marketing plan for announcing and promoting the project
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    Someone is committed to managing community interactions (responding to issues, reviewing and merging pull requests)
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    At least two people have administrative access to the project
  </label>
</div>

## You did it!

Congratulations on open sourcing your first project. No matter the outcome, working in public is a gift to the community. With every commit, comment, and pull request, you're creating opportunities for yourself and for others to learn and grow.

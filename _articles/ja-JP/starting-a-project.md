---
locale: ja-JP
title: オープンソースプロジェクトを立ち上げる
description: オープンソースの世界をもっと理解し、自分のプロジェクトを立ち上げる準備をする
class: 初心者
toc:
  the-what-and-why-of-open-source: "The what and why of open source"
  should-i-launch-my-own-open-source-project: "Should I launch my own open source project?"
  launching-your-own-open-source-project: "Launching your own open source project"
  naming-and-branding-your-project: "Naming and branding your project"
  your-pre-launch-checklist: "Your pre-launch checklist"
order: 2
image: /assets/images/cards/beginner.png
---

## オープンソースとは何か、なぜオープンソースにするのか
## The "what" and "why" of open source

オープンソースで何かを始めたいと考えていますか？それは素晴らしい！世界中の人々が喜んでくれるでしょう。ではオープンソースとは何なのか、なぜオープンソースにするのか、お話しましょう。
So you're thinking about getting started with open source? Congratulations! The world appreciates your contribution. Let's talk about what open source is and why people do it.

### オープンソースとは何を意味するのか？
### What does "open source" mean?

プロジェクトがオープンソースであるとは何を意味するのかというと、そのプロジェクトが、**だれでも閲覧が可能で、利用し、変更を加え、再配布することができる、それもあらゆる目的のために**、ということになります。それらの許可は[オープンソースライセンス](https://opensource.org/licenses)によって保証されています。
When a project is open source, that means **anybody can view, use, modify, and distribute your project for any purpose.** These permissions are enforced through [an open source license](https://opensource.org/licenses).

オープンソースは強力なものです。というのは、オープンソースであるプロジェクトは採用しやすいからです。また、プロジェクトのアイディアを急速に広められるからです。
Open source is powerful because it lowers the barriers to adoption, allowing ideas to spread quickly.

オープンソースのはたらきをもっと理解するには、こんな想像をしてみましょう。友人から持ち寄りのパーティーに誘われ、あなたはチェリーパイを持参したとします。
To understand how it works, imagine your friend is having a potluck, and you bring a cherry pie.

* みんながチェリーパイを食べる (_利用する_)
* チェリーパイは大好評！彼らはチェリーパイの作り方を教えてもらう (_閲覧する_)
* パティシエである友人アレックスが、砂糖を減らすことを提案する (_変更する_)
* 別の友人リサがアレックスのレシピを気に入り、来週のディナーで使うことになる (_再配布する_)
* Everybody tries the pie (_use_)
* The pie is a hit! They ask you for the recipe, which you provide (_view_)
* One friend, Alex, who's a pastry chef, suggests reducing the sugar (_modify_)
* Another friend, Lisa, asks to use it for a dinner next week (_distribute_)

一方、ソースコードを公開しないプロセスを例えるなら、レストランでチェリーパイを注文するようなものです。代金がかかるうえに、レシピも教えてもらえないでしょう。レシピをそっくりマネして自分の店を出そうものなら、レストランに訴えられかねません。
By comparison, a closed source process would be going to a restaurant and ordering a slice of cherry pie. You must pay a fee to eat the pie, and the restaurant probably won't give you their recipe. If you copied their pie exactly and sold it under your own name, the restaurant could take action against you.

### なぜ人々は作ったものをオープンソースにするのか
### Why do people open source their work?

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/1500684?v=3&s=460" class="pquote-avatar" alt="avatar">
  私にとって最も満足の得られた経験。そのなかには、利用しているオープンソースプロジェクトでの共同作業から得たものがあります。それは、周りの開発者と信頼関係を築けたことです。彼らとともに開発をしているとき、私は多くの難しい問題で頭を抱えていたのですが、彼らも同じ困難に直面していたのです。
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["どうやってオープンソースは最高！と思えるようになったか"](https://medium.com/@kentcdodds/how-getting-into-open-source-has-been-awesome-for-me-8480cd756a80#.pjt9oqp4w)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/1500684?v=3&s=460" class="pquote-avatar" alt="avatar">
  One of the most rewarding experiences I get out of using and collaborating on open source comes from the relationships that I build with other developers facing many of the same problems I am.
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["How getting into Open Source has been awesome for me"](https://medium.com/@kentcdodds/how-getting-into-open-source-has-been-awesome-for-me-8480cd756a80#.pjt9oqp4w)
  </p>
</aside>

[理由はたくさんありますが](http://ben.balter.com/2015/11/23/why-open-source/) 、なぜ、個人にしろ組織にしろ、オープンソースでプロジェクトを始めようとするのでしょうか。いくつかの例を挙げると:
[There are many reasons](http://ben.balter.com/2015/11/23/why-open-source/) why a person or organization would want to open source a project. Some examples include:

* **他者との協力:** オープンソースプロジェクトは世界中のあらゆる人々からの変更を受け入れられます。 [Exercism](https://github.com/exercism/)の例でいえば、これはプログラミング教育プラットフォームですが、350人を超えるコントリビュータによって支えられています。
* **Collaboration:** Open source projects can accept changes from anybody in the world. [Exercism](https://github.com/exercism/), for example, is a programming exercise platform with over 350 contributors.

* **採用すること、混ぜ合わせること:** オープンソースプロジェクトはあらゆる人が使うことができます、目的の似ている人であれば。別のものを作るために利用することだってできます。例えば[WordPress](https://github.com/WordPress)、これはあるプロジェクトのフォークとして始まりました。あるプロジェクトとは、[b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md)と呼ばれるものです。
* **Adoption and remixing:** Open source projects can be used by anyone for nearly any purpose. People can even use it to build other things. [WordPress](https://github.com/WordPress), for example, started as a fork of an existing project called [b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md).

* **透明性:** あらゆる人がオープンソースプロジェクトのエラーや矛盾を検査できます。透明性が特に重要視されるのは政治であり、たとえば、[ブルガリア](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a)や[アメリカ](https://sourcecode.cio.gov/)のような国々です。あるいは、規制がなされる産業も同様で、たとえば銀行や医療産業などが挙げられます。ほかにも、セキュリティソフトウェアでも重要で、[Let's Encrypt](https://github.com/letsencrypt)のような例があります。
* **Transparency:** Anyone can inspect an open source project for errors or inconsistencies. Transparency matters to governments like [Bulgaria](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a) or the [United States](https://sourcecode.cio.gov/), regulated industries like banking or healthcare, and security software like [Let's Encrypt](https://github.com/letsencrypt).

オープンソースはソフトウェア以外の分野でも重要です。データセットから書籍まで、あらゆるものをオープンソースにすることができます。[GitHub Explore](https://github.com/explore)を見れば、オープンソース化できる様々なアイディアを得られるでしょう。
Open source isn't just for software, either. You can open source everything from datasets to books. Check out [GitHub Explore](https://github.com/explore) for ideas on what else you can open source.

### オープンソースとは「無料」を意味するのか？
### Does open source mean "free of charge"?

オープンソースの最大の特徴のひとつは、コストをかけずに利用できることです。しかし、「無料」であることはオープンソースの本質的な価値から生じた副産物にすぎません。
One of open source's biggest draws is that it does not cost money. "Free of charge", however, is a byproduct of open source's overall value.

[オープンソースライセンスが義務付けることがあります](https://opensource.org/osd-annotated)。同じような目的をもつあらゆる人たちに利用、修正、共有できるようにすることです。その義務付けにより、プロジェクト自体は無料になる傾向があります。なぜなら、もしプロジェクトを有料にしても、だれでも無料版のコピーを合法的に作ることができるので、普通に考えれば無料版を使うと思われるからです。
Because [an open source license requires](https://opensource.org/osd-annotated) that 
anyone can use, modify, and share your project for nearly any purpose, 
projects themselves tend to be free of charge. 
If the project cost money to use, anyone could legally make a copy and use the free version instead.

つまり、ほとんどのオープンソースプロジェクトは「自由」ではありますが、「無料」であることはオープンソースの定義に含まれていません。オープンソースプロジェクトを間接的に課金することは可能であり、たとえば２つのライセンスを適用したり、あるいは利用できる機能に制限をかけるなどをして、オープンソースの公式的なルールに則ったうえで課金することはできます。
As a result, most open source projects are free, but "free of charge" is not part of the open source definition. There are ways to charge for open source projects indirectly through dual licensing or limited features, while still complying with the official definition of open source.

## 私は自分でオープンソースプロジェクトを立ち上げるべきか？
## Should I launch my own open source project?

結論から言えば「イエス」です。なぜなら、結果を求められるわけではないからです。自分でオープンソースプロジェクトを立ち上げることが素晴らしいのは、オープンソースの仕組みをよく理解することができるということです。
The short answer is yes, because no matter the outcome, launching your own project is a great way to learn how open source works.

もしこれまでオープンソースプロジェクトを立ち上げたことがないなら、不安を感じているかもしれません。他者がどう反応するだろうか、あるいはだれも気づいてくれないのではないか、と。もしそうだとすれば、心配する必要はありません。あなたはひとりではないのですから！
If you've never open sourced a project before, you might be nervous about what people will say, or whether anyone will notice at all. If this sounds like you, you're not alone!

オープンソースの仕事というのは創造的な活動のようなもので、執筆業や絵画と似ています。自分で作ったものを世界中の人々に共有することは怖いかもしれませんが、その気持ちとうまく付き合う最良の方法は、実際にやってみることです。たとえ共有する相手がいなかったとしても。
Open source work is like any other creative activity, whether it's writing or painting. It can feel scary to share your work with the world, but the only way to get better is to practice - even if you don't have an audience.

もし確信が持てないとしても、少し考えてみてください。あなたのゴールをどこに設定しますが？
If you're not yet convinced, take a moment to think about what your goals might be.

### ゴールを設定する
### Setting your goals

ゴールを設定することは、自分が何をやろうとしているのか理解する助けになるでしょう。また、何をやらないのか、どういう部分で他者の助けが必要なのか理解することにもなります。自分自身に問いかけることから始めましょう。_なぜこのプロジェクトをオープンソースにするのでしょうか？_
Goals can help you figure out what to work on, what to say no to, and where you need help from others. Start by asking yourself,  _why am I open sourcing this project?_

ひとつの絶対的な答えがあるわけではありません。プロジェクトに複数のゴールが存在することはありえますし、ゴールに応じていくつかのプロジェクトを持っているかもしれません。
There is no one right answer to this question. You may have multiple goals for a single project, or different projects with different goals.

自分の作品を見せびらかしたいだけなら、他者からのコントリビュートを望まないかもしれませんし、READMEにそう書くかもしれません。一方、他者からのコントリビュートを得たい、時間をかけてドキュメントを分かりやすくして興味を持ってくれた他者を歓迎したい、と考えるかもしれません。
If your only goal is to show off your work, you may not even want contributions, and even say so in your README. On the other hand, if you do want contributors, you'll invest time into clear documentation and making newcomers feel welcome.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/3520168?v=3&s=460" class="pquote-avatar" alt="avatar">
  ある時期に、私はUIAlertViewを自分でカスタマイズして使っていたのですが...、これをオープンソースにしようと決断しました。そして、よりダイナミックなものに修正して、GitHubにアップロードしました。また、開発者の人々に使ってもらうために、使い方を説明したドキュメントを初めて書きました。とても簡単なプロジェクトだったので、おそらく誰も使わなかったと思います。しかし、自分のプロジェクトをオープンソースで公開したことに、私は満足感を覚えました。
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

プロジェクトが成長するにつれて、そのコミュニティはあなたのコードだけではなく、ほかのタスクも必要になってきます。イシューに返信すること、コードをレビューすること、プロジェクトの存在を広めること、それら全てがプロジェクトにとって重要なタスクとなります。
As your project grows, your community may need more than just code from you. Responding to issues, reviewing code, and evangelizing your project are all important tasks in an open source project.

上記のコーディングしないタスクに、どれだけの時間を費やせば良いでしょうか。それは、プロジェクトの大きさと範囲によって決まります。コーディングしないタスクに取り組む役割のことをメンテナといいますが、あなたはメンテナになる準備を進めるべきです。あるいは、ひとりでメンテナの役割を担うのが大変ということであれば、あなたを助けてくれる人を探しましょう。
While the amount of time you spend on non-coding tasks will depend on the size and scope of your project, you should be prepared as a maintainer to address them yourself or find someone to help you.

**もしあなたがオープンソースプロジェクトを運営する会社のメンバーだとしたら**、知っておかなければならないことがあります。そのプロジェクトを成長させるためには、社内リソースが必要になるということです。プロジェクト公開後のメンテナンスに誰が責任をもつのか明確化したり、これまであなたが担当していたタスクを社内メンバーにどう共有するか考えることになります。
**If you're part of a company open sourcing a project,** make sure your project has the internal resources it needs to thrive. You'll want to identify who's responsible for maintaining the project after launch, and how you'll share those tasks with your community.

プロジェクトを広めたり、メンテナンスするのには予算や人員が必要になるかもしれません。そうであるなら、上記の社内での話し合いは、できるだけ早めにやったほうが良いです。
If you need a dedicated budget or staffing for promotion, operations and maintaining the project, start those conversations early.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1857993?v=3&s=460" class="pquote-avatar" alt="avatar">
  あなたがオープンソースプロジェクトを始めるにあたり、非常に重要なことがあります。それはプロジェクト管理プロセスをよく考えるということなのですが、プロジェクト周辺のコミュニティにいるコントリビュータの人々や彼らの技能について配慮するということです。恐れずにコントリビュータを巻き込みましょう。たとえ彼らを雇用しておらずビジネス的な関係を結んでいないとしても、それはプロジェクトの重要な側面に影響するわけではありません。特に彼らが頻繁にコントリビュートしてくれる人々であれば、なおさらです。
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

もしあなたのゴールが、どのように他者と協働すればよいか学ぶこと、あるいはオープンソースがどのようにはたらくか理解することだとすれば、既存のプロジェクトに貢献してみるのはどうでしょうか。すでに利用していて、愛着の湧くプロジェクトで始めるのが良いでしょう。プロジェクトにコントリビュートするというのは、誤字を直すことやドキュメントをアップデートするようなシンプルなことでも歓迎されます。
If your goal is to learn how to collaborate with others or understand how open source works, consider contributing to an existing project. Start with a project that you already use and love. Contributing to a project can be as simple as fixing typos or updating documentation.

コントリビュータとしてどのように始めればよいか分からない場合、[どうやってオープンソースに貢献するか](../how-to-contribute/)をチェックしてみてください。
If you're not sure how to get started as a contributor, check out our [How to Contribute to Open Source guide](../how-to-contribute/).

## 自分のオープンソースプロジェクトを立ち上げる
## Launching your own open source project

オープンソースプロジェクトを立ち上げるのに十分な時間というものは、存在しません。あなたはアイディアをオープンソースにすることができますが、その作業は実はすでに進行しているか、あるいは数年の間クローズドソースでいた後にオープンソースとなるのです。
There is no perfect time to open source your work. You can open source an idea, a work in progress, or after years of being closed source.

一般的にプロジェクトをオープンソース化すべき状況とは、どうのような状況でしょうか。それは、プロジェクトを他者から見られて気持ち良いと思える場合か、フィードバックをもらいたいという場合です。
Generally speaking, you should open source your project when you feel comfortable having others view, and give feedback on, your work.

プロジェクトのオープンソース化を決心できたかどうかに関わらず、あらゆるプロジェクトには以下のドキュメントが用意されているべきです。
No matter which stage you decide to open source your project, every project should include the following documentation:

* [Open source license](https://help.github.com/articles/open-source-licensing/#where-does-the-license-live-on-my-repository)
* [README](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
* [Contributing guidelines](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
* [Code of conduct](../code-of-conduct/)

メンテナとして、これらのコンポーネントは次のようなことについてあなたを助けてくれるでしょう。あなたが最終的にやりたいことを明確化すること、コントリビューションを管理すること、あなた自身を含むあらゆる人々の法的な権利を守ること、についてです。上記のドキュメントを用意することによって、あなたが得られる経験はより意義深いものになるでしょう。
As a maintainer, these components will help you communicate expectations, manage contributions, and protect everyone's legal rights (including your own). They significantly increase your chances of having a positive experience.

もしプロジェクトがGitHubにあるなら、それらのファイルを推奨されたファイル名にしてrootディレクトリに設置すると良いでしょう。そうすれば、GitHubはそれを認識して自動的にあなたを購読している人々に知らせてくれるでしょう。
If your project is on GitHub, putting these files in your root directory with the recommended filenames will help GitHub recognize and automatically surface them to your readers.

### ライセンスを選ぶ
### Choosing a license

オープンソースライセンスは次のことを保証します。他者がそのプロジェクトを利用、複製、修正、そしてプロジェクトに貢献し返してくれる場合などに発生しうる、アクシデントの影響をなくしてくれます。法的に面倒な状況からも、あなたを守ってくれます。**オープンソースプロジェクトを立ち上げる場合には、必ずライセンスを含めなければなりません。**
An open source license guarantees that others can use, copy, modify, and contribute back to your project without repercussions. It also protects you from sticky legal situations. **You must include a license when you launch an open source project.**

法律に関する仕事は楽しいものではありません。しかし、良いニュースがあるとすれば、既存のライセンスをコピー&ペーストして良いということです。つまり、あなたが多大な労力をかけて作ったプロジェクトを、ほんの短時間で守ることができるということです。
Legal work is no fun. The good news is that you can copy and paste an existing license into your repository. It will only take a minute to protect your hard work.

[MIT](https://choosealicense.com/licenses/mit/)、[Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)、[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)は、もっとも人気のあるオープンソースライセンスですが、[その他のオプション](https://choosealicense.com)も選択することができます。
[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) are the most popular open source licenses, but [there are other options](https://choosealicense.com) to choose from.

あなたが新しいプロジェクトをGitHub上で作成するなら、どのライセンスを選択するか選ぶオプションが表示されます。オープンソースライセンスを含めることは、あなたのGitHubプロジェクトをオープンソースにすることを意味します。
When you create a new project on GitHub, you are given the option to select a license. Including an open source license will make your GitHub project open source.

![ライセンスを選ぶ](/assets/images/starting-a-project/repository-license-picker.png)
![pick a license](/assets/images/starting-a-project/repository-license-picker.png)

その他に質問がある場合や、オープンソースプロジェクトの運営するうえでの法的な側面に興味があるなら、[こちらのページで案内しています](../legal/)。
If you have other questions or concerns around the legal aspects of managing an open source project, [we've got you covered](../legal/).

### READMEを書く
### Writing a README

READMEが重要なのは、プロジェクトの使い方を説明するだけではありません。なぜあなたのプロジェクトが重要なのか、プロジェクト利用者がどんなことをできるようになるか、ということも説明します。
READMEs do more than explain how to use your project. They also explain why your project matters, and what your users can do with it.

READMEに何を書けばよいかということですが、以下の質問に対する回答を書いてください:
In your README, try to answer the following questions:

* このプロジェクトは何をやっているのか？
* なぜこのプロジェクトが役に立つのか？
* どうやって使い始めればよいのか？
* 詳しいヘルプを知りたくなったとき、どこを見ればよいか？
* What does this project do?
* Why is this project useful?
* How do I get started?
* Where can I get more help, if I need it?

他の質問に関する回答を書いても良いでしょう。たとえば、コントリビューションをどう扱うのか、プロジェクトのゴールはどう設定されているのか、ライセンスと帰属に関する情報、など。もしあなたがコントリビュータを受け入れたくない場合や、実用的な形としてまだ仕上がっていない場合には、それらの情報もREADMEに書いておきましょう。
You can use your README to answer other questions, like how you handle contributions, what the goals of the project are, and information about licenses and attribution. If you don't want to accept contributions, or your project is not yet ready for production, write this information down.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  良いドキュメンテーションが意味するものとは、より多くのユーザーがいて、より少ないサポートで、より多くのコントリビュータがいる、ということです。忘れてはいけないことは、そのドキュメントを読んでいる人たちは、あなたではないということです。プロジェクトに訪れてくれたその人たちは、あなたとは全く異なる経験をしてきた人々なのです。
  <p markdown="1" class="pquote-credit">
— @limedaring, ["自分が書いた言葉を誰かに読んでもらうために（動画）"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  Better documentation means more users, less support requests, and more contributors. (...) Remember that your readers aren't you. There are people who might come to a project who have completely different experiences.
  <p markdown="1" class="pquote-credit">
— @limedaring, ["Writing So Your Words Are Read (video)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

ときどき、READMEを書かないようにしている人々がいます。プロジェクトがまだ完成していないから、あるいはコントリビューションを望んでいないから、と思っているようです。しかし、実はそのような状況は、READMEを書くにはとても良い機会なのです。
Sometimes, people avoid writing a README because they feel like the project is unfinished, or they don't want contributions. These are all very good reasons to write one.

もっとインスピレーションが必要ということであれば、@18Fの["READMEをより読みやすくする"](https://pages.18f.gov/open-source-guide/making-readmes-readable/)や、@PurpleBoothの[READMEテンプレート](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)を参照して、より理想に近いREADMEを書いてみましょう。
For more inspiration, try using @18F's ["Making READMEs Readable"](https://pages.18f.gov/open-source-guide/making-readmes-readable/) or @PurpleBooth's [README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) to write a complete README.

READMEファイルをプロジェクトのrootディレクトリに置けば、GitHubは自動的にリポジトリのホームに表示してくれます。
When you include a README file in the root directory, GitHub will automatically display it on the repository homepage.

### コントリビュートのガイドラインを書く
### Writing your contributing guidelines

CONTRIBUTINGファイルとは、あなたのプロジェクトを見ている人に、どうすればそのプロジェクトに参加できるのかを伝えるものです。たとえば、以下のような情報です:
A CONTRIBUTING file tells your audience how to participate in your project. For example, you might include information on:

* どうやってバグリポートを提出するか（[イシューとプルリクエストのテンプレート](https://github.com/blog/2111-issue-and-pull-request-templates)を使ってください）
* どうやって新しい機能を提案するか
* どうやって環境設定を行い、テストを行うか
* How to file a bug report (try using [issue and pull request templates](https://github.com/blog/2111-issue-and-pull-request-templates))
* How to suggest a new feature
* How to set up your environment and run tests

技術的な詳細に加えて、CONTRIBUTINGファイルはどんなことをコントリビュートしてほしいのか伝えます。たとえば:
In addition to technical details, a CONTRIBUTING file is an opportunity to communicate your expectations for contributions, such as:

* どのような種類のコントリビューションをしてほしいか
* 今後のロードマップやビジョン
* どのような手段であなたに連絡を取るべきか（取るべきでないか）
* The types of contributions you're looking for
* Your roadmap or vision for the project
* How contributors should (or should not) get in touch with you

温かい心をもって、友好的な口調で、やってほしいコントリビューションを具体的に伝えましょう（たとえばドキュメンテーションを書くこと、ウェブサイトを作ること）。これからの長い道のりを、新しく参加してくれた人々は、歓迎されている喜びを感じながら、ワクワクした気持ちでプロジェクトに参加することができる。
Using a warm, friendly tone and offering specific suggestions for contributions (such as writing documentation, or making a website) can go a long way in making newcomers feel welcomed and excited to participate.

たとえば、[Active Admin](https://github.com/activeadmin/activeadmin/)は[コントリビューションのガイド](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md)をこんな文章で書き始めています:
For example, [Active Admin](https://github.com/activeadmin/activeadmin/) starts [its contributing guide](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) with:

> まずはじめに、あなたに感謝の気持ちを伝えたい。Active Adminへのコントリビュートを検討してくれてありがとう。あなたのような人々が、Active Adminをすばらしいツールにしてくれるのだ。
> First off, thank you for considering contributing to Active Admin. It's people like you that make Active Admin such a great tool.

プロジェクト最初期の段階では、CONTRIBUTINGファイルはシンプルなものでしょう。あなたが常に説明すべきことですが、どうやってバグレポートを提出するか、技術的な必要条件（たとえばテスト）にどのようなものがあるか、ということをコントリビュータに伝えなければなりません。
In the earliest stages of your project, your CONTRIBUTING file can be simple. You should always explain how to report bugs or file issues, and any technical requirements (like tests) to make a contribution.

プロジェクト開始からある程度の時期が経ったら、よくある質問をCONTRIBUTINGファイルに書くと良いでしょう。この情報を書くことで、何度も同じ内容の質問をされることを回避できます。
Over time, you might add other frequently asked questions to your CONTRIBUTING file. Writing down this information means fewer people will ask you the same questions over and over again.

CONTRIBUTINGファイルの書き方でもっとヘルプが必要であれば、@nayafiaの[コントリビューションガイドのテンプレート](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) 、あるいは@mozillaの ["どうやってCONTRIBUTING.mdを書くか"](http://mozillascience.github.io/working-open-workshop/contributing/)が助けになるでしょう。
For more help with writing your CONTRIBUTING file, check out @nayafia's [contributing guide template](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) or @mozilla's ["How to Build a CONTRIBUTING.md"](http://mozillascience.github.io/working-open-workshop/contributing/).

リンクをREADMEからCONTRIBUTINGファイルに貼っておくことで、より多くの人びとに見てもらうことができます。もし[CONTRIBUTINGファイルをあなたのプロジェクトのリポジトリに置いたら](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)、GitHubは自動的にリンクをあなたのファイルに貼ってくれますが、それはコントリビュータがイシューを作成した時、あるいはプルリクエストを開いたときに貼られます。
Link to your CONTRIBUTING file from your README, so more people see it. If you [place the CONTRIBUTING file in your project's repository](https://help.github.com/articles/setting-guidelines-for-repository-contributors/), GitHub will automatically link to your file when a contributor creates an issue or opens a pull request.

![コントリビューションガイドライン](/assets/images/starting-a-project/Contributing-guidelines.jpg)
![contributing guidelines](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### Code of Conductを制定する
### Establishing a code of conduct

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/11214?v=3&s=460" class="pquote-avatar" alt="avatar">
  私たちはみな、嫌な思いをした経験があります。それは、メンテナの立場としてあるやり方がなぜそうなっているのか説明させられたことであり、あるいは、ユーザの立場として(...)すぐに分かりそうな簡単な質問を誰かにしてしまったということです。みな、その両方を経験したことがあるでしょう。(...)Code of Conductを簡単に参照でき、リンク可能な状態にしておくことで、あなたのチームは上記のような不毛な経験を回避し、建設的な会話に集中できるようになるでしょう。
  <p markdown="1" class="pquote-credit">
— @mlynch, ["オープンソースをもっと幸せな場所にする"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f#.v4qhl7t7v)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/11214?v=3&s=460" class="pquote-avatar" alt="avatar">
  We’ve all had experiences where we faced what was probably abuse either as a maintainer trying to explain why something had to be a certain way, or as a user...asking a simple question. (...) A code of conduct becomes an easily referenced and linkable document that indicates that your team takes constructive discourse very seriously.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["Making Open Source a Happier Place"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f#.v4qhl7t7v)
  </p>
</aside>

最終的に、Code of Conductはどういう振る舞いをして良いかというルールの基盤をつくり、プロジェクト参加者に提供します。これが特に役に立つのは、あなたがコミュニティや会社のためにオープンソースプロジェクトを立ち上げるときです。Code of Conductはあなたに権限を与えることを意味し、健康的かつ建設的にコミュニティ上で振る舞うようにはたらきかけることで、メンテナとしてのストレスを軽減させるでしょう。
Finally, a code of conduct helps set ground rules for behavior for your project's participants. This is especially valuable if you're launching an open source project for a community or company. A code of conduct empowers you to facilitate healthy, constructive community behavior, which will reduce your stress as a maintainer.

もっと詳しい情報が必要であれば、[Code of Conductガイド](../code-of-conduct/)を参照してください。
For more information, check out our [Code of Conduct guide](../code-of-conduct/).

コミュニケーションに加えて、_どうやって_あなたが期待することを参加者に行ってもらうかということですが、Code of Conductは次のようなことを伝えるのに役立ちます。Code of Conductの対象が誰なのか、いつ適用されるのか、もし違反が起きた時にどう対処すればよいのか、ということです。
In addition to communicating _how_ you expect participants to behave, a code of conduct also tends to describe who these expectations apply to, when they apply, and what to do if a violation occurs.

オープンソースライセンスと同様に、Code of Conductは近年に新しく作られた決まりであり、あなたが自分で書く必要はありません。[Contributor Covenant](http://contributor-covenant.org/)はCode of Conductの溜まり場のようなもので、これは[40,000以上のオープンソースプロジェクト](http://contributor-covenant.org/adopters/)に使われていて、Kubernetes、Rails、Swiftなどでも利用されています。仮にこのテキストを利用しなかったとしても、施行するCode of Conductは必要に応じて用意すべきです。
Much like open source licenses, there are also emerging standards for codes of conduct, so you don't have to write your own. The [Contributor Covenant](http://contributor-covenant.org/) is a drop-in code of conduct that is used by [over 40,000 open source projects](http://contributor-covenant.org/adopters/), including Kubernetes, Rails, and Swift. No matter which text you use, you should be prepared to enforce your code of conduct when necessary.

そのテキストを直接ペーストしてください。リポジトリの中にあるCODE_OF_CONDUCTファイルの中に。CODE_OF_CONDUCTファイルはプロジェクトのrootディレクトリに置き、見つけやすいようにし、そしてREADMEからリンクしやすいようにしておきましょう。
Paste the text directly into a CODE_OF_CONDUCT file in your repository. Keep the file in your project's root directory so it's easy to find, and link to it from your README.

## プロジェクト名とブランド戦略
## Naming and branding your project

ブランド戦略とは、華やかなロゴや人気を呼びそうなプロジェクト名をつける、ということだけにとどまりません。プロジェクトをどのように紹介するかということであり、どのような人々に届けたいのかという意味をもっています。
Branding is more than a flashy logo or catchy project name. It's about how you talk about your project, and who you reach with your message.

### 正しい名前を選ぶ
### Choosing the right name

覚えやすい名前を選ぶことが重要であり、理想的には、何をするプロジェクトなのか伝えることができればなお良いでしょう。たとえば:
Pick a name that is easy to remember and, ideally, gives some idea of what the project does. For example:

* [Sentry](https://github.com/getsentry/sentry) アプリのクラッシュを監視してレポートを送る
* [Thin](https://github.com/macournoyer/thin) 速くてシンプルなRuby製のWebサーバ
* [Sentry](https://github.com/getsentry/sentry) monitors apps for crash reporting
* [Thin](https://github.com/macournoyer/thin) is a fast and simple Ruby web server

もし既存プロジェクトのうえに乗ったプロジェクトを立ち上げるなら、既存プロジェクトの名前を接頭辞として用いれば、何をするプロジェクトなのかを理解する助けになるでしょう。（例: [node-fetch](https://github.com/bitinn/node-fetch)はwindow.fetchをNode.jsにもたらしてくれます）
If you're building upon an existing project, using their name as a prefix can help clarify what your project does (ex. [node-fetch](https://github.com/bitinn/node-fetch) brings `window.fetch` to Node.js).

何よりも明瞭さを考慮してください。語呂合わせで名前を決めることは楽しいですが、それ以上に重要なことは、ジョークは異なる文化や異なる経験をして育ってきた人々にとって、翻訳できない可能性があるということです。潜在的なユーザのなかには会社に雇われている人びともいるかもしれません。彼らを不快な気持ちにさせるつもりはなかったとしても、彼らは仕事中に真面目な顔でジョークを含んだプロジェクトのことを説明しなければならないのですよ！
Consider clarity above all. Puns are fun, but remember that some jokes might not translate to other cultures or people with different experiences from you. Some of your potential users might be company employees: you don't want to make them uncomfortable when they have to explain your project at work!

### 別プロジェクトと同じ名前にしない
### Avoiding name conflicts

ほかのオープンソースプロジェクトに似たような名前がないか確認してください。特に、同じ言語やエコシステムを共有している場合には。もし既存の人気プロジェクトと重複していたら、利用者を混乱させることになってしまいます。
Check for open source projects with a similar name, especially if you share the same language or ecosystem. If your name overlaps with a popular existing project, you might confuse your audience.

ウェブサイト、ツイッターのハンドルネーム、あるいはその他の資産を用いてプロジェクトを広めたいと思うなら、欲しい名前を取得することができるか確認しておきましょう。できることなら、平静な気持ちで、[すぐに確保しましょう](https://instantdomainsearch.com/) 。たとえ、いますぐ使う予定がなかったとしても。
If you want a website, Twitter handle, or other properties to represent your project, make sure you can get the names you want. Ideally, [reserve those names now](https://instantdomainsearch.com/) for peace of mind, even if you don't intend to use them just yet.

重要なことですが、プロジェクト名は商標権を犯してはいけません。あなたの会社にプロジェクトを停止させられるかもしれませんし、法的な行動を取られるかもしれません。不必要なリスクは避けましょう。
Make sure that your project's name doesn't infringe upon any trademarks. A company might ask you to take down your project later on, or even take legal action against you. It's just not worth the risk.

[WIPO Global Brand Database](http://www.wipo.int/branddb/en/)を見れば、重複したトレードマークがないか調べることができます。もし会社としてオープンソースプロジェクトを立ち上げようとしているのであれば、[貴社の法務チームが助けてくれることは様々ありますが](../legal/)、商法違反がないか調べることはそのうちのひとつです。
You can check the [WIPO Global Brand Database](http://www.wipo.int/branddb/en/) for trademark conflicts. If you're at a company, this is one of the things your [legal team can help you with](../legal/).

最後に、プロジェクト名をGoogle検索してみましょう。これからプロジェクトを利用する人たちは、簡単にプロジェクトを見つけることができそうですか？もし検索結果一覧に、関係のないウェブサイトがたくさん表示されているとしたら、見つけにくくなりますよね？
Finally, do a quick Google search for your project name. Will people be able to easily find your project? Does something else appear in the search results that you wouldn't want them to see?

### 言葉遣いやコーディングスタイルが、ブランドにも影響を与える！
### How you write (and code) affects your brand, too!

プロジェクトの至るところで、何かを書くことになります。たとえば、README、チュートリアル、コミュニティのドキュメント、イシューへの返信、あるいはニュースレターやメーリングリストへの投稿など。
Throughout the life of your project, you'll do a lot of writing: READMEs, tutorials, community documents, responding to issues, maybe even newsletters and mailing lists.

公式なドキュメントであるか、カジュアルなメールなのかに関わらず、あなたがどのような書き方をするかということはプロジェクトのブランドに影響を与えるのです。考えてみてください。プロジェクトを訪問してくれた人があなたの振る舞いを見たとき、どういう印象を持つでしょうか？あなたが伝えようとしていることが、適切な言葉で表現されているでしょうか？
Whether it's official documentation or a casual email, your writing style is part of your project's brand. Consider how you might come across to your audience and whether that is the tone you wish to convey.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/11321?v=3&s=460" class="pquote-avatar" alt="avatar">
  メーリングリストに投稿されるすべてのスレッドに投稿するよう努力し、規範となるような振る舞いをし、親切な受け答えを心がけ、イシューに真摯に返信し、あらゆる場面で誰かの役に立つように心がけました。すると、周りの人々は質問をするだけでなく、別の人の質問に答えて手助けをするようになったのです。私は大きな喜びを感じました。コミュニティにいる人々は、私のやり方のまねをしたのです。
  <p markdown="1" class="pquote-credit">
— @janl on [CouchDB](https://github.com/apache/couchdb), ["持続可能なオープンソース"](http://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>
<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/11321?v=3&s=460" class="pquote-avatar" alt="avatar">
  I tried to be involved with every thread on the mailing list, and showing exemplary behaviour, being nice to people, taking their issues seriously and trying to be helpful overall. After a while, people stuck around not to only ask questions, but to help with the answering as well, and to my complete delight, they mimicked my style.
  <p markdown="1" class="pquote-credit">
— @janl on [CouchDB](https://github.com/apache/couchdb), ["Sustainable Open Source"](http://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

温かい気持ちで、他者を巻き込むような言葉遣いをすること（たとえば「彼ら」のような言葉を用いること。たとえ特定の誰かに言及するような場合であっても）は、プロジェクトを運営していく長い期間に渡って、新しいコントリビュータを歓迎する雰囲気を作ってくれます。これは、ある言語に限ったことではなく、英語ネイティブでない人々についても同じことが言えます。
Using warm, inclusive language (such as "them", even when referring to the single person) can go a long way in making your project feel welcoming to new contributors. Stick to simple language, as many of your readers may not be native English speakers.

どういう言葉で表現するかということ以上に、あなたのコーディングスタイルも同様にプロジェクトのブランドの一部となっていくでしょう。[Angular](https://github.com/johnpapa/angular-styleguide)や[jQuery](http://contribute.jquery.org/style-guide/js/)は、厳格なコーディングスタイルとガイドラインを持つ事例です。
Beyond how you write words, your coding style may also become part of your project's brand. [Angular](https://github.com/johnpapa/angular-styleguide) and [jQuery](http://contribute.jquery.org/style-guide/js/) are two examples of projects with rigorous coding styles and guidelines.

スタイルガイドを用意する必要性ですが、プロジェクトが始まったばかりの頃は必要というわけではありませんし、むしろコーディングスタイルの違いにおもしろさを感じるかもしれません。しかし、事前に予測しておくことは重要ですから、あなたの言葉遣いやコーディングスタイルが、他者を魅了したり、あるいはやる気を削ぐ可能性があることは頭に入れておくべきです。プロジェクト最初期の段階というのは、あなたが見たいようにできる良い機会です。
It isn't necessary to write a style guide for your project when you're just starting out, and you may find that you enjoy incorporating different coding styles into your project anyway. But you should anticipate how your writing and coding style might attract or discourage different types of people. The earliest stages of your project are your opportunity to set the precedent you wish to see.

## ローンチ直前のチェックリスト
## Your pre-launch checklist

プロジェクトをオープンソース化する用意はできていますか？このチェックリストが役に立つでしょう。すべての項目にチェックが入りましたか？では準備OKです！["publish"をクリック](https://help.github.com/articles/making-a-private-repository-public/) して、自分を褒めてあげましょう。
Ready to open source your project? Here's a checklist to help. Check all the boxes? You're ready to go! [Click "publish"](https://help.github.com/articles/making-a-private-repository-public/) and pat yourself on the back.

**ドキュメンテーション**
**Documentation**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox1" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox1" class="overflow-hidden d-block text-normal">
    LICENSEファイルが用意されていて、その中にはオープンソースライセンスが含まれている
    Project has a LICENSE file with an open source license
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    基本となるドキュメンテーションが用意されている（README、CONTRIBUTING、CODE_OF_CONDUCT）
    Project has basic documentation (README, CONTRIBUTING, CODE_OF_CONDUCT)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    プロジェクト名が、覚えやすい名前になっている。何をするプロジェクトなのか推測しやすい。そして、ほかのプロジェクトと名前が重複したり商標権の違反をしていない
    The name is easy to remember, gives some idea of what the project does, and does not conflict with an existing project or infringe on trademarks
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    イシューが最新の状態になっていて、ラベル付けされるなど整然とまとまっている
    The issue queue is up-to-date, with issues clearly organized and labeled
  </label>
</div>

**コード**
**Code**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    コードの書き方に一貫性があり、function/method/variableの名前が分かりやすく書かれている
    Project uses consistent code conventions and clear function/method/variable names
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    コードを補完するコメントが書かれていて、そのコードが書かれた意図やエッジケースについて説明されている
    The code is clearly commented, documenting intentions and edge cases
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    機密情報がリビジョン履歴、イシュー、プルリクエストに残っていない（例: パスワードや公開したくない情報など）
    There are no sensitive materials in the revision history, issues, or pull requests (ex. passwords or other non-public information)
  </label>
</div>

**人**
**People**

個人としてオープンソース化する場合:
If you're an individual:

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  法務チームからオープンソース化することの許可を得ていて、かつ（または）、知的財産やオープンソースポリシーについてあなたの会社にすでに相談済みである（もしあなたが会社や組織に雇用されている立場なら）
  You've talked to the legal department and/or understand the IP and open source policies of your company (if you're an employee somewhere)
  </label>
</div>

会社や組織としてオープンソース化する場合:
If you're a company or organization:

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    法務チームからオープンソース化することの許可を得ている
    You've talked to your legal department
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    マーケティングプランは計画済みであり、どう告知するか、どうプロモーションするか明確に考えられている
    You have a marketing plan for announcing and promoting the project
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    プロジェクトの担当者がすでに決定していて、コミュニティ上のやりとりを管理することになっている（たとえばイシューへの返信、レビュー、プルリクエストのマージなど）
    Someone is committed to managing community interactions (responding to issues, reviewing and merging pull requests)
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    少なくとも2人以上の組織内の人が、プロジェクトの管理者権限をもっている
    At least two people have administrative access to the project
  </label>
</div>

## すべて完了です！
## You did it!

おめでとうございます！初めてのオープンソースプロジェクトは、これで公開されました。結果がどうなるとしても、他者に開かれたかたちで何かを作るということは、コミュニティにとって大きなプレゼントになるのです。あらゆるコミット、コメント、プルリクエストは、あなたの成長の機会となるだけでなく、他者が学ぶ機会でもあるのです。そして、その機会はまさに、あなたの手によって作られているのです。
Congratulations on open sourcing your first project. No matter the outcome, working in public is a gift to the community. With every commit, comment, and pull request, you're creating opportunities for yourself and for others to learn and grow.

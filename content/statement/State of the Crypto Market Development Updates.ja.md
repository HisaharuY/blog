+++
title = "State of the Crypto Market and Development Updates"
tags = [
    "Development",
    "Wallet Development",
    "CoinHours",
    "CX",
    "Roadmap",
    "Statement",
    "Bitcoin",
]
bounty = 15
date = "2017-10-14"
categories = [
    "Statement",
    "Development Updates",
]
+++

- [Q&A](#q-a)
- [ビットコイン市場の現状](#summary-of-the-current-bitcoin-market)
- [New Wallet](#new-wallet)
- [CoinHours](#coinhours)
- [Skycoin \(DEX\) Distributed Exchange Support](#skycoin-dex-distributed-exchange-support)
- [Skycoin Projects Position on the Smart Contracts Fad](#skycoin-projects-position-on-the-smart-contracts-fad)
- [CX](#cx)
- [Skycoin Roadmap Finished](#skycoin-roadmap-finished)
- [First Distributed Social Media Platform on Skycoin Platform Launches](#first-distributed-social-media-platform-on-skycoin-platform-launches)
- [Skycoin OTC Market](#skycoin-otc-market)

## Q&A

>ホワイトペーパーに関する進捗状況を知りたいです。
>市場公開が既に始まっているため、参考資料作成を優先するよう希望します。
>技術が特徴のコインなので、最新の状況を知らせてください。

関係者の作業の関係で対応が遅くなっています。

今後の予定としては、テクニカルライターに依頼して、コンテンツを作成し、記事を公開していく予定です。

>なぜ小数点以下のコインが出金できないのでしょうか。
>他のコインの場合、小数点以下6～8桁の対応が可能だと思います。

小数点第1桁のコインとした場合、単位は0.3ドル（約33円）となります。

今後、Skycoinが10ドルになった時点で、小数点第2桁の使用を可能にする予定です。なお状況により小数点以下最大6桁まで拡張が将来可能です。

現在、少額のスパム送信や、ジャンク取引によるブロックチェーンの肥大化を避けるためこのような設定にしています。

>なぜTelegramとSlack channelを閉鎖しないのでしょうか。
>意見の一致が見られていないようですが。

意見の対立はとくに発生していません。また、Slack はあまり使用されていない状況です。

我々にはSkyメッセンジャーと、独自のメッセージプラットフォームがありますので、最終的にはそちらへ移行したいと考えています。

我々はその他に、BBSとソーシャルメディアプラットフォームも現在活用しています。

>Telegramはうまく機能していないようです。Slackのニュースにアクセスはできますが、メインのSlackやBBSには入れません。

Telegramはスパム回避のため、英語圏以外の国のユーザを禁止しています。対応として、Google voice numberを使用してください。

>アルトコインやビットコイン等は、別の市場へ移行するのではないでしょうか。

確かにそのとおりです。

ユーザがいない市場でうまく機能しないプラットフォームで何十億円も取引されている例があります。ビットコインは来年３月には1万ドルに達するかもしれません。

## ビットコイン市場の現状　Summary of the Current Bitcoin Market　

仮想通貨市場の裏側で何が起こっているのか、我々が議論した内容を紹介します。

仮想通貨の価格や市場規模は日々変化していますが、この市場へ流入する資金量や人々の関心は、ますます増える一方です。

ところが現在この市場には、本物の正真正銘のコインは“ほとんど存在しない”という状況であると我々は考えています。ウエブサイトが素晴らしく、重厚なアドバイザリーボード(顧問団)が控えているように見えるコインが多くあります。そして、ICOによって何百億円もの資金を集めています。

しかし、これらのほとんどの多くのコインは、ソフトウエア開発チームがなく、またはチームを編成し運営する能力もなく、ソフトを設計、デザインすることさえできない状況です。

一方、彼らはマーケティングを得意としています。ソフト開発ではなく、100%の能力をマーケティングに注力します。その背後でプロジェクトの実務担当グループはうまく機能していません。

開発部隊のいないプロジェクトであっても、かなりの資金を集め、「オープンソースのソフトではない(誰にも確認できない)」と宣言し、「AI(人工知能)が完成した。」とさえ言います。そして人工知能による学習システムを完成させます。(こりゃなんだ？！)　そして、本当に彼ら自身がプログラムしたのかどうか、完成したシステムが動作するかどうかなんて、誰にもわからないのです。

本物のプロジェクトに、巨大な資金が急速に流れ込む、というのは極めて稀でしかありません。

皆が何か特別に目立つコインに殺到しているような時に、ほとんど誰も気づいていない本物のプロジェクトに投資できる時というのは、とても短い間だけです。


コインが市場で受け入れられる前に、一般向けに低価格で事前販売するという期間が設けられる場合がありました。これは例えば何年もの期間でした。（LitecoinやBitcoin等）

最近では、Byteball等のように、数円から8万円程に爆発的に上昇するまでに数か月ほどの場合もあります。そして、この速度はどんどん短くなってきています。

Cardanoのような例では、全てのコインがインサイダー(内部関係者)により事前に販売されます。そして、どこからともなく、突然トップ15位にランク入りするのです。このような場合、コミュニティーの中で売買されるという準備期間がありません。彼らはインサイダーにコインを売り、最初の段階からVC(ベンチャーキャピタル)はお金持ちになっています。そのコインは交換所で突然公式の金額で出現し、宣伝活動によって、人々は購入の勧誘を受けます。一方、インサイダーはいくらでもコインを投げ売りできるのです。

以前は、人々は良くて安いコインを見つける期間があったのに、今はインサイダーによるカルテルによって、彼らはコインを人々に分配し、事前に裕福になります。（Pre-ICO？こりゃ一体なんだ？）　そして、コインは交換所に投入され、彼らは好きなだけ販売するのです。

流行のモデルは次のとおり：

- 設立者とインサイダーはICOの1/10の価格で購入します。
- 彼らは一般向けにICO価格で販売します。（インサイダーが”pre-ICO”で購入した価格の10倍。これは非公開）
- そして彼らは取引所にて、Pre-ICOおよびICOで得たコインを、ICO価格に最低保証価格を加えてばらまき、
　プロジェクトをダメにしていく。間抜けな購買者に大量に売りさばく。
- アドバイザーボードのメンバーは20以上ものコインでこれをやる。何人かはICOだけを行い、次のコインに移り、毎週これを繰り返す。

ほとんどの「150億円をICOで調達した！」というような宣言はウソです。例えてみるなら、5人でお金を出してコインを買い、自分たちで裏からお金を回収しているようなものです。

「投資者」は大幅なディスカウントを要求します。「他のコインはどこでも、市場価格の30%をこちらに分け前として提供してくれるよ」というわけです。彼らは「仮想通貨投資ファンド」として突然出現し、5～20億円もの大量のコインを購入し、5%～20%の値引きをして、その後、彼らはコインを市場にばらまいて利益を得るのです。

以前のモデル：

- あなたはコインを放出します。
- コミュニティーは成長し、コインが受容されていくとともに認知されていきます。
- 早期に関与した人たちは任務を果たし、プロジェクトは可能であれば、何か有益なことを行っていきます。

流行のモデルは、あなたが本来得るはずであったものを騙し取るにすぎません。

私が過去に受けた相談や、会議での経験から私にはこんなことが予想されます。つまり、いくつかの仮想通貨交換所のオーナーは政府によって銃を向けられ、押し倒され、彼らのサーバーが奪われ、没収されると。これは、彼らが詐欺師であるからではなく、彼らがやり方をよくわかっておらず、規制当局や適正な行動をしない人たちを丁寧に扱わないでいるからです。

基本的には、規制当局あるいはその友人が市場に参入し、部外者を排除しようという時までは、どの政府もビットコインや交換所を“規制”したりはしたくないでしょう。アメリカでは特に、CoinBaseのようなオリガルヒ(新興財閥)がいくつか存在し、彼らだけが業務を許されています。彼らはコインのホワイトリスト(警戒する必要のない一覧)を作成し、彼らのコインのみ交換可能とされ、それ以外はリストからはずされます。

正しい人によって運営されていない取引所は、今後閉鎖（若しくはハッキング）されるでしょう。

彼らは「言うとおりにしろ。悪いようにはしないから」と言いながら、銃で押さえつけて“認可済”の業者を配置します。そして、仲間内で例えば、BitcoinをiMessageに組み込んだり、どのコインがアップルストアに適合可能かのホワイトリストを作ったりしようとするでしょう。このようなコントロール方法を皆が知らなければいけません。

アップル社が公式にこのようなウォレットのみを許可し、iMessageに組み込み、その他のアプリを排除するような事態を想像してみてください。

コイン市場はオリガルヒを形成してしまうでしょう。消費者は詐欺を恐れて規制を望みます。その結果、その他のものを受け付けなくなってしまいます。これが現状です。

もう一つ、マウントゴックスのような、大きなハッキングの発生も予想されます。

過去に取引所BTC-eが閉鎖された時のような、特定の取引所の閉鎖命令はないかもしれませんが、MtGoxのようにハッキングして通貨が消滅してしまうかもしれません。

ある電話会議ではこんな指摘がされていました。SEC(米国証券取引委員会)は規制活動や、
罰金、資産没収を基にして設立されていると。これらから彼らの資金が出ているのです。

- 交換所は、取引量でランキングされています。
- 「手数料無料」のある取引所は、無理やり取引を増やします。
　そして手数料をとる交換所はあまりランクキングされません。(正確に算出しないなら話は別ですが。)
- ある取引所は裏の手数料値引きを行い、取引量を水増ししてランキングトップにいこうとします。
　実際には取引は少ないのに。
- もっと悪い取引所は、データを加工して、取引量を膨れ上げさせるようにしてランキングを上げていきます。
- 交換所には大きなインセンティブがあるので、ウソや水増しが生じるのです。
　（詐欺コインは取引量の増大を保証してくれるので、それらは交換所に受け入れられます。）

交換所は、そのコインの取引手数料が１日あたり5,000ドル～4万ドルほどないと、受け入れてくれません。
そのため、ICOのあとに手っ取り早く収益を得ようとするので、ユーザコミュニティーはほったらかしになります。
交換所は双方から0.1%の手数料をとります。(1取引あたり0.2%。なぜなら自分どうしで取引しているから。)
そのため、1日に百万ドルの取引があったとして、2,000ドルの取引手数料が流出していることになります。
いくつかのコインは、「有料ボリューム」または「保証ボリューム」として、毎日6,000万～1,000万ドルの取引があります。
（中クラスのコインにおいて、1日当たり12,000ドルまたは20,000ドル）
交換所のオーナーは取引量のみを気にします。

詐欺(scam)コインや巨大ICOは、「市場メーカー」と呼ばれる人たちにお金を支払い、
大きな取引量であるように見せて、取引所オーナーにとって利益があるかのように感じさせます。

Krakenはおそらくは唯一、このような問題がない取引所です。

大規模に購入する顧客は、Bitfinex等から直接購入しています。

多くの交換所は、売買の登録費用ではなく、交換取引量に応じた収益を得ていますが、
注文数は限られています。そのため、わずかな資金によって、コイン価格は操作されうる状況です。
(この理由から、大きな注文をする際には、一般の交換所ではなく直接購入が望ましいということになります。)
市場構造は壊されたり、都合の良いように操作されたりするのです。

- 製造者・購買者の登録費用はなく、注文量は少ない。
- コインの交換の量が多くなると、手数料も増える。
- ウソの交換量によってランキングが発表されている。(交換所が偽っている場合あり。)
- 取引の隠されたリベート
- 市場メーカーが雇われている。(大きな取引量に見せるために大きなお金を払っている）
- 不正確な交換所ランキング(ウソの取引量)
- 市場では売買が難しい(従って直接購買が必要)
- 多くのコインは市場に出ていない。ハッキングの危険性があるため（Mt.Gox事件）
- 実際にはそれほどの注文がないため、わずかな資金で何千億円もの市場規模であるようにみせることができる。
- 注意深くマーケティングを行った巨大なICO（すべてが詐欺である）は、巨大な取引量を強調する。
　そして技術や実際の組織を重視しない。

具体的な例として、3つのマイクログリッドトークンと企業があります。

- 1つはトークンを発行しており、1億人/年の既存事業者であって、
   暖房/発電の複合設備を30年に渡って運用してきています。そして、
   規制や、顧客価格に関する法律、およびコンプライアンスに関する法律部門をもっています。
   既存の顧客と収益を持っています。
- 他の2つのコインは、数千億ドルもの資金を調達した大規模なICOであり、
　ICOを成功させるための、ソフトウェアも従業員もなく、電力網を構築する経験もなく、
 　市場での事業運営に必要な規制を理解していない。
　　そして、顧客がなく、収益もなく、資金を調達している市場でも営業することはできません。

結果は次のとおり：

- The two scam ICOs, already have multiple exchanges lined up to list them,
  with confirmed listing dates
- The actual company with 100 million/year in revenue with actual power grid
  projects, cannot even get a phone call or get the exchanges to talk to them

That is what the altcoin market looks like right now. The non-scams are
actually being filtered out for economic reasons.

What is happening now is:

- The latest generation of users is buying/selling 15 or 60 coins in their
  portfolio. Someone who owns 60 coins does not have 60 wallets installed on
  their computer. Even the altcoin investment fund people are having trouble
  keeping 15 wallets installed to an offline computer and figuring out how to
  do offline transaction signing for them.
- They do not even have wallets installed for ANY of the coins. Meaning all
  of the coins are just sitting on exchanges waiting to be looted
- I did a survey of Ethereum users and ask them questions like "What Ethereum
  Thin Wallet is Best? Is there something like Electrum for Ethereum? What are
  the best Ethereum wallets?" and most of the "Ethereum Users" have never
  actually used an Ethereum wallet or cannot answer, do not know. This means
  all that money is on exchanges somewhere, its not in their wallets.

For the smaller coins (even coins valued in hundreds of millions or billions
of dollars), many actually have almost zero real transactions, zero people
actually with the wallet. I know this from node IP stats and harvested data I
have seen.

Also, for the majority of the coins the volume is fake. There are coins with
very impressive volume (which the exchanges are making a lot of money on) and
very impressive market caps, but its all fake. Just completely fake. To get
enough volume to get on exchanges, you have to agree to pay a market maker to
create volume.

So some coins are giving 3 or 5 million dollars in coins to day trade on the
exchange, to make the exchange owner money and lure in suckers and if you are
an honest coin or not doing that, they won't list you and will complain "Your
volume is not high enough" and to go give their friends free coins to day
trade and make the exchanges a lot of money.

They know the people that will do this and who wont.

The exchanges are making so much money on the scam and scam ICOs, that they
will only list scam coins (which they make more money on). Their whole
business is about volume. They can have 10 million/day in "volume" and the
real order book depth is ten Bitcoin.

Also, most (the most popular) "Bitcoin News" websites are publishing fake
news, "China Bans Bitcoin for the fifth time", "Russia Bans Bitcoin". Then
when exchanges shut down something actualy happens (an event) there are ZERO
articles about it on those website, because the REAL NEWS is not timed to
their market pump and dumps. The media sites are literally just doing timed
market pump and dumps with completely fake news. They are even recirculating
fake, leaked "regulatory letters" from four years ago as "Just released China
banned Bitcoin" news. And every single day is either a "pump day" or a "dump
day".

So for 90% of these projects, unless you are an insider and the one rigging
the markets and in the cartel, you are not going to benefit from buying any of
these coins. They have already appreciated 100x before you will even see them
on the market. They are just popping into the top 20 out of no where now, with
no one in public able to buy anything before the peak and then immediately
crash afterward.

There are almost 0 (ZERO) news websites tracking:

- Actual technology
- Real world usage of blockchain
- Real world development (projects with developers)
- Smaller projects that are trying to do something more than run a pump and
  dump for the suckers

The whole market has been taken over completely. The libertarian aspiration of
Bitcoin have been killed by simple greed and lust after easy money.

---

There are people who have real data (primary data) and they know which coins
have actual users and real user communities. I track this data constantly and
the data is pretty bad. The existing coin market is a train wreck.

Since no one ever withdraws coins from the exchange, the data suggests that
many coins are selling more coins than actually exist. The trading volume and
activity is completely uncorrelated to any real verifiable primary metrics.

People have told me that some exchanges have a history of sudden delisting of
some coins without allowing the users to withdrawal. Which would explain what
is happening. My attitude now is "If the coins are not in my wallet and on my
computer, they do not exist".

Once the regulators lock out the smaller coins from the markets completely
with white-listing, the only thing that is getting listed will be two or three
multi-billion dollar mega-scams a month. I have no idea what this will look
like. Only the biggest, most toxic, best dressed scams who paid off the most
people will be able to get listed.

The big changes to the market will be:

- Multi-coin support (cross platform coin/wallet support standards, people
  pulling coins off the exchanges)
- DEX (distributed exchanges), the real and long term money has already moved
  off the exchanges because of the hacking risk.
- Real uses of blockchain instead of speculation (actual companies, using
  tokens for real business functions)

However, the sophisticated people are doing very very well. The people who
know what is going on.

Many of the large investors are moving off of the exchanges to OTC.

They are boycotting all the coins with one or two "pre-ICOs" where the
insiders get to buy at 1/100th the price of the public. They are ignoring the
massive ICOs and looking at fundamentals and primary metrics.

It is sort of obvious, to anyone that is not an idiot, that if a coin raised 1
billion dollars in an ICO, that the price is not going to go up 100x (that 100
billion dollars in shucks are going to come along and dump one hundred billion
dollars into the coin so that all the people in the ICO can exit 100x when the
bought it at before the ICO). Especially if the coin is a "Smart Contract
Platform" with no users or applications and not Enron selling a billion
barrels a year of oil for E-coin.

IF:

- A coin raises 1 billion dollars in an ICO
- The coin WILL NOT increase to 100x the ICO price
- To go up 100x, the existing coin holders have to be bough out for 100 billion
- That money has to come from somewhere (where as the vast majority of coins
  only lose money and all of their inflows come from people buying the coin
  for speculation)

So it is obvious that all the best relative returns are in the smaller
projects and not the mega-ICOs.

So all the money is being made by avoiding the mega-ICOs and focusing on
fundamentals.

Where as idiots see "They raised twelve billion dollars in FIVE MINUTES. I
NEED TO MORTGAGE MY HOUSE AND BUY THIS IN CASE IT GOES UP 3x AFTER THE ICO".
Then all the people who bought the coin at 1% of the ICO in the "pre-ICO"
(that you were not invited to), will dump everything at the ICO price as soon
as it hits the market.

This trend of everyone creating twelve bitcoin forks, so they can get free
coins and dump them is also ridiculous.

## New Wallet

Wallet Version 20 is released.

All nodes have been upgraded.

Completely new wallet from scratch. The new wallet is dozens of times faster.

Blockchain syncing is hundreds of times faster and is almost instant now. The
old wallet took 1 second per block to sync. The new wallet syncs a few
thousand blocks in a few seconds.

In future upgrade, all blocks will be treated as immutable data objects in
CXO, so that the blockchain can be downloaded in parallel across all blocks
and all connected peers, using all available bandwidth in parallel with no
constraints on the block ordering.

This will be even faster than Bitcoin's "header first downloads" or the rust
ethereum approach.

## CoinHours

The new wallet (version 20) now shows the "CoinHours", which users earn for
holding Skycoin.

We are working on an exchange for converting and establishing an exchange rate
between CoinHours and Skycoin. Coin Hours are similar to the "Gas" in Ethereum
or coin aging in Bitcoin, but are exchange-tradeable and are a separate
parallel currency in Skycoin.

Coin Hours are used for transaction fees in Skycoin and will also be used for
network resources on Skywire.

Coin Hours may eventually also be used for allocation of distributed
computation resources, storage or bandwidth on SkyLedger and any Skycoin side
changes with embedded CX scripting language.

The future wallet versions will add an API and UI to specify or
split the CoinHour balances in transactions.

If Skycoins are held on an exchange, the coin hours earned will go to the
exchange.

Skycoin CoinHours are also a very important part of the Skycoin CoinJoin
infrastructure for increasing transaction privacy. CoinHours will be posted as
collateral for mixing to prevent participants from backing out of or slowing
down CoinJoin transactions. Skycoin CoinJoin transactions improve the
mathematical guarantee of Skycoin transaction privacy by spending outputs from
multiple wallets in the same transaction. This prevents the most common
deanonymizing attacks in Bitcoin. When fully implemented, this will give
Skycoin a ZeroCoin-level mathematical guarantee of transaction privacy, with
orders of magnitude less complexity and computation overhead than the ZeroCoin
implementation, by eliminating the requirement of the highly complicated
zero-knowledge proof system.

## Skycoin (DEX) Distributed Exchange Support

We are currently designing a hardcoded, 2-factor multi-signature transaction
type with relative time locks for Skycoin. This new transaction type
will enable DEX and atomic swap support across Skycoin and all Skyledger
coins.

We are also evaluating proposals for introducing a third transaction type for
atomic swaps between blockchains. However, we believe that atomic swaps
between blockchains are not mature yet and that the 2-signature multi-sig with
relative time lock is the simpliest/easiest way to implement this.

## Skycoin Projects Position on the Smart Contracts Fad

Skycoin does not have a "Smart Contracting Language". Our blockchain language
is a full programming language suitable for both desktop, server, networked
applications but with all the features required for blockchain embedding.

We believe that "smart contracts" are a fad. In the future when anyone can
publish their own blockchain as easily as creating a word-press blog, it does
not make sense to cram the real world uses of blockchain scripting onto a
third party platform. While we have a programming language, CX, that is
designed for actual applications and real world usage, not "smart contracts"
(as to date we have been unable to find a single real use or application for
smart contracts).

## CX

CX is an extremely strict, statically typed, affordance based (based upon Alan
Kay's COLA architecture),  mathematically deterministic language. CX is
designed to support the whole range of applications from being embedded on
blockchain, to programming for GPU, FPGAs and achieving power saving and
performance on next generation CPU architectures (RISC-V) which have explicit
cache load/store instructions.

We are currently prototyping OpenGL support for CX.

CX also has a new website and programming sandbox.

https://cx.skycoin.net

I want to see people writing video games or a poker app or something on CX
soon. I enjoyed "GameCoin" and we need more experiments in embedding video
games on blockchain like GameCoin.

**The Skycoin bounty program will expand to including incentive for video games
and applications written in CX on the Skycoin platform.**

The Skycoin bounty program will expand to including incentive for video games and applications written in CX on the Skycoin platform.


I like huntercoin because it is a blockchain based MMO and we wanted to build
a language and platform platform to make gaming and communication applications
easy. We did not feel this is even possible with a "smart contracts" language.
Expecially because the most popular  application by user are messaging/
communication, file sharing and gaming applications.

We also wanted to allow developers to prototype business logic and test
applications in CXO (which is like blockchain-lite) before publishing onto a
real blockchain, where making updates/fixing bugs becomes much more
complicated.

Skycoin is also the first platform that will be able to distribute blockchain
state updates globally in less than 300 ms (instead of 15 minutes or 30
seconds) and this is the minimum threshold for "real time" interaction
required for several applications like decentralized poker.

Obviously the issues of waiting +30 seconds between interactions and an
inconsistent block rate impair the user experience. Bitcoin's rate of one
block every 15 minutes makes poker unplayable and Ethereum's rate is still
insufferable for real time applications.

I do not see any real world usage, economics or technological capacities
justifying the billion dollar valuations of these "Smart Contract Platforms".
I think "smart contracts" are already past peak and are in a bubble.

So for us to enable these real applications, required years of technology work
to have a platform that could meet these requirements. Regardless of whatever
the "smart contract platforms" say in their marketing, these applications are
only becoming possible in the next generation. Simply none of the current
generation of platforms has a technical solution to overcome the requirements
for mainstream adaption.

So I am really excited about doing a bounty to have something like HunterCoin
(MMO on blockchain) or some kind of real money rogue-like (e.g. NetHack) built
on top of CX. "Real Money Dwarf Fortress on Blockchain". It will be exciting
to see what people do with this.

[CX source code](https://github.com/skycoin/cx)

## Skycoin Roadmap Finished

The roadmap is on the website now

https://www.skycoin.net/roadmap/

## First Distributed Social Media Platform on Skycoin Platform Launches

The beta test of the first distributed social media application on the Skycoin
platform is ready.

https://www.skycoin.net/downloads/ (scroll down to the BBS section)

BBS is a peer-to-peer replicated social media application, built upon immutable
data structures (CXO) on top of the Skycoin platform.

All database in the Skycoin distributed BBS application is replicated
peer-to-peer using the Skycoin CXO library (previously called Aether). Post
submissions are submitted over a prototype of Sky-messenger, which is Skycoin's
TOX-like standard for machine-to-machine communication between public keys
[(github.com/skycoin/net)](https://github.com/skycoin/net).

Sky-messenger is specifically designed for peer-to-peer machine-to-machine
communication, but also has a human-usable, Wechat-like interface.

## Skycoin OTC Market

Now that the prototype for Sky-messenger is working, we can include an
integrated Skycoin OTC market in the next wallet release.

The new wallet will also eventually include a "Send to Bitcoin address"
function, which should increase Skycoin liquidity.

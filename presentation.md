title: すえなみチャンス忘年会
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
.bottom-bar[
  {{title}}
]

---

class: impact

# {{title}}
## @yoshiyoshifujii

---

# 自己紹介

.col-6[

- Yoshitaka Fujii [@yoshiyoshifujii](https://twitter.com/yoshiyoshifujii)
- Chatwork株式会社 (4ヶ月)
- Scala関西 Summit スタッフ
- Scala、Python、Java、JavaScript
  - 最近、PHP、Go
- 4年ほど前からTryしてます
  - DDD、Miciroservices、Serverless
  - Agile、Scrum、DevOps

]

.col-6[

.right[<img src="https://pbs.twimg.com/profile_images/907421547551277056/_vQ3f2Fg_400x400.jpg">]

]

---

# 今やっていること

- OAuth2認可サーバの実装・運用
- 既存のChatworkのキャッチアップ
  - IFTTT連携
  - k8s
  - CI/CDの仕組み
  - PHPで作られているところ

---

# 関心のある技術領域

- gRPC
  - [Akka gRPCを試してみた \- Qiita](https://qiita.com/yoshiyoshifujii/items/04944ade01af4fe06bca)
  - [クックパッドの動画事業での AWS AppSync 活用事例 / Practical use of AWS AppSync by Cookpad \- Speaker Deck](https://speakerdeck.com/wata/practical-use-of-aws-appsync-by-cookpad)
- k8s
  - CI/CD
      - [Rancher2\.1のPipelinesを試す \- Qiita](https://qiita.com/yoshiyoshifujii/items/4e360a7a4f2ac76bbc28)
- DDD
  - [DDDをやって良かったと思ったこと \- Qiita](https://qiita.com/yoshiyoshifujii/items/d874afca232928cab10a)

---

# 議論したいこと

gRPCが主流になってくると、クラサバ間や、サバサバ間のRESTfulなやりとりを、一つの仕様から落としこめて、かつ各種言語のボイラープレートを自動生成してくれて、かなり生産性が上がりそうで、注目しています。

DDD+CQRS+EventSourcingの文脈で言うと、GraphQLはQueryに使えて、gRPCは、Command+EventSourcingのあたりで使えそうだなーと。

で、そのあたり実現していくと、AWS AppSyncとか、k8sとか、良い感じにCommandをGraphQLで読み取れるReadModelにタイムリーに反映していくみたいなん要りそうで…


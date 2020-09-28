---
title: 必須レビューでのプルリクエストの承認
intro: リポジトリでレビューが必須になっているなら、プルリクエストがマージできるようになるためには、リポジトリに _書き込み_ あるいは _管理_ 権限を持つ人からの承認レビューが指定された数だけ必要です。
redirect_from:
  - /articles/approving-a-pull-request-with-required-reviews
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

必須レビューに関する詳しい情報については[プルリクエストのための必須レビューについて](/articles/about-required-reviews-for-pull-requests)を参照してください。

プルリクエストにコメントしたり、変更を承認したり、承認に先立って改善をリクエストしたりできます。 詳しい情報については[プルリクエストのための必須レビューについて](/articles/about-required-reviews-for-pull-requests)及び[プルリクエストで提案された変更をレビューする](/articles/reviewing-proposed-changes-in-a-pull-request)を参照してください。

{{ site.data.reusables.search.requested_reviews_search }}

{% tip %}

**参考**: 承認したプルリクエストが大きく変更された場合、レビューを取り下げることができます。 そのプルリクエストは、マージする前に新しいレビューが必要になります。 詳しい情報については[プルリクエストレビューの却下](/articles/dismissing-a-pull-request-review)を参照してください。

{% endtip %}

{{ site.data.reusables.repositories.sidebar-pr }}
{{ site.data.reusables.repositories.choose-pr-review }}
{{ site.data.reusables.repositories.changed-files }}
4. プルリクエスト内の変更をレビューし、[特定の行にコメント](/articles/reviewing-proposed-changes-in-a-pull-request/#starting-a-review)することもできます。
{{ site.data.reusables.repositories.review-changes }}
{{ site.data.reusables.repositories.review-summary-comment }}
7. [**Approve**] を選択して、プルリクエスト中で提案された変更のマージを承認します。
{{ site.data.reusables.repositories.submit-review }}

{{ site.data.reusables.repositories.request-changes-tips }}

### 参考リンク

- [プルリクエストのための必須レビューについて](/articles/about-required-reviews-for-pull-requests)
- [プルリクエストで提案された変更のレビュー](/articles/reviewing-proposed-changes-in-a-pull-request)
- [プルリクエストへのコメント](/articles/commenting-on-a-pull-request)
# Contribution Guide

This guide describes how to contribute to the [rt-net](https://github.com/rt-net) organization repository.

## Issues

Thank you for helping us improve the quality of the repository.

We have prepared a template to make it easier for you to create issues.

## Pull Requests

Thank you for creating Pull Requests.

The following rules apply to your Pull Request (PR)

- The content of the PR is subject to the license of each repository (as described in the `LICENSE` or `README.md`).
- PRs are reviewed by `rt-net` members before being merged
  - Not all PRs will be merged and the review process may take some time.
- For requests to repositories where CI and tests are set up, please try to pass the tests as much as possible.
  - If you submit a PR without testing for a specific reason (e.g., if there is a mistake in the testing), please describe it in the PR.
- When merging, all commits in the PR will be `squashed` into one commit.
- Keep the changes requested in a single PR as simple as possible
- To make it easier to trace back the history after a squash merge, please split a PR if it contains changes with different content.
  - For example, if you are adding multiple features, or adding features and refactoring at the same time, each should be a separate PR.

---

# Contribution Guide

[rt-net](https://github.com/rt-net) organizationリポジトリへのコントリビュート方法について記載しています。

## Issues

リポジトリの品質向上にご協力頂きありがとうございます。

Issueの作成を簡単にするテンプレートを用意しているので活用してください。

## Pull Requests

Pull Requestの作成ありがとうございます。
提出したPull Request（PR）には次のルールが適用されます。

- PRの内容には各リポジトリのライセンス（`LICENSE`または`README.md`に記載されています）が適用されます
- PRは`rt-net`のメンバーによるレビューを経てからマージされます
  - すべてのPRがマージされるわけではなく、希望に添えない場合もありますのでご容赦ください
- リポジトリにテストが設定されている場合はできるだけテストを通してください
  - 何かしらの理由（テストに間違いがある場合など）でテストを通さずPRを出す場合はその旨をPRに記載してください
- マージする際にはPR内の全コミットが1つのコミットに`squash`されます
- 1つのPRでリクエストする変更はできるだけシンプルにしてください
- squashマージしても履歴を辿りやすくするため、異なる内容の変更を含む場合はPRを分割してください
  - 例えば、複数の機能追加したり、機能追加とリファクタリングを同時にする場合はそれぞれ別々のPRとしてください

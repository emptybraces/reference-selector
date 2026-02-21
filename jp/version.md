# バージョン
---
## 2.1.0
- [Selection History] 参照を設定したオブジェクトを自動的に選択履歴へ追加する機能を追加。直接選択をしていない参照への再アクセスが可能になりました。
- [Preferences] フォルダを開いた際に、直前の選択オブジェクトを自動で復元するオプションを追加。フォルダ表示によってインスペクタ表示が切り替わってしまうストレスを軽減します。
- [Preferences] EditorPrefsに保存していたパラメータをScritpableObject管理に変更。
- [Preferences] Preferencesに表示していなかったオプションを表示するように修正。

## 2.0.0
- リファクタリングを行い、パフォーマンスが僅かに向上。
- 各ドキュメント、ロゴイメージを刷新。
- [Context Menu] GetComponent操作のメニューを追加。
- [Context Menu] Sibling操作のメニューを追加。
- [Context Menu] 複数編集時にHierarhy Treeメニューを実行した時、選択オブジェクトそれぞれのヒエラルキーツリーから参照を検索するように修正。
- [Inspector Menu] Prev/Next操作のデフォルトショートカットキーをShift+ホイールダウン/アップに修正。
- [Inspector Menu] Open Historyの外観を修正。
- [Inspector Menu] Open Historyで項目選択時、コントロールキーを押しながらクリックするとPropertiesエディタウィンドウを開くオプションを追加。
- [Inspector Menu] 右端のコンフィグボタンのメニューに、"Edit Preferences", "Editor Shortcuts", "Version"を追加
- [Preferences] Reference Selector専用の項目を新規作成
- [Preferences] 選択履歴最大数を追加。

## 1.0.2
- [Bugfix] 特定のジェネリッククラスのフィールドのコンテキストメニュー表示時に例外が発生する。

## 1.0.1
- [Bugfix] 特定の状況でUnityEngine以降の名前空間を持つコンポーネントが取得できない。

## 1.0.0 
- 初回リリース
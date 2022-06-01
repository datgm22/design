# GitHubのプロジェクトの登録を失敗したときの対処

- Explorerで、間違えたUnityのプロジェクトフォルダーを開く
- UnityのProjectフォルダーの中に、プロジェクトフォルダーと同じ名前のフォルダーがあるはず。それを開く
- フォルダー内のフォルダーとファイルを全て選択して**切り取る**
- 1つフォルダーを戻って、Unityのプロジェクトフォルダーの直下へ移動
- 貼り付ける

以上で、gitで管理に必要なフォルダーがUnityフォルダーに移動する。Gitのリポジトリーである`.git`フォルダーが正しい場所にあることが重要。

以下の作業をしてGitHub Desktopでフォルダーの場所を変更する。

- GitHub Desktopに切り替える
- Fileメニューを開いて、Add local repository...を選択
- Choose...ボタンを押して、ドキュメント>自分の名前のフォルダーの中の、Unityのプロジェクトフォルダーを選択して、Add repositoryボタンをクリック
- Changesに、AssetsフォルダーなどのUnityのファイルが追加されるので、Summaryに「フォルダー追加」などを入力して、Commit to main > Push originをクリック

以上。

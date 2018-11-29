# test-infovis
git 使い方

＄git branch
現在のbranchの場所がわかる

$git checkout -b test
$git checkout  test
$git checkout master
checkoutでbranchの移動、移動先を指定する。
その際、新しいbranchを作るなら-bオプジョンをつける。

$git push origin test
ローカルのtest branchでの作業をリモートのtest branchにpush

$git checkout master
$git merge test
ローカルのtest branchをローカルのmasterにmerge

$git push origin master



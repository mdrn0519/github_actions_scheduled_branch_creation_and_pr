# Github Actions Scheduled Branch Creation and PR
毎週水曜日と金曜日の朝９時に、developブランチからリリースブランチ（`release/yyyyMMdd`）を作成し、mainに向けたPRを作成する。
mainブランチとdevelopブランチを比較し、差分がなければPRは作成されません。

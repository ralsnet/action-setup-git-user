# ralsnet/action-setup-git-user@v1

このアクションは、GitHub Actions で使用するための Git ユーザーを設定します。
他のオーガニゼーションのプライベートリポジトリにアクセスできるユーザーを設定すれば、そのリポジトリを参照したり、GitHub Packages にアクセスしたりできるようになります。

## Usage

```yaml
- uses: ralsnet/action-setup-git-user@v1
  with:
    # git configに設定するユーザー名
    user-name: "Ralsnet"
    # git configに設定するユーザーのメールアドレス
    user-email: "ralsnet@example.com"
    # 設定するユーザーのSSHキー
    private-key: ${{ secrets.PRIVATE_KEY }}
```

## License

The scripts and documentation in this project are released under the MIT License. See the [LICENSE](LICENSE) file for details.

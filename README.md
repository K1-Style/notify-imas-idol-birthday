# 今日誕生日のアイドルをSlackで知らせる

## 参考

* [CircleCI Orb Registry \- yutagoto/todays\-imas\-idol](https://circleci.com/orbs/registry/orb/yutagoto/todays-imas-idol)
* [今日誕生日のアイドルを出力するCircleCI orbをつくったお話](https://medium.com/@gggooottto/%E4%BB%8A%E6%97%A5%E8%AA%95%E7%94%9F%E6%97%A5%E3%81%AE%E3%82%A2%E3%82%A4%E3%83%89%E3%83%AB%E3%82%92%E5%87%BA%E5%8A%9B%E3%81%99%E3%82%8Bcircleci-orb%E3%82%92%E3%81%A4%E3%81%8F%E3%81%A3%E3%81%9F%E3%81%8A%E8%A9%B1-fff413118a40)

## CircleCIの環境変数で設定必要なもの

* `SLACK_WEB_HOOK`
    * SlackのIncoming Webhookで用意したWebhook URL
* `SLACK_ICON`
    * Slackのアイコンエイリアス。`:slack:`, `:calendar:` など

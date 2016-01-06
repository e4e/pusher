# Pusherを理解する

Pusherは、Webアプリ/mobileアプリ、またはその他のネット接続デバイスに、WebSocketを使ったリアルタイムの双方向通信を、すぐに、簡単に、そして安全に導入するためのシンプルなAPIです。

私たちは、アプリで使える充実した[ライブラリ](https://pusher.com/docs/libraries)のセットを用意しており、その中には
webアプリ/HTML5アプリのための [JavaScript client library](https://pusher.com/docs/client_api_guide/#lang=js) も含まれます。

私たちの**イベントベースの抽象化**は、クライアント・サーバー側からトリガーされたイベントをUIに紐付けるのを簡単にします。

私たちは、あなたのアプリが将来も使い続けられるように、またデータ使用量を最小限に抑えながら**双方向コミュニケーション**を追加することが簡単になるように、WebSocketsを使っています(Javascriptクライアントライブラリの中では、 [FlashとHTTPへのフォールバック](https://pusher.com/docs/fallbacks)とともに)。

WebSocketsAPIと同様、私たちはメッセージ発行のための[REST API](https://pusher.com/docs/rest_api)を用意しています。これはWebサーバの技術と非常に相性が良く、さらに私たちは開発をサポートするために[主要言語でのREST APIライブラリ](https://pusher.com/docs/libraries#rest_libraries)も用意しています。

<center>![Pusher with bi-directional WebSockets and REST API](https://pusher.com/assets/docs/hero_howitworks-d5840af909cfca0b448c6b24fdfdf9af6a95263d79ada6a789607b8f6bc7a6e1.png)</center>

私たちは、ユーザーの受け取るメッセージをフィルターしてコントロールするための、channelsベースのシンプルな**Publish/Subscribe**モデルを提供します。

私たちは、[private channels](https://pusher.com/docs/private_channels)のための認証メカニズムのような機能や、誰がオンラインなのかを追跡し続けるための[presence](https://pusher.com/docs/presence)機能を提供しています。

私たちは[アプリデバッグ](https://pusher.com/docs/debugging)のためのツールも提供していますし、もしあなたが何か困ったときは、いつでもチャットで私たちに[コンタクト](https://pusher.com/about/contact)することができます。

### はじめよう

To get started check out the [JavaScript quick start guide](https://pusher.com/docs/javascript_quick_start), the [Client API Overview](https://pusher.com/docs/client_api_guide) or the [Server API Overview](https://pusher.com/docs/server_api_guide). Alternatively have a look at some of the [examples](https://pusher.com/examples) of Pusher in use, or checkout some of the resources we have collected.

Have you tried [using the search](https://pusher.com/docs/search) to find what you’re after? If you still have a question then [get in touch with us](https://pusher.com/support) and let us help you out.

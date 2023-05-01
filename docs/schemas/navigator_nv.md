# `nv` ナビゲーター
## `nv/camera/`
カメラを開きます。
### Example
- `line://nv/camera/`
カメラを開きます。
## `nv/cameraRoll/{mode: "single" | "multi"}`
カメラロールを開きます。
### mode: single
一枚のみ開きます。
### mode: multi
複数開くことができます。
### Example
- `line://nv/cameraRoll/single`
一枚のみ開く
- `line://nv/cameraRoll/multi`
複数枚開ける
## `nv/location`
位置情報選択画面を開きます。現在地を共有することができます。
### Example
- `line://nv/location`
## `nv/recommendOA/{LINE_ID}`
"送信先を選択"画面が表示されます。公式アカウントを共有できます。
### `LINE_ID`
公式アカウントのLINE IDを指定します。必須です。
### Example
- `line://nv/recommendOA/ms_rinna`
りんなを共有できます
## `nv/profile`
自分のプロフィール画面を開きます。
### Example
- `line://nv/profile`
自分のプロフィール画面を開きます。
## `nv/profileSetId`
自分のLINE IDの設定/確認画面を開きます。
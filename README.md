# README

プロジェクト作成後
Gemに以下のものが入っているかを確認し、
```
gem 'webpacker', '~> 4.0'
```
確認され次第、コマンドで以下を実行
```
rails webpacker:install
rails webpacker:install:vue
```
Controller,view作成後、viewファイルに
```html:index.html.erb
<%= javascript_pack_tag 'hello_vue' %>
```
と記述することで`hello_vue.js`を取り込む

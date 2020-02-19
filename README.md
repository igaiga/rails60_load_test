autoloadとeager_loadのテストサンプルアプリ

Rails 6.0.2.1
Ruby 2.6.5

lib以下にFooクラス定義

テストコマンド

- $ DISABLE_SPRING=true RAILS_ENV=production rails runner "Foo.new.foo"

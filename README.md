# devise_gem_practice

- devise gem で新規登録した際に、メールで確認をする機能がうまく働くかどうかの確認。

- development.rbに

`config.action_mailer.smtp_settings = {
  :address => "smtp.gmail.com",
  :port => 587,
  :user_name => "?????@example.com",
  :password => "パスワード",
  :authentication => :plain,
  :enable_starttls_auto => true
}`

を追加した後に、サーバーを再起動させないとデフォルトのメールアドレスの変更が行われない。


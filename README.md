## README


### Reproduction app for https://github.com/rails/rails/issues/23300 and https://github.com/rails/web-console/issues/184

git clone 
bundle
rails c
```
/Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/web-console-3.1.0/lib/web_console/extensions.rb:10:in `console': WebConsole::DoubleRenderError (WebConsole::DoubleRenderError)
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/railtie.rb:248:in `public_send'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/railtie.rb:248:in `each_registered_block'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/railtie.rb:224:in `run_console_blocks'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/application.rb:461:in `block in run_console_blocks'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/engine/railties.rb:13:in `each'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/engine/railties.rb:13:in `each'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/application.rb:461:in `run_console_blocks'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/engine.rb:442:in `load_console'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/commands/console.rb:34:in `initialize'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/commands/console_helper.rb:9:in `new'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/commands/console_helper.rb:9:in `start'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/commands/commands_tasks.rb:78:in `console'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/commands/commands_tasks.rb:49:in `run_command!'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/command.rb:20:in `run'
	from /Users/prathamesh/.rbenv/versions/2.3.0/lib/ruby/gems/2.3.0/gems/railties-5.0.0.beta1.1/lib/rails/commands.rb:19:in `<top (required)>'
	from bin/rails:4:in `require'
	from bin/rails:4:in `<main>'


```

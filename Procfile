web: RUBYOPT="--yjit --yjit-exec-mem-size=${RUBY_YJIT_EXEC_MEM_SIZE:-64}" bundle exec puma -C config/puma.rb
worker: bundle exec sidekiq
release: bundle exec rails db:migrate

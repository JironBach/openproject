web: ./packaging/scripts/web
web: bin/bundle exec bin/rails server -p $PORT -e development
worker: bin/bundle exec rake jobs:work
backup: ./packaging/scripts/backup
check: ./packaging/scripts/check

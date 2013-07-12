source 'https://rubygems.org'

gem 'rake'

gem 'activesupport', '>= 4.0'
gem 'activerecord',  '>= 4.0'
gem 'delayed_job',   :git => 'https://github.com/collectiveidea/delayed_job.git'


group :test do
  platforms :jruby do
    gem 'activerecord-jdbcmysql-adapter'
    gem 'jdbc-mysql'

    gem 'activerecord-jdbcpostgresql-adapter'
    gem 'jdbc-postgres'

    gem 'activerecord-jdbcsqlite3-adapter'
    gem 'jdbc-sqlite3'
  end

  platforms :ruby, :mswin, :mingw do
    gem 'mysql', '~> 2.8.1'
    gem 'pg'
    gem 'sqlite3'
  end

  gem 'coveralls', :require => false
  gem 'rspec', '>= 2.11'
  gem 'simplecov', :require => false
end

source 'https://rubygems.org'
source 'https://rails-assets.org'

ruby '2.7.2'
# dotenv has to be placed first due to some quirks
gem 'dotenv-rails', require: 'dotenv/rails-now', groups: [:development, :test]

gem 'rails', '~> 6.0.4.7'

gem 'pg'
# front-end
gem 'sass-rails', '>= 5.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails'

gem 'rack-ssl-enforcer'
gem 'font-awesome-sass'
gem 'geocoder'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'slim'
gem 'simple_form'
gem 'rails-assets-reflux'
gem 'react-rails'
gem 'rails-assets-react-bootstrap'
gem 'rails-assets-underscore'
gem 'rails-assets-classnames'
gem 'js-model-rails'

gem 'savon', '~> 2.10.0'
gem 'wash_out',:path=>"vendor/gems/wash_out_0.9.2"
gem 'terminal-table'
gem 'newrelic_rpm'

gem 'spree',:git =>"https://github.com/spree/spree.git",:branch => "4-3-stable"

gem 'spree_backend','4.3.0'
gem 'spree_frontend','4.3.0'
gem 'spree_api','4.3.0'
gem 'spree_auth_devise', '~> 4.3'
gem 'spree_gateway', '~> 3.9'
gem 'spree_emails', '>= 4.3'
gem 'spree_i18n', '~> 5.0'
gem 'spree_globalize', github: 'spree-contrib/spree_globalize'
gem 'deface'
gem "devise","~> 4.7"

gem 'omniauth-invisalign', '2.3.1', tag: 'v2.3.1', git: 'https://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:x-oauth-basic@github.com/Align-Deployment/omniauth-invisalign.git'
gem 'alignnume-ids-layout',branch: 'dev/storenume', git: 'https://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:x-oauth-basic@github.com/Align-Deployment/align-ids-layout.git'
gem 'align-ids-layout','1.0.99', branch: 'dev/1.0.x_navigation_fix', git: 'https://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:x-oauth-basic@github.com/Align-Deployment/align-ids-layout.git'

#kafka
gem 'ruby-kafka'
gem 'avro_turf'

gem 'delayed_job'
gem 'delayed_job_active_record'
gem 'restforce', '~> 3.1.0'

# gem 'aws-sdk', '< 2.0'
gem "aws-sdk", ">= 2.0"
gem 'httparty'
gem 'nokogiri'
gem 'rack-cors', :require => 'rack/cors'

#gem 'spree_mail_settings', github: 'spree-contrib/spree_mail_settings', branch: '3-0-stable'


group :production, :staging do
  gem 'rack-timeout'
end

group :production do
  gem 'rails_12factor'
  gem 'unicorn'
  # gem 'airbrake'
  # gem 'airbrake',"4.3.0"
end
gem 'airbrake'


gem 'omniauth-saml'

gem 'spree_analytics_trackers'
gem 'bootstrap-sass', '~> 3.3.3'
#
gem "webpacker"
gem "compass"


gem 'puma', '>= 5.3.1'
gem 'activerecord-nulldb-adapter'
gem 'factory_bot'
gem 'factory_girl', '~> 4.9'
gem 'polyglot', '~> 0.3.5'
gem 'factory_girl_rails', '~> 4.9' , :require => false
gem 'spree_bulk_discounts',:path=>"vendor/gems/spree_bulk_discounts"

gem "image_processing" ,"~> 1.12.2"
gem 'actioncable',">=6.0.4.7", :require => false

gem 'sqreen'


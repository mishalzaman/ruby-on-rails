# Ruby on Rails learning process

Learning Ruby On Rails, will be updating this over time.

Create new Rails app:

	$ rails new {app_name}
	
Starting the web server (within the app directory)

	$ bin/rails server
	
## Generate

**Controller**

	$ bin/rail generate controller {action 1} {action 2...n}
	
**model**

	$ bin/rail generate model {model_name} {table_name}:{data_type}
	$ bin/rails db:migrate VERSION={migration_version_number}
	
> bin/rail generate user id:integer name:text

To destroy a model:

	$ bundle exec rake db:rollback
	$ rails destroy model {model_name}
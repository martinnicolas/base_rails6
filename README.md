# Proyecto base Ruby On Rails 6

Este es un Proyecto base para la creación de proyectos usando Ruby On Rails.

Requisitos:

	* Ruby 2.5.0
	* Rails 6.0.3.3

Utilizando RVM (Ruby Version Manager) ejecutar:

	1- rvm install 2.5.0

	2- gem install rails -v 6.0.3.3


Una vez instalados todos todos los requerimientos ejecutar:

	1- git clone https://github.com/martinnicolas/base_rails6.git

	2- cd base_rails6

	3- rails g rename:app_to NEW_NAME (Por ejemplo, sistema_nuevo)

	4- bundle install

	5- rake db:create

	6- rake db:migrate

	7- rake db:seed

	8- rails s
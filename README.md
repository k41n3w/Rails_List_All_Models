# Rails_List_All_Models
Comandos básicos para listar todas tabelas de um banco conectado a um projeto rails.

Rails.application.eager_load! 

ActiveRecord::Base.descendants

# Library

Project Demo - https://libraryproject-pern-stack.onrender.com/

FrontEnd - React
BackEnd - Node, Express
DB - PostGres
Cloud Host - Render

This project is just an experiment of how to set up a PERN Stack using sequelize & Supabase as a storage solution

# Sequelize Commands

1. Generate Model: "sequelize model:generate --name Book --attributes book_id:integer,name:string,author:string,year_published:smallint"

2. Generate "books": sequelize seed:generate --name books

3. Create DB model in supabase: "sequelize db:migrate"

4. Migrate Data to DB using Seeder: "sequelize db:seed:all"

# Notes

1. You might run into issues with pg. Try "npm install -g pg --save"

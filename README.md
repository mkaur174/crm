# Rails CRM Application

A Ruby on Rails Customer Relationship Management (CRM) application built with Active Admin and styled using Bulma CSS.

Repository Link: https://github.com/mkaur174/crm

---


---

## Setup & Installation Steps

### 1. Clone the Repository

git clone [https://github.com/mkaur174/crm.git](https://github.com/mkaur174/crm.git)
cd crm

## install dependencies:
bundle install

## set up database:
rails db:create
rails db:migrate
rails db:seed
run it: rails s

http://127.0.0.1:3000/

## CREATE CONTROLLER :
rails g controller Customers index alphabetized missing_email

## ADMIN SETUP :
rails g active_admin:install
rails g active_admin:resource Customer

## GIT INITIALIZE AND COMMIT:
git init
git add .
git commit -m "Complete customer CRM card layout, navigation tabs, and Bulma styling"

## CONNECT TO REMOTE REPOSITORY AND PUSH:
git remote add origin [https://github.com/mkaur174/crm.git](https://github.com/mkaur174/crm.git)
git branch -M main
git push -u origin main

# NEW UPDATE
git status
git add .
git commit -m "update message"
git push
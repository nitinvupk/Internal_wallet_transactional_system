# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

 # Ruby version
   2.7.2
 # Rails version
   6.1.7
 # Database initialization
   * rails db:create
   * rails db:migrate
   * rails db:seed
# Start Rails server
  * Rails server
# About project
  * This is an API application (Internal wallet transactional system)
  * The basic idea of ths API application to handle many transactions b/w user and stock
  * Login, Add money, withdraw money, Buy stock, Sale stock
# Login endpoint
  * http://localhost:3000/login
  * pass params{ email: user1@gmail.com password: password123 }
  * respose will be auth token that help you to perform transactions
# Add Money API
  * http://localhost:3000/wallets/deposit
  * params{ auth_token: from above step, amount: 10000}
# Withdraw Money
  * http://localhost:3000/wallets/withdraw
  *  params{ auth_token: from above step, amount: 1000}
# Check Balence
  * http://localhost:3000/wallets/check_balance
  * params{ auth_token: from above step}
# Find Available Stock
  * http://localhost:3000/stocks/available_stocks
  * params{ auth_token: from above step}
# Purchase Stock
  * http://localhost:3000/stocks/purchase_stock
  * params{ auth_token: from above step, stock_identifier: 'NAUKRIEQN', quantity: 1}
# Sale Stock
  * http://localhost:3000/stocks/purchase_stock
  * params{ auth_token: from above step, stock_identifier: 'NAUKRIEQN', quantity: 1}
  

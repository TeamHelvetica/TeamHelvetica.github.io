# TeamHelvetica.github.io
HCI:CS374

# Before the beginning
Please, download or pull the whole files from the github and run index.html. Because, our project uses Google Map API and Google Map API key doesn't work for github.io. Most of functionality works, but "search location in any language" function doesn't work in github.io, which is important part of our project. So, to have full experience of the project, please download files from github.

# How to use
start with index.html
At the begining there is only search result of baseballbat, so try to search with 'baseball' 'bat' or 'baseballbat'
When the user request a product, it will be added to database. Then the user can serach his or her product with tag or name.

# Explanation of each file
index.html is main page, dealing with search algorithm, and show search result
product_page.html shows details of product. It brings data frome firebase to show product detail.
request.html is adding new product to databse for requesting. new requested product can be searched by name or tag.
shopping_cart.html shows items added to shopping cart. This information is came from firebase.
shopping_done.html is address filling page. This page use google map api to get current location and fill address for user.

Every html file has own .css and .js file.
Every html uses bootstrap

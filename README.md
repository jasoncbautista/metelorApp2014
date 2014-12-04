Add less / bootbstrap


http://www.manuel-schoebel.com/blog/meteorjs-and-twitter-bootstrap---the-right-way

// 1. Add the less compiler so meteor compiles everything for you
meteor add less

// 2. Add the bootstrap
meteor add nemo64:bootstrap

// 3. Clone this stylesheet boiler
// Also delete the .git folder and .gitignore if you don't like those
cd yourapp/client/
git clone https://github.com/DerMambo/stylesheets.git

// 4. Add everything you need into the file
// yourapp/client/vendor/custom.bootstrap.json

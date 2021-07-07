# NodeJS Shopping Cart - NodeJS, Express, Express-Session, Express handlebars (hbs)

### Run locally on your machine
You need to have installed Node and NPM.

![NodeJS Shopping Cart](/data/nodejs-cart-1.png?raw=true "NodeJS Shopping Cart")

Clone this repository
``` shell
git clone https://github.com/gtsopour/nodejs-shopping-cart.git
```

Install dependencies
``` shell
npm install
```

Start NodeJS server at http://localhost:3000
``` shell
npm start
```

For Nodemon usage
``` shell
nodemon ./bin/www
```

### Technologies
NodeJS, Express, Express-Session, Nodemon, hbs - Express.js view engine for handlebars.js

For any extra questions, please contact me at gtsopour@gmail.com. 


// catch 404 and forward to error handler
// app.use(function(req, res, next) {
//   var err = new Error('Not Found');
//   err.status = 404;
//   next(err);
// });

// error handler
// app.use(function(err, req, res, next) {
//   // set locals, only providing error in development
//   res.locals.message = err.message;
//   res.locals.error = req.app.get('env') === 'development' ? err : {};
//   // render the error page
//   res.status(err.status || 500);
//   res.render('error');
// });
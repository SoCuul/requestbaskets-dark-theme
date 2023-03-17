# Request Baskets Dark Theme

## Description
This is a dark-theme for your self-hosted instance of [**Request Baskets**](https://github.com/darklynx/request-baskets).
It is a modified version of the [darkly](https://bootswatch.com/3/darkly/) theme from [bootswatch](https://bootswatch.com/), to integrate perfectly into the dashboard interface.

## Installation
To apply this theme, you must build **Request Baskets** from the source code provided here: https://github.com/darklynx/request-baskets
Once you clone the repo, replace the following lines in every single html file:
```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
```
with...
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/socuul/requestbaskets-dark-theme@ce0617b/bootstrap.min.css" integrity="sha384-wUFMHEIMFTe6O6b7N3YlgbeHGiry12Q8IUgn3VS2zu/wCp+FXaP621TgGu3RpLCL" crossorigin="anonymous">
```

## Contributing
Feel free to improve upon the theme, as the design decisions taken were my personal preference.

## Screenshots
![Home page](https://i.imgur.com/YVKDkWP.png)
![Baskets Summary View](https://i.imgur.com/7agFL8V.png)
![Individual Basket View](https://i.imgur.com/Uoh3fqp.png)
![Individual Basket View (With logged requestsO](https://i.imgur.com/ekQwHEx.png)

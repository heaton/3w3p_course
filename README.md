### Get started

This is a simple boilerplate project for web designer/developer, it contains the following things:

1.	Guardfile to watch changes
2.	config.rb used for compass
3.	A very simple HTML5 boilerplate file

To use it, simply clone this repo and :

```sh
$ bundle install
```

Then start server by
```sh
python -m SimpleHTTPServer
```
Then go to [localhost:8000](http://localhost:8000) you will see a hello world page.
After the required `gem`s are installed, you can then run 

```sh
$ guard start
```

And if you don't have the amazing chrome [plugin](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei) installed, you should install it. 

Once it's installed, open the page in browser, and click the `live reload` button to enabled. You should then see something like this if you have `guard` started:

```
[1] guard(main)> 23:58:49 - INFO - Browser connected.
```

That's it, have fun with coding more interesting stuff.

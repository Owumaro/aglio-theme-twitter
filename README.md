# aglio-theme-twitter
A basic [aglio](https://github.com/danielgtaylor/aglio) theme inspired by [Twitter's REST API documentation](https://dev.twitter.com/rest/public).

![screenshot](https://cloud.githubusercontent.com/assets/5205295/7212032/ebbc4d0a-e561-11e4-8861-89040151a620.png)

### Installation

This is a quick (and quite dirty) theme, therefore I created it based on the default aglio theme. I only changed CSS styles.

To use it, you will have to copy `twitter.jade` directly into the `templates` folder of your aglio installation.

To locate your aglio installation folder, on Mac OS X, you can try `which aglio | xargs ls -l`.
```
lrwxr-xr-x  1 root  admin  38 17 avr 21:33 /usr/local/bin/aglio -> ../lib/node_modules/aglio/bin/aglio.js
```
In that case copy the jade template at `/usr/local/lib/node_modules/aglio/templates`.

### Usage

To check if your installation was successful, try `aglio -l`. You should see `twitter` in the list.

Then you can pass a `-t twitter` argument to your usual `aglio` calls.
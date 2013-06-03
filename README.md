# Web Components Demo

Just some examples I threw together to demonstrate the main features of the new Web Components specs.

Don't expect these to be examples which explain everything, or demonstrate best practises, or even work in all browsers, they're just scratchpad code that I was playing with. Browser support may change at any time and both the spec and its implementations are likely to change and break this sample code with no notice.

## Getting started

Clone this repository locally and grab the submodules

    git clone git://github.com/gareth/web_components_demo.git
    cd web_components_demo
    git submodule update --init --recursive

Start a server. There's no server-side component to these so the quickest way is [probably with python](http://stackoverflow.com/a/532710/31582):

    # Python 2 (probably the default)
    python -m SimpleHTTPServer 8080

    # Python 3
    python -m http.server 8080

Take a look at the demos. Although native support is currently (tentatively) available in Chome Canary [via some development flags](http://html5-demos.appspot.com/static/webcomponents/index.html#3), a Javascript polyfill should add support into other browsers. However, for these demos the polyfill only seems to work for Chrome.

    http://localhost:8080/demo
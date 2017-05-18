# Purescript Hello world


# Commands

    npm install -g purescript pulp bower
    pulp build
    pulp test
    pulp run
    node -e 'require("./output/Main").main()'

Still working on getting Google Closure working:

    $ brew install closure-compiler

    $ closure-compiler -O ADVANCED --module_resolution NODE --process_common_js_modules closure/main.js
    closure/main.js:2: WARNING - Failed to load module "./output/Main"
    require("./output/Main").main()
    ^

    closure/main.js:2: ERROR - variable require is undeclared
    require("./output/Main").main()
    ^^^^^^^

    1 error(s), 1 warning(s)
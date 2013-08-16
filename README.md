# cljminecraft

A Leiningen template for cljminecraft.

## Usage

    > lein new cljminecraft yourplugin

This will create a subfolder called yourplugin with the basics needed to get
started, with some sample configuration in src/config.yml and the plugin.yml
already setup under src/plugin.yml, ready to roll.

    cd yourplugin
    lein jar
    cp target/*.jar /path/to/bukkit/plugins/

Start up your Bukkit server and go, by default, you'll see a message when you
place a sign and there will be a command '/yourplugin.random' which does a dice
roll. Very exciting stuff!

Update your details in the plugin.yml and README.md files.

## License

Copyright © 2012 CmdrDats

Distributed under the Eclipse Public License, the same as Clojure.

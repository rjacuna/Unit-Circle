# Unit Circle
Unit Circle using [Tau](http://tauday.com/tau-manifesto) as the circle constant.

## Instructions

1. Install [lein](http://leiningen.org/#install), [boot](https://github.com/boot-clj/boot#install), and the latest [JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).

2. Install [text2svg](https://github.com/ksss/text2svg), you'll need it to generate the static labels. The way to install it varies between OS, so does the installation path.

3. On a terminal execute:
  $ which tex2svg

  Go to the file /src/uc/generate.clj, locate (def tex2svg "/usr/local/bin/tex2svg"), and replace that string with the output of which. If you're on Windows, replace it with the path of the installation of tex2svg if you managed to install it.
4. On a terminal execute:
   $ lein run

   This will generate all the static labels.

5. Once it's done execute:
 $ boot dev

6. On your browser navigate to [localhost:3000](http://localhost:3000)

## Copyright and license

Copyright © 2016 Ricardo J. Acuña

Licensed under the EPL (see the file LICENSE).

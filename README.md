# EuterpeaMusic
> Dianelys Soto-Cruz

## Table of contents
- [Description](#description)
- [Prerequisites](#prerequisites)
- [How to use](#how-to-use)
- [Installing](#installing)
- [Author](#author)

## Description
Simple project using Haskell's Euterpea music library.

## Prerequisites
1. Have Haskell and Euterpea installed.
2. MIDI
3. verde.hs as sample file

## Installing

1.  Download verde.hs
2.  Install Haskell :

    On Linux Ubuntu

    ```sh
      $ sudo apt-get install haskell-platform
    ```
  
    Others available here: https://www.haskell.org/platform/

3.  Installing Euterpea :
    
    ```sh
      $ cabal update
    ```

    ```sh
      $ cabal install Euterpea
    ```
4.  MIDI on Linux using Timidity

       ```sh
      $ sudo apt-get install timidity
    ```
    
## How to use
1.  Start timidity:

     ```sh
       $ timidity -iA -Os
    ```
2.  On new terminal window in verde.hs directory

     ```sh
       $ ghci
       $ :load verde.hs
       $ import Euterpea
       $ devices // Timidity should appear on Output devices
       $ playDev 2 verde
    ```

## Author
Created by Dianelys Soto-Cruz

## References

1.  http://euterpea.com/

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

# EuterpeaMusic
  High Level Programming Languages - CCOM4029  
  
  ## General info
  Simple class project using Haskell's Euterpea music library.
 
  ## Prerequisites
  1) Have Haskell and Euterpea installed.
  
  2) MIDI
  
  3) verde.hs as sample file
  
  ## Installing
  * Download verde.hs
  
  * Install Haskell : 
  
      On Linux Ubuntu 
  
      $ sudo apt-get install haskell-platform
  
      Others available here
  
      https://www.haskell.org/platform/
  
  * Installing Euterpea : 
  
     $ cabal update
     
     $ cabal install Euterpea
  
  * MIDI on Linux using Timidity 
  
     $ sudo apt-get install timidity
  
  ## How to use
  * Start timidity:
  
    $ timidity -iA -Os
    
  * On new terminal window in verde.hs directory 
  
    $ ghci
    $ :load verde.hs 
    $ import Euterpea 
    
    $ devices 
    Timidity should appear on Output devices
    
    $ playDev 2 verde
  

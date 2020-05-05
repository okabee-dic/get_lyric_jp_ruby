getlyric.rb
====

## Overview
getlyric.rb gets japanese lyrics from utamap.co.jp or kget.jp and show.

## Description
getlyric.rb gets japanese lyrics.  
in default, getlyric.rb gets from utamap.co.jp.  
when -k option is set, gets from kget.jp.  
kget.jp has more lyrics of japanese songs, but slower than utamap.co.jp.  

## Demo

## Requirement
Typhoeus  
Nokogiri

## Usage
ruby getlyric.rb [-k] <artistname> <songname>  
ruby getlyric.rb [-k] -t <songname> [<artistname>]  
ruby getlyric.rb [-k] -l <artistname>  

## Install
bundle install

## Contribution

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[okabee-dic](https://github.com/okabee-dic)


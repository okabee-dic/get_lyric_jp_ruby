getlyric.rb
====

## Overview
getlyric.rb gets japanese lyrics from utamap.com or kget.jp and show.

## Description
getlyric.rb gets japanese lyrics.  
in default, getlyric.rb gets from utamap.co.jp.  
when -k option is set, gets from kget.jp.  
kget.jp has more lyrics of japanese songs, but slower than utamap.com.  

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


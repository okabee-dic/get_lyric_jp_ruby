getlyric.rb
====

## Overview
getlyric.rb gets japanese lyrics from utamap.com or kget.jp and show.

## Description
getlyric.rb gets japanese lyrics.  
in default, getlyric.rb gets from utamap.com.  
when -k option is set, gets from kget.jp.  
kget.jp has more lyrics of japanese songs, but slower than utamap.com.  

## Demo

## Requirement
Typhoeus  
Nokogiri

## Usage
ruby getlyric.rb [-k] &lt;artistname&gt; &lt;songname&gt;  
ruby getlyric.rb [-k] -t &lt;songname&gt; [&lt;artistname&gt;]  
ruby getlyric.rb [-k] -l &lt;artistname&gt;  

## Install
bundle install

## Contribution

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[okabee-dic](https://github.com/okabee-dic)


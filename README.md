getlyric.rb
====

## Overview
getlyric.rb gets japanese lyrics from utamap.com or kget.jp and show.

## Description
getlyric.rb gets japanese lyrics.  
in default, getlyric.rb gets from utamap.com.  
when -k option is set, gets from kget.jp.  
kget.jp has more lyrics of japanese songs, but slower than utamap.com.  
-f option will write lyrics down to the file &lt;artist&gt; - &lt;title&gt;.txt on the current directory.  

## Demo

## Requirement
Typhoeus  
Nokogiri

## Usage
ruby getlyric.rb [-k] [-f] &lt;artistname&gt; &lt;songname&gt;  
ruby getlyric.rb [-k] [-f] -t &lt;songname&gt; [&lt;artistname&gt;]  
ruby getlyric.rb [-k] -l &lt;artistname&gt;  

## Install
bundle install

## Contribution

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[okabee-dic](https://github.com/okabee-dic)


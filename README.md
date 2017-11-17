### js汉字 -> 拼音

#### 字库

字库方面使用了 http://github.com/fayland/perl-lingua-han/tree/master/Lingua-Han-PinYin/
#### 使用

<pre><code>
import w2p from 'w2p'

w2p('汉字') //'han zi'
w2p('汉字', '') //'hanzi'
w2p('汉字', '-') //'han-zi'
</code></pre>
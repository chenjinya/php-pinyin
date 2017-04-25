# php-pinyin


提供php版本的汉字转拼音功能
使用方法

```

echo Pinyin::encode("哇哈哈");
> wa ha ha


echo Pinyin::encode("哇哈哈", 'initial');
> w h h

echo Pinyin::encode("哇哈哈", 'initial', '-');
> w-h-h

echo Pinyin::encode("哇哈哈", 'all', '.');
> wa.ha.ha

```
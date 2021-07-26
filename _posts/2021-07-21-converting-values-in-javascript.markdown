---
layout: default
title:  "Converting Values in JavaScript"
date:   2021-07-05 15:56:37 +0100
categories: jekyll update
---
Operating in Javascript is important in order to recognise Data types of values and trying to advoid unexpected results.

{% highlight html %}

( function (){
    let sum, net = '25', tax = 5.00

    sum = net + tax
    console.log('sum: ' + sum + '' + typeof sum )
    
    console.log('tax:' + tax + '' + typeof tax )
    tax= tax.toString()
    console.log('tax: ' + tax + '' + typeof tax )
    
    net = '$' + net
    console.log('net: ' + net + '' + parselnt( net ))
    consike.log('net Not a Number? ' + isNan( net )) 

{% endhighlight %}

# How to see what you did!

On your keyboard at the same time press CTRL, SHIFT, I. Then go onto 'Console' And then you can see what you coded!

# strings

Strings in JavaScript are primitive data types and immutable, which means they are unchanging. A string is a sequence of one or more characters that may consist of letters, numbers, or symbols.
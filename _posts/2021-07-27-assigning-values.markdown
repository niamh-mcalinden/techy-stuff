---
layout: default
title:  "Assigning Values"
date:   2021-07-05 15:56:37 +0100
categories: jekyll update
---

The Assignment Operator are shorthand forms of longer expressions. That means each equivalent is also given clarity.

{% highlight html %}

( function (){
            let msg = 'JavaScript' ; msg + = ' Fun '
            console.log('Add & Concatenate:' + msg )
            let sum = 5.00 ; sum + = 2.50 
            sum = 8 ; sum -=4
            console.log('Subtract & assign decimal: ' + sum )
            sum = 8 ; sum*= 4
            console.log('Multiply & assign integer: ' + sum )
            sum = 8 ; sum/=4
            console.log('Divide & assign integer: ' + sum )
            sum = 8 ; sum%=4
            console.log('Modulus & assign integer: ' + sum )
        })
s
{% endhighlight %}


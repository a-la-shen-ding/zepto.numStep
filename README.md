# zepto.numStep
number step, based on zepto, used to add and subtract the number of shopping goods

### How to user it
no JS:

```
 <div id="buy-step" class="total-num num-step" data-role="numStep" data-trigger="#total-price" data-min="1" data-max="5">

    <a class="btn-bar icon-minus minus-bar"></a>

    <span><ins class="text-attractive num-show" data-num="1" data-perprice="199.00" data-totalprice="">1</ins></span>

    <a class="btn-bar icon-plus plus-bar"></a>

  </div>

  <div class="total-price">

    <div>总价：<ins id="total-price" data-totalprice="199.00">199</ins>元</div>

  </div>
```

the data-* attributes are required.

You can set  the minimum&maximum number with 'data-min' & 'data-max' , the default value is 1&100000000.

'data-trigger' is a div's id, the div correspond to all of the total value of commodity prices.

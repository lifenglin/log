log
===

## Example:

###代码

```
use Tofu\Log;
require('Log.php');
Log::init();
function a(){
    foreach ($a as $b) {
    }
}
a(1,2,3,array(1,23));
```

###日志输出
```
PHP Notice: Undefined variable: a in /Users/lifenglin/dev/B计划/log/Example.php on line 6
#0 /Users/lifenglin/dev/B计划/log/Example.php(9): a(1, 2, 3, array(0=>1,1=>23,))
PHP Warning: Invalid argument supplied for foreach() in /Users/lifenglin/dev/B计划/log/Example.php on line 6
#0 /Users/lifenglin/dev/B计划/log/Example.php(9): a(1, 2, 3, array(0=>1,1=>23,))
```

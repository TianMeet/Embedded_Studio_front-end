```
1
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        for(var i = 0;i < 5;i++){
            (function (i){
                setTimeout(() => {
                    console.log(i);
                }, 3000*i);
            }(i))   
        }
    </script>
</body>
</html>

2.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        var arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
        //在数组中这个随机值位置的数和arr[i]位置的数据交换，循环结束，产生随机数组。
        function randSort(arr) {
            for(var i = 0, len = arr.length; i < len; i++) {
                var rand = parseInt(Math.random() * len);
                var temp = arr[rand];
                arr[rand] = arr[i];
                arr[i] = temp;
            }
            return arr;
        }

        console.log(randSort(arr));
    </script>
</body>
</html>
3.
ccc
undefined
undefined
www

4.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        (function(a,b){           
            a = a.split("").sort()
            b = b.split("").sort()
            for(let i = 0, len = b.length; i < len; i++) {
                if(a[i] !== b[i])
                console.log(b[i])             
            } 
        })(s1,s2);
    </script>
</body>
</html>
```

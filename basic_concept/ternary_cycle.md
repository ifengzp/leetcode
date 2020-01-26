# [求三次循环的时间复杂度](https://www.cnblogs.com/sheeva/p/6497687.html)
## 问题描述
三层循环，求最内层循环的执行次数，代码如下：
```js
let count=0,n=10;
for(i=0; i<n; i++){
    for(j=0; j<i; j++){
        for(k=0; k<j; k++){     
            count+=1;
        }
    }
}
console.log(count)
```



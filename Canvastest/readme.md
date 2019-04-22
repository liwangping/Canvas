这里的动画中为什么一拉最多只有12个圆圈呢？
因为这里的o是1，para.o是0.09，只能有12个小于0的移除掉了 谢谢了
round_arr[i].o -= para.o;

if( round_arr[i].o <= 0){
      round_arr.splice(i,1);
       i--;
 }
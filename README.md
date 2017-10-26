# fullpage
vue整屏滚动

使用方法

js
import fullpage from 'fullpage'
components:{
   Fullpage
}

html
<fullpage :isScroll='false'>
   <div>
     ...
  </div>
   <div>
     ...
  </div>
   <div>
     ...
  </div>
</fullpage>


滚动条 (isScroll)
	是否显示  布尔值  默认true显示
  
滚动时间 (scrollTime)
	滚动开始到结束时间   数字  默认 500ms
  
滚动导航点 (isDots)
	滚动导航  仅在没有滚动条是可选择   布尔值  默认false不显示
  
当前位置信息 （currentPage）
	当前位置返回值   数字  @currentPage回调
  
跳转至  （toPage回调）
	返回跳转至某个指定位置   给父组件导航使用    数字  默认0
  
滚动方向（path回调）
	返回向上或向下滚动方向    布尔值   向上为false  向下为true

<template>
  <div class="hello">
    <header class="bar bar-nav">
	  <h1 class="title">视图列表</h1>
	</header>
	<div class="content">
	  
    <router-link to="/login">登录</router-link>
	  <div class="content-block-title">图标、标题和副标题</div>
	  <div class="list-block">
	    <ul>
	      <li class="item-content">
	        <div class="item-media"><i class="icon icon-f7"></i></div>
	        <div class="item-inner">
	          <div class="item-title">商品名称</div>
	          <div class="item-after">杜蕾斯</div>
	        </div>
	      </li>
	      <li class="item-content">
	        <div class="item-media"><i class="icon icon-f7"></i></div>
	        <div class="item-inner">
	          <div class="item-title">型号</div>
	          <div class="item-after">极致超薄型</div>
	        </div>
	      </li>
	    </ul>
	  </div>
	  <div class="content-block-title">标题和副标题</div>
	  <div class="list-block">
	    <ul>
	      <li class="item-content">
	        <div class="item-inner">
	          <div class="item-title">商品名称</div>
	          <div class="item-after">杜蕾斯</div>
	        </div>
	      </li>
	      <li class="item-content">
	        <div class="item-inner">
	          <div class="item-title">型号</div>
	          <div class="item-after">极致超薄型</div>
	        </div>
	      </li>
	    </ul>
	  </div>
	  <div class="content-block-title">带箭头</div>
	  <div class="list-block">
	    <ul>
	      <li class="item-content item-link">
	        <div class="item-media"><i class="icon icon-f7"></i></div>
	        <div class="item-inner">
	          <div class="item-title">商品名称</div>
	          <div class="item-after">杜蕾斯</div>
	        </div>
	      </li>
	      <li class="item-content item-link">
	        <div class="item-media"><i class="icon icon-f7"></i></div>
	        <div class="item-inner">
	          <div class="item-title">型号</div>
	          <div class="item-after">极致超薄型</div>
	        </div>
	      </li>
	    </ul>
	  </div>
	</div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App  我是高超'
    }
  }
}
</script>
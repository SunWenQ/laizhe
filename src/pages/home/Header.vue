<template>
  
 <header class="header">
 	<a class="header-left"><</a>
 		<div class="header-title">
				<span class="single-line">输入城市/景点/游玩主题</span>
 		</div>
 		<div class="header-right">
 				<span class="mp-nav-city">北京</span>	
 		</div>
	</header>
</template>	

<script>

export default {
 
 
}
</script>

<style scoped>
.header {
    position: relative;
    width: 100%;
    height: .88rem;
    background: #00bcd4;
    text-align: center;
    color: #fff;
	}
	.header-left{
    width: .4rem;
    line-height: .88rem;
    padding: 0 .2rem;
    color: #fff;
    font-size: .36rem;
    text-align: left;
    float:left;
}
	.header-title{
	position:absolute;
	top: .14rem;
	left:.8rem;
	right:1.28rem;
	background:#fff;
	color:#ccc;
	border-radius: .06rem;
    line-height: .6rem;

	}	
	.header-right{
		line-height:.88rem;
		width:1.28rem;
		float:right;
	}
</style>

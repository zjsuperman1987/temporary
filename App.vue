<template>
  <div id="app">

   	<div class="headBar">
   		<img src="./images/head.jpg">
   	</div>
   	<div class="nameOfShop">永辉超市</div>
   	<div class='shadowBar'></div>
   	<div class="middleBar">
   		<div class="telephone">
   			<span class="icon-phone"></span>
   			<span class="telephoneNumber">13892703659</span>
   		</div>
   		<div class="floor">
   			<span class="icon-compass"></span>
   			<span class="floorInfo">负一楼-B1-001; L1-CS-001</span>
   		</div>
   	</div>
   	<div class='shadowBar'></div>
   	<div class="brandIntroduce">
   		<div class="leftCorner">
   			<h4>品牌简介</h4>
   			<span>Brand introduction</span>
   		</div>
   		<div class='brandContent'>
   			<p>
   			    互联网时代，一些曾经是大胆的想象，如今已司空见惯。当人们习惯了网约车，你再提出租车特许经营，顾客能答应吗？青年人习惯了扁平结构，你再教育他们一步一步往上爬，你能招得到人吗?当有志者期待合作共赢时，你让他听从于你的指指点点，他能接受吗?这张图揭示了我们所处时代的变革，也是永辉变革的外部逻辑。
   			</p>
   			<p>
   			    如今几乎每个行业都面临着产能过剩的问题，中国已经从一个所谓的短缺经济时代走到了供应过剩的时代，共享经济已经具备了充分的物质基础。现代人在认知上已有了双倍盈余，需要通过在社会之间进行传导与互助，将盈余分享出去，因此对共享经济有了更迫切的需求。例如：打车、汽车租赁服务行业、O2O行业，均属于共享经济商业模式。未来共享经济模式将会颠覆现有的商业逻辑与商业价值。
			</p>

   			<p>
   			    互联网时代，一些曾经是大胆的想象，如今已司空见惯。当人们习惯了网约车，你再提出租车特许经营，顾客能答应吗?青年人习惯了扁平结构，你再教育他们一步一步往上爬，你能招得到人吗?当有志者期待合作共赢时，你让他听从于你的指指点点，他能接受吗?这张图揭示了我们所处时代的变革，也是永辉变革的外部逻辑。
   			</p>
   		</div>
   	</div>
   	<div class="patternMaking">
   			<img src="./images/yh1.jpg">
   			<img src="./images/yh2.jpg">
   			<img src="./images/yh3.jpg">
   			<img src="./images/yh4.jpg">
	</div>

  </div>
</template>

<script>

</script>

<style lang="less" scoped>
 @import '../../assets/css/common.less';
 @import '../../assets/css/page.less';

#app {
	font-size:12px;
}

.headBar {
	height: 200px;
	width: 100%;
}
.headBar > img {
	height: 100%;
	width: 100%;
}
.nameOfShop {
	height: 30px;
	line-height:30px;
	text-align: center;
	font-size: 12px;
	font-weight: bold;
	border-bottom:1px solid #CDC9C9;
}
.shadowBar {
	height:5px;
	background: #DEDEDE;
}
.middleBar {
	height: 100px;
	padding-left: 20px;
}
.telephone, .floor {
	height: 49px;
	line-height: 49px;
}
.telephone {
	border-bottom: 1px solid #EE9A00;
}
.leftCorner {
	margin: 10px 0;
	color: #EE9A00;
}
.brandContent p {
	margin-top: 10px;
}
.patternMaking {
	width:100%;
}
.patternMaking img {
	width: 100%;
	margin-top:10px;
}
</style>

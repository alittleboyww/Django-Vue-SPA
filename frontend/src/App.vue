<template>
	<div>
		<header-view></header-view>
		<router-view></router-view>
	</div>
</template>

<script>
import header from './components/header';


export default {
	components: {
		headerView: header
	}
}
</script>

<style>
html {overflow-y:scroll;} 
div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,form,fieldset,input,textarea,blockquote,p{padding:0; margin:0;} 
table,td,tr,th{font-size:12px;} 
li{list-style-type:none;} 
a { text-decoration: none;
    color: #258fb8;
}
img{vertical-align:top;border:0;} 
ol,ul {list-style:none;} 
h1,h2,h3,h4,h5,h6{ font-size: 14px; font-weight:normal;} 
address,cite,code,em,th {font-weight:normal; font-style:normal;} 
body {
    background: #eee;
    color: #444;
    font-family: 'Source Sans Pro', 'Helvetica Neue', Arial, sans-serif;
    font-size: 14px;
    text-shadow: 0 0 1px transparent;
	margin:0; 
	padding:0;
}
.inner {
    width: 1200px;
	margin: 0 auto;
}
@media screen and (max-width: 1260px)
{
	.inner {
		width: 100%;
	}
	body {
		margin: 0 30px;
	}
}
.clearfix {
    zoom: 1;
	clear: both;
}
.alignleft {
    float: left;
}
.alignright {
    float: right;
}
article .entry p, article .entry blockquote, article .entry ul, article .entry ol, article .entry dl, article .entry table, article .entry iframe, article .entry h3,article h1, article .entry h4, article .entry h5, article .entry h6, article .entry pre {
    margin-top: 15px;
}
</style>

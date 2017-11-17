<template>
	<p>{{greeting}} World!</p>
</template>

<script src="../js/vue.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript">
	var app=new Vue({
		data:function(){
			return {
				greeting:'Hello'
			}
		}
	})
</script>
<script type="text/javascript">
	let name = "abraham lincoln";
	let src = "./images/abraham-lincoln.png"; 
	let user = {
		firstName: 'Ris',
		lastName: 'yandi'
	}

	import Footer from './Footer.svelte'
</script>

<!-- print svelte -->
<b>{name}</b> <br/>
<img {src} alt="abraham lincoln" style="width:200px; height:200px;">


<br/>
<!-- debug svelte -->
<input bind:value={user.firstName} type="text">
<input bind:value={user.lastName} type="text">
<!-- {@debug user} -->
<h1>Hello {user.firstName + user.lastName}</h1>
<Footer/>
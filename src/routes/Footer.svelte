<script>
	import {
		modal
	} from './stores.js';
	let tabIndexFooter=0;
	$: $modal ? tabIndexFooter=-1 : tabIndexFooter=-0;
</script>

<footer class="footer p-5 mt-6">
	<div class="content has-text-centered is-size-6">
				<p>If you have any questions, please send an email to: <a href="mailto:sofiane5434@gmail.com">sofiane5434@gmail.com</a></p>
	</div>
</footer>

<style>
	ul li {display:inline-block}
	ul li:before {content:"• "; padding:5px;}
</style>
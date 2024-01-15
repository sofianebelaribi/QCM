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
				<p><a href="https://qcm-five.vercel.app/#https://raw.githubusercontent.com/sofianebelaribi/QCM/master/QCM1.txt" target="_blank">QCM Anapath</a></p>
				<p><a href="https://qcm-five.vercel.app/#https://raw.githubusercontent.com/sofianebelaribi/QCM/master/QCM2.txt" target="_blank">QCM Ergo</a></p>
				<p><a href="https://qcm-five.vercel.app/#https://raw.githubusercontent.com/sofianebelaribi/QCM/master/QCM3.txt" target="_blank">QCM Semiologie</a></p>
				<p><a href="https://qcm-five.vercel.app/#https://raw.githubusercontent.com/sofianebelaribi/QCM/master/QCM4.txt" target="_blank">QCM Pharmaco</a></p>
	</div>
</footer>

<style>
	ul li {display:inline-block}
	ul li:before {content:"• "; padding:5px;}
</style>
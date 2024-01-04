<script>
	import FlourishScroller from '../components/FlourishScroller.svelte';
	import NewsArticle from './NewsArticle.svelte';
	let steps = [
		'O número de turistas a chegar a Portugal é notório, mas é evidente a falha no que diz respeito à promoção do turismo cultural.',
		'Grande parte dos museus, monumentos e palácios pertencentes ao Património Cultural do país têm sido alvo de perdas significativas de visitantes ao longo de dez anos.',
		'Alguns destes espaços têm ganho força, mas a sua grande maioria tem acompanhado a um declínio no que diz respeito à falta de visitantes.',
		'Por que motivo Portugal, mesmo sendo conhecido pelo seu emblemático mar de turistas anuais, não consegue evoluir na questão do turismo cultural?',
	];
</script>

<FlourishScroller flourish_id="2138411" {steps} />

<NewsArticle />

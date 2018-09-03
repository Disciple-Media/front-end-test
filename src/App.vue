<template>
	<div>
		<div id="actions">
			<ul>
				<li><button>DiscipleText</button></li>
			</ul>
		</div>
		<main>
			<li>
				<disciple-text />
			</li>
			<li>
				<disciple-button />
			</li>
			<li>
				<disciple-image />
			</li>
		</main>
	</div>
</template>

<script>
import DiscipleText from './components/DiscipleText.vue'
import DiscipleButton from './components/DiscipleButton.vue'
import DiscipleImage from './components/DiscipleImage.vue'

export default {
	name: 'app',
	components: {
		DiscipleText,
		DiscipleButton,
		DiscipleImage,
	},
}
</script>

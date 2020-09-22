<template>
  <div>
		<b-jumbotron>
			<template v-slot:lead>
				{{currentQuestion.question}}
			</template>

			<hr class="my-4">

			<p>
				answer choices
			</p>

			<b-button variant="primary" href="#">Do Something</b-button>
			<b-button variant="success" href="#">Do Something Else</b-button>
		</b-jumbotron>
	</div>
</template>

<script>
export default {
	props:{
		currentQuestion: Object
	}, 
}
</script>
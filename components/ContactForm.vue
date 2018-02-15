<template>
	<div class="form-collection">
		<div class="field">
			<label for="" class="label">Name</label>
			<div class="control">
				<input type="text" class="input" placeholder="Type your name here">
			</div>
		</div>
		<div class="field">
			<label for="" class="label">Email</label>
			<div class="control">
				<input type="email" class="input" placeholder="Type your Email address here">
			</div>
		</div>		
		<div class="field">
			<label for="" class="label">Subject</label>
			<div class="control">
				<input type="text" class="input" placeholder="Type your message subject here">
			</div>
		</div>
		<div class="field">
			<label for="" class="label">Message</label>
			<div class="control">
				<textarea type="text" class="textarea" placeholder="Type your message here"></textarea>
			</div>
		</div>
		<div class="field-body">
	    <div class="field">
	      <div class="control">
	        <button class="button is-primary">
	          Send message
	        </button>
	      </div>
	    </div>
  	</div>
	</div>
</template>

<script>
	export default {

	  name: 'ContactForm',

	  data () {
	    return {

	    }
	  }
	}
</script>

<style lang="sass" scoped>
</style>
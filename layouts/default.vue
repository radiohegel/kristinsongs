<template>
  <div>
		<nav class="navbar is-fixed-top is-white">
			<div class="navbar-brand">
				<router-link to="/" class="navbar-item">KristinSongs</router-link>
			</div>
			<div class="navbar-menu">
				<router-link to="/about" class="navbar-item"> About</router-link>
				<router-link to="/shows" class="navbar-item"> Shows</router-link>
				<router-link to="/contact" class="navbar-item"> Contact</router-link>
			</div>
			<div class="navbar-menu navbar-end">
				<span class="navbar-item">
					<iframe name="mini" style="border:0px;width:100%;height:72px;" src="//widget.cdbaby.com/60cd6bd3-716f-4d90-80d7-4d7b5c458146/mini/light/transparent"></iframe>
				</span>
			</div>
		</nav>
    <nuxt/>
  </div>
</template>

<style lang="sass">
  @import './stylevariables.sass'

  .navbar
  	opacity: .8

</style>
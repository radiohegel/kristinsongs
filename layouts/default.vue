<template>
  <div>
		<nav class="navbar is-fixed-top is-light">
			<div class="navbar-brand">
				<router-link to="/" class="navbar-item">KristinSongs</router-link>
			</div>
			<div class="navbar-menu">
				<router-link to="/about" class="navbar-item"> About</router-link>
				<a class="navbar-item"> Store</a>
				<a class="navbar-item"> Contact</a>
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

</style>
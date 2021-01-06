<template>
	<q-layout>
		<q-page-container>
			<router-view />
		</q-page-container>
	</q-layout>
</template>

<script>

export default	{
	name: 'MainLayout',
	data()	{

	}
}
</script>

<style lang="sass">
#q-app
	background-color: $blue-grey-1
</style>
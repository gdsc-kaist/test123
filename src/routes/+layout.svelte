<script lang="ts">
	import TopAppBar, { Row, Section, Title } from '@smui/top-app-bar';
	import IconButton from '@smui/icon-button';
</script>

<TopAppBar variant="static" color="primary">
	<Row>
		<Section>
			<IconButton class="material-icons">menu</IconButton>
			<Title>동아리연합회</Title>
		</Section>
		<Section align="end" toolbar>
		</Section>
	</Row>
</TopAppBar>
<slot />

<style lang="scss">
    :global(html, body) {
        margin: 0;
        padding: 0;
    }
</style>

<script lang="ts">
	import Select, { Option } from '@smui/select';

	let izels = [1, 2, 3, 4, 5, 6, 7];
	let value = 2;
</script>

<h1>이젤 대여</h1>
<Select bind:value label="Select Menu">
	{#each izels as izel}
		<Option value={izel}>{izel}</Option>
	{/each}
</Select>

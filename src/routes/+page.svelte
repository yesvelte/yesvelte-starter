<script>
	import { Alert, Divider, Button, El } from 'yesvelte';
	import { Counter } from '$lib';
</script>

<El container="lg" p="4">
	<Alert color="primary">
		<El mb="3" textMuted>Welcome to YeSvelte!</El>
		<Button target="_blank" color="primary" href="https://www.yesvelte.com/docs">
			Get Started!
		</Button>
	</Alert>
	<Divider>Example component</Divider>

	<Counter />
</El>

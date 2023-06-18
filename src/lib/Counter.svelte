<script>
	import { Card, CardBody, CardFooter, CardActions, El, Button } from 'yesvelte';

	let count = 0;

	function increment() {
		count += 1;
	}
	function decrement() {
		count -= 1;
	}
</script>

<Card title="Counter" style="max-width: 30rem" mx="auto">
	<CardBody>
		<CardBody>
			<El textAlign="center" tag="h1">{count}</El>
		</CardBody>
	</CardBody>

	<CardFooter>
		<CardActions>
			<Button color="cyan" on:click={decrement}>Decrement</Button>
			<Button color="indigo" on:click={increment}>Increment</Button>
		</CardActions>
	</CardFooter>
</Card>

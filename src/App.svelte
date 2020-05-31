<script>
	import { Router, basepath } from '@sveltech/routify';
	import { routes } from '@sveltech/routify/tmp/routes';

	if ('process.env.BASEPATH') $basepath = '/process.env.BASEPATH';
</script>

<Router {routes} />

<script>
	import { url } from '@sveltech/routify';
</script>

<div>
	<a href={$url('/')}>main</a>
	<a href={$url('/about')}>about</a>
</div>

<slot />

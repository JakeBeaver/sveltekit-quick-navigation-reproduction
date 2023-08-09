<script>
    import {page} from '$app/stores';
</script>
<li><a href="/">home</a></li>
<li><a href="/load">/load</a></li>

<h1>route: {$page.route.id}</h1>

<slot />


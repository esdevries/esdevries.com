<script>
    import Nav from '$lib/nav.svelte'
    import Foot from '$lib/foot.svelte'
    import '../styles/style.css'
</script>

<header>
    <Nav />
</header>

<main>
    <slot></slot>
</main>

<footer>
    <Foot />
</footer>
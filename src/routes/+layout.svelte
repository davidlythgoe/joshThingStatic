<script>
import Header from "$lib/components/Header.svelte"
import '$lib/styles/style.scss'
import '../app.css'

export let data
</script>

<svelte:head>

<link rel="preconnect" href="https://fonts.googleapis.com">

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Laila:wght@500&display=swap" rel="stylesheet">

</svelte:head>

<Header />

<p style="font-size: 6em; font-family: 'Laila', sans-serif;"><el style="color:RGB(70,140,210)">n</el>ovel<el style="color:RGB(70,140,210)">m</el>ind</p>

<slot />


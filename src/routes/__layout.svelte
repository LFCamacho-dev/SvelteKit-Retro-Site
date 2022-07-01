<script>
    import Title from '$lib/title.svelte';
    
    // import '../styles/global.css'
</script>

<header>
    <Title title="Retro Gaming Guides"/>
</header>

<main>
    <!-- page content -->
    <slot></slot>
</main>

<footer>
    <p>Copyright &copy; Creatos Studio</p>
</footer>


<style>
    header {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    main {
      max-width: 960px;
      margin: 20px auto;
    }
    footer {
      text-align: center;
    }
</style>
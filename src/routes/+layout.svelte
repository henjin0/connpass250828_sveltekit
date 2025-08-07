<script>
    import '../app.css';
    let { children } = $props();
</script>

<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/reactive">Reactive</a></li>
        <li><a href="/eventhandler">Event Handler</a></li>
        <li><a href="/templatesyntax">Template Syntax</a></li>
        <li><a href="/minesweeper">Minesweeper</a></li>
    </ul>
</nav>

<main>
    {@render children()}
</main>
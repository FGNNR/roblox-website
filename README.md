# roblox-website
<script>
    const links = document.querySelectorAll('nav a');
    links.forEach(link => {
        link.addEventListener('click', function() {
            links.forEach(l => l.classList.remove('active'));
            this.classList.add('active');
        });
    });
</script>
<style>
    nav a.active {
        font-weight: bold;
        text-decoration: underline;
    }
</style>

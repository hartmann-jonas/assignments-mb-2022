<script>
    //import global from "../global.css"
</script>


<nav>
    <ul>
        <li><a href="/todo">todos</a></li>
        <li><a href="/">My perfectly working website</a></li>
        <li><a href="/test">clicker</a></li>
    </ul>
</nav>

<style>
    ul {
        display: flex;
        justify-content: space-around;
    }

    li {
        padding: 10px;
        list-style: none;
    }

    nav {
        min-height: 10vh;
    }
    
    a {
        text-decoration: none;
        color: rgb(12, 12, 12);
        font-size: 30px;
        font-weight: bolder;
        transition: 0.4s;
    }

    a:hover {
        color: rgb(30, 122, 124);
    }
</style>
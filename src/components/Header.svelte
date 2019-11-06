<script></script>


<style>

    header {
        display: flex;
        justify-content: center;
        background-color: #F5F3F1
    }

    nav {
        width: 86%;
        height: 99px;
        display: grid;
        grid: repeat(2, 1fr) / repeat(5, 1fr);
        border-left: 2px solid #383737;
        border-right: 2px solid #383737;
    }
    nav div{
        display: flex;
        align-items: center;
        padding-left: 12px;
    }
    .title {
        grid-row: 1 / 3;
        grid-column: 1 / 4;
    }
    
    .nav-item{
        border-left: 2px solid #383737;
    }

</style>

<header>
    <nav>
        <div class="title">Frank <span>Bowling</span></div>
        <div class="nav-item" style="border-bottom: 2px solid #383737;">
            <a href="#">Exhibitions</a>
        </div>
        <div class="nav-item" style="border-bottom: 2px solid #383737;">
            <a href="#">Work</a>
        </div>
        <div class="nav-item"><a href="#">About</a></div>
        <div class="nav-item"><a href="#">Contract</a></div>
    </nav>
</header>
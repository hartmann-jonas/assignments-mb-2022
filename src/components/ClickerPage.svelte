<script>
    //import global from '../styles.css'

    let count = 0
    
    function add(){
        count += 1;
    }
</script>


<div class="title">
    <h2>the ONLY REAL clicker!!!</h2>
    <h3>go and waste your time now</h3>
</div>

<div class="clickerBox">
    <h1>PogChamp</h1>
    <div class="clickerButton">
        <button id="clicker" on:click={add}>
            {#if count == 0}
                CLICK ME
            {:else}
                {count}
            {/if}
        </button>
    </div>
</div>

<style>
    .clickerBox {
        text-align: center;
    }

    .title {
        padding: 20px;
        margin: auto;
        text-align: center;
        background-color: rgb(36, 36, 36);
    }

    #clicker{
        background-color: red;
        width: 250px;
        height: 250px;
        border-radius: 100%;
        font-size: 33px;
        align-items: center;
        font-weight: bold;
        
    }

    .clickerButton{
        text-align: center;
        display:block;
        padding-top: 20px;
    }
</style>
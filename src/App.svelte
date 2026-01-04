<script>
    function myFunction() {
        window.location.href=("https://zl.conduitnet.ir/")
    }
    function myFunction1() {
        window.location.href=("https://zl.conduitnet.ir/")
    }
</script>
<main>
    <h1 class="title">
        an attempt to prepare for the worst
    </h1>
    <div class="parent">
        teamspeak
        <button class="myButton" on:click={(e)=>{
            e.preventDefault()
            navigator.clipboard.writeText("conduitnet.ir")
        }}>
            copy
        </button>
        <br>
        zipline
        <button class="myButton1" on:click={myFunction}>redirect</button>
        <br>
        matrix
        <button class="myButton2" on:click={myFunction1}>redirect</button>
    </div>
</main>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
    .title {
        font-family: 'Bebas Neue', cursive;
        text-align: center;
        color: #0089ff;
    }
    .myButton2 {
        background-color:transparent;
        border-radius: 10em;
        border: .1em solid #4e6096;
        display:inline-block;
        cursor:pointer;
        color:#ffffff;
        font-size: .7em;
        padding: .5em 1.3em;
        text-decoration:none;
        text-shadow:0px 1px 0px #283966;
    }
    .myButton2:hover {
        background-color:transparent;
    }
    .myButton2:active {
        position:relative;
        top:1px;
    }
    .myButton1 {
        background-color:transparent;
        border-radius: 10em;
        border: .1em solid #4e6096;
        display:inline-block;
        cursor:pointer;
        color:#ffffff;
        font-size: .7em;
        padding: .5em 1.3em;
        text-decoration:none;
        text-shadow:0px 1px 0px #283966;
    }
    .myButton1:hover {
        background-color:transparent;
    }
    .myButton1:active {
        position:relative;
        top:1px;
    }

    .myButton {
        background-color:transparent;
        border-radius: 10em;
        border: .1em solid #4e6096;
        display:inline-block;
        cursor:pointer;
        color:#ffffff;
        font-size: .7em;
        padding: .6em 1.1em;
        text-decoration:none;
        text-shadow:0px 1px 0px #283966;
    }
    .myButton:hover {
        background-color:transparent;
    }
    .myButton:active {
        position:relative;
        top:1px;
    }
    .parent{
        border: .20em solid black;
        border-radius: 5em;
        text-align: center;
        margin: 1em 6em;
        padding: 1em 10em;
        color: #4f70ea;
        border-color: #3e4151;
        font-family: 'Bebas Neue', cursive;
        font-size: 2em;
    }
    :root{
        background-color: #202331;
    }
</style>





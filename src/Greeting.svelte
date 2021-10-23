<script>
    export let name = "Rence";
</script>

<style>
    .greeting-message {
        font-size: 24px;
        font-weight: lighter;
    }
    .container {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .bordered-message {
        border: black 2px solid;
        padding: 10px 10px 10px 10px;
    }
</style>

<div class="container">
    <div class="bordered-message">
        <span class="greeting-message change-color">Hello {name}</span>
    </div>
</div>

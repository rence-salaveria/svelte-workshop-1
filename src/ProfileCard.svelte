<script>
    export let name;
    export let course;
    export let shortDesc;
    export let fbLink;
</script>

<style>
    .change-color {
        color: red;
    }
</style>

<div class="card" style="width: 18rem;">
    <div class="card-body">
        <h5 class="card-title change-font change-color">{name}</h5>
        <h6 class="card-subtitle mb-2 text-muted">{course}</h6>
        <p class="card-text change-font">{shortDesc}</p>
        <a href="{fbLink}" class="card-link" target="_blank">Facebook link</a>
    </div>
</div>

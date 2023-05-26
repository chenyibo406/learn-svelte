<div class="card">
    <slot></slot>
</div>

<!-- a slot is a tag we can specify in the child 
component, then overwrite with content from inside 
the parent -->

<style>
    .card {
        background-color: #fff;
        color: #333;
        border-radius: 15px;
        padding: 40px 50px;
        margin: 20px 0;
        position: relative;
    }
</style>
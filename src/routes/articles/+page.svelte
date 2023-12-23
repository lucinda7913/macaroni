<script>
    import Title from '$lib/title.svelte'

</script>
<Title title="Tea and Information"/>
<div class="about">
    <h2>Articles</h2>
    <p>articles articles</p>
    <ul><li><a href="/">home</a></li></ul>
</div>

<style>
    .about{
        text-align: center;
        display: block;
        margin: 20px, auto;
    }
    ul{
        list-style-type: none;
        padding: 0;
    }
    a{
        display: inline-block;
        margin-top: 10px;
        padding: 10px;
        border: 1px dotted rgba(255,255,255,0.2);
    }

</style>
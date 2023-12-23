<script>
    import Title from '$lib/title.svelte'

</script>
<Title title="About Tea and Tranquility"/>
<div class="about">
    <h2> About Us</h2>
    <p>mmmmmm</p>
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
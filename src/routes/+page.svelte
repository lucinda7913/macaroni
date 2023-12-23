<!-- npm run dev -->
<!-- reactive javascript code goes in script-->
<script>
    import Title from '$lib/title.svelte'

</script>


<Title />
<div class="index">
    <h2>
        <img src="/logo.ico" alt="site logo">
        Tea & Tranquility
    </h2>
    <p>
        A safe place for you to learn about managing anxiety.
    </p>
    <ul><li><a href="/about">about</a></li></ul>
    <ul><li><a href="/articles">articles</a></li></ul>


</div>

<!-- any css to style the template-->
<style>
    .index{
        text-align:center;
        display:flexbox;
        margin: 20px, auto;
        background-color:rgb(157, 157, 157);
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
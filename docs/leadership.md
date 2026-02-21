<style>
.grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }
.grid-item {
        display: flex;
        flex-direction: column;
        align-items: center; 
    }
.grid-item img {
        width: 200px;
        height: 200px;
        object-fit: cover;
        border-radius: 5px;
    }
.grid-item-content {
        /* max-height: 300px; /* set to the height of the image */
        line-height: 1.0;
        max-width: 200px;
        /* overflow: hidden; /* hides any content that exceeds the max-height */
        text-align: center; /* centers the text */
        padding: 10px 0; /* some vertical padding */
    }
</style>

<p style="font-size:25px"><center><b>NCOR Leadership</b></center></p>
<div class="grid-container">
    <div class="grid-item">
        <img src="https://ubwp.buffalo.edu/ncor/wp-content/uploads/sites/40/2015/10/Barry-Smith-300x300.jpg" alt="Barry Smith">
        <div class="grid-item-content">
            <h3><a href="http://ontology.buffalo.edu/smith/">Barry Smith</a></h3>
            NCOR Director
            <a href="//www.buffalo.edu/cas/philosophy.html">Distinguished Professor Department of Philosophy University at Buffalo</a></p>
            <p><em>Research in Theoretical and Applied Ontology</em></p>
        </div>
    </div>
    <div class="grid-item">
        <img src="https://ubwp.buffalo.edu/ncor/wp-content/uploads/sites/40/2020/05/20200518_235644.jpg" alt="John Beverley" width="200" height="200">
        <div class="grid-item-content">
            <h3><a href="https://johnbeverley.com">John Beverley</a></h3>
            NCOR Co-Director<br>
            <a href="https://www.buffalo.edu/cas/philosophy.html">Assistant Professor Department of Philosophy University at Buffalo</a>
            <p><em>Research in Applied Ontology, Logic, Metaphysics, and Social Epistemology</em></p>
        </div>
    </div>
</div>
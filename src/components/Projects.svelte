<script>
    import projects from "./projects";
</script>

<div class="container">
    <h1 class="section-title" id="projects">Projects</h1>
    <div class="grid-container">
        {#each projects as project}
            <div class="blog-card">
                <img class="thumbnail" src={project.thumbnail} alt="{project.title}"/>
                <div class="title-content">
                    <p>{project.title}</p>
                    <hr />
                </div>
                <p class="card-info">{project.description}</p>
                <div>
                    <br/>
                    <div class="title-content">Stack</div>
                    <div class="tag-list">
                        {#each project.stack as tech}
                            <img class="icon" src="/icons/{tech}.svg" alt="{tech}"/>
                        {/each}
                    </div>
                </div>
                <div class="utility-list">
                    <a class="external-links" href={project.code} target="_blank" rel="noreferrer">Code</a>
                    <a class="external-links" href={project.live} target="_blank" rel="noreferrer">Live</a>
                </div>
            </div>
        {/each}
    </div>
</div>

<style>
    .container{
        display: flex;
        flex-direction: column;
        padding: 0;
        margin: 0 auto;
        max-width: 1040px;
        box-sizing: content-box;
        position: relative;
        overflow: hidden;
        grid-template-columns: 1fr 1fr;
        padding-top: 32px;
    }
    .grid-container{
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
        padding: 3rem;
        place-items: center;
        column-gap: 2rem;
        row-gap: 3rem;
    }
    .blog-card{
        border-radius: 10px;
        box-shadow: 3px 3px 20px rgba(80, 78, 78, 0.5);
        text-align: center;
        width: 400px;
    }
    .title-content{
        text-align: center;
        z-index: 20;
        width: 100%;
    }
    .title-content p{
        font-weight: 500;
        letter-spacing: 2px;
        color: #9cc9e3;
        padding: .5rem 0;
        font-size: 2rem;
    }
    .title-content hr{
        width: 50px;
        height: 3px;
        margin: 20px auto;
        border: 0;
        background: #9cc9e3;
    }
    .card-info{
        width: 100%;
        padding: 0 50px;
        color: #e4e6e7;
        font-style: 2rem;
        line-height: 24px;
        text-align: justify;
    }
    .thumbnail{
        width:100%;
        height:100%;
        object-fit: cover;
        overflow: hidden;
    }
    .tag-list{
        display: flex;
        justify-content: space-around;
        padding: 2rem;
    }
    .utility-list{
        list-style-type: none;
        padding: 0;
        display: flex;
        justify-content: space-around;
        margin: 2.5rem 0;
    }
    .external-links{
        color:#333;
        font-size: 1rem;
        padding: 0.4rem 0.8rem;
        background: #9cc9e3;
        border-radius: 8px;
        transition: 0.5s;
    }
    @media screen and (max-width: 768px) {
    }
    @media screen and (max-width: 640px) {
        .grid-container{
            display: flex;
            flex-direction: column;
            padding: 2rem;
            padding-bottom: 1rem;
        }
        .title-content p{
            padding: 0
        }
        .tag-list{
            padding: 1rem 2rem;
        }
        .utility-list{
            margin: 0.2rem;
            margin-bottom: 1rem;
        }
        .blog-card{
            width: 100%;
        }
        .card-info{
            padding:.6rem;
        }
    }
    
</style>

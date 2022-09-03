<div class="container">
    <br />
    <div class="section-title" id="technologies">Technologies</div>
    <div class="section-text">I've worked with a range a technologies in web development and DevOps.</div>
    <div class="list">
        <div class="list-item">
            <img class="icon" src="/icons/svelte.svg" alt="svelte"/>
            <div class="list-container">
                <h1 class="list-title">Front-End</h1>
                <p class="list-paragraph">React, Svelte and <br/> Tailwind</p>
            </div>
        </div>
        <div class="list-item">
            <img class="icon" src="/icons/nodedotjs.svg" alt="node"/>
            <div class="list-container">
                <h1 class="list-title">Backend-End</h1>
                <p class="list-paragraph">NodeJS, Express <br />and MySQL</p>
            </div>
        </div>
        <div class="list-item">
            <img class="icon" src="/icons/gcp.svg" alt="gcp"/>
            <div class="list-container">
                <h1 class="list-title">DevOps</h1>
                <p class="list-paragraph">GCP, GitHub actions, <br />and Logtail</p>
            </div>
        </div>
    </div>
    <div class="section-text">I also work with</div>
    <div class="tech-list">
        <!-- <img src="/icons/nodedotjs.svg" alt="tech"> -->
        <img class="icon" title="TypeScript" src="/icons/typescript.svg" alt="ts">
        <img class="icon" title="Tailwind" src="/icons/tailwindcss.svg" alt="tw">
        <img class="icon" title="Express" src="/icons/express.svg" alt="ex">
        <img class="icon" title="MongoDB" src="/icons/mongodb.svg" alt="mongo">
        <img class="icon" title="Github" src="/icons/github.svg" alt="gh">
        <img class="icon" title="GCP" src="/icons/gcp.svg" alt="gcp"/>
        <img class="icon" title="Rust" src="/icons/rust.svg" alt="rust"/>
        <img class="icon" title="Stripe" src="/icons/stripe.svg" alt="stripe">
        <img class="icon" title="Docker" src="/icons/docker.svg" alt="docker">
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
        padding-bottom: 32px;
    }
    .list{
        list-style-type: none;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 40px;
        margin: 3rem 0;
    }
    .list-item{
        max-width: 320px;
        display: flex;
        flex-direction: column;
    }
    .list-container{
        display: flex;
        flex-direction: column;
        margin-top: 2px;
    }
    .list-title {
        font-weight: 700;
        font-size: 28px;
        line-height: 32px;
        letter-spacing: 0.02em;
        color: #FFFFFF;
        margin-bottom: 8px;
    }
    .list-paragraph {
        font-size: 18px;
        line-height: 30px;
        color: rgba(255, 255, 255, 0.75);
    }
    .tech-list{
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        flex-direction: row;
    }

    @media screen and (max-width: 1024px) {
        .container{
            background-image: none;
            padding: 0;
            margin-top: 40px;
        }
        .list{
            margin: 64px 0;
        }
    }
    @media screen and (max-width: 768px) {
        .container{
            background-image: none;
            padding: 0;
            margin-top: 16px;
        }
        .container{
            background-image: none;
            padding: 0;
            margin-top: 16px;
        }
        .list{
            margin: 64px 0;
            gap: 24px;
        }
        .list-title{
            font-size: 24px;
            line-height: 28px;
        }
        .list-paragraph{
            font-size: 16px;
            line-height: 28px;
        }
        .list-item{
            max-width: 203px;
        }
    }   
    @media screen and (max-width: 640px) {
        .list{
            display: flex;
            flex-direction: column;
            margin: 32px 0;
        }
        .list-container{
            display: flex;
            margin-left: 18px;
        }
        .list-title{
            font-size: 20px;
            line-height: 28px;
            letter-spacing: 0.02em;
            margin-bottom: 4px;
        }
        .list-paragraph{
            font-size: 14px;
            line-height: 22px;
        }
        .list-item{
            margin-bottom: 14px;
            max-width: 320px;
            flex-direction: row;
        }
    }   
</style>
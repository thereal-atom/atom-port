<div class="container">
    <div class="div1">
        <a href="/">
            <svg fill="#fff" role="img" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg"><title>Atom</title><path d="M13.632 5.289c-0.613 0.129-1.823 0.565-2.662 0.984-1.275 0.613-1.759 0.968-2.921 2.13s-1.517 1.646-2.13 2.921c-1.646 3.373-1.646 6.6 0 10.005 0.613 1.291 0.952 1.759 2.13 2.921 1.178 1.178 1.63 1.501 2.921 2.13 1.969 0.936 2.921 1.162 5.002 1.162s3.034-0.226 5.002-1.162c1.275-0.613 1.727-0.952 2.921-2.13 1.178-1.194 1.517-1.646 2.13-2.921 0.774-1.63 1-2.388 1.178-4.002l0.113-1h-3.195l-0.21 1.243c-1.017 6.471-8.907 9.069-13.587 4.47-3.792-3.712-2.969-10.005 1.678-12.732 0.871-0.516 2.63-1.049 3.437-1.049h0.532v-3.227l-0.597 0.016c-0.339 0-1.113 0.113-1.743 0.242zM14.213 9.645c-3.421 0.92-5.648 4.325-5.067 7.745 0.662 3.792 4.212 6.39 7.891 5.761 3.776-0.645 6.39-4.212 5.761-7.859-0.71-4.115-4.647-6.713-8.585-5.648z"/></svg>
            <span>Oscar</span>
        </a>
    </div>
    <div class="div2">
        <span>
            <a href="#projects">Projects</a>
        </span>
        <span>
            <a href="#technologies">Technologies</a>
        </span>
        <span>
            <a href="#about">About</a>
        </span>
    </div>
    <div class="div3">
        <a target="_blank" rel="noopener" href="https://github.com/thereal-atom"><img class="icon" title="Github" src="/icons/github.svg" alt="gh" /></a>
        <a target="_blank" rel="noopener" href="https://twitter.com/oscarfalll"><img class="icon" title="Twitter" src="/icons/twitter.svg" alt="tw" /></a>
        <a target="_blank" rel="noopener" href="https://discordapp.com/users/806657133960495154"><img class="icon" title="Discord" src="/icons/discord.svg" alt="dc" /></a>
    </div>
</div>

<style>
    .container{
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        grid-template-rows: 1fr;
        grid-column-gap: 2rem;
        padding: 1rem;
        padding-top: 1rem;
    }
    span{
        font-size: 2rem;
    }
    .div1{
        grid-area: 1 / 1 / 2 / 2;
        display: flex;
        flex-direction: row;
        align-content: center;
    }
    .div1 span{
        font-size: 1.5rem;
    }
    .div1 a{
        display: flex;
        align-items: center;
    }
    .div1 svg{
        margin-right: 8px;
    }
    .div2{
        grid-area: 1 / 2 / 2 / 4;
        display: flex;
        justify-content: space-evenly;
    }
    .div3{
        grid-area: 1 / 5 / 2 / 6;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    .div2 a {
        font-size: 1.5rem;
        line-height: 32px;
        color: rgba(255, 255, 255, 0.65);
        transition: 0.4s ease;
    }
    .div2 a:hover {
        color: #fff;
        opacity: 1;
        cursor: pointer;
    }
    .div3 a {
        transition: 0.3s ease;
        color: white;
        border-radius: 50px;
        padding: 8px;
    }
    .icon{
        width: 28px;
        height: 28px;
    }
    @media screen and (max-width: 660px){
        .container{
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            grid-template-rows: repeat(2, 60px);
            grid-column-gap: 0.5rem;
            grid-row-gap: 0.5rem;
        }
        .div1{
            grid-area: 1 / 1 / 2 / 3;
        }
        .div1 span{
            font-size: 1rem;
        }
        .div2 {
            grid-area: 2 / 2 / 3 / 5;
        }
        .div3 {
            align-items: center;
            grid-area: 1 / 4 / 2 / 6;
        }
        .div2 a{
            font-size: 1.2rem;
            padding: 0.5rem;
        }
    }

</style>
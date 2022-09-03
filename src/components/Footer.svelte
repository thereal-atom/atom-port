<div class="footer-wrapper">
    <div class="link-list">
        <a target="_blank" rel="noopener" href="https://discordapp.com/users/806657133960495154" class="link-column">
            <div class="link-title">Discord</div>
            <div class="link-item">oscarッ#0671</div>
        </a>
        <a target="_blank" rel="noopener" href="https://github.com/thereal-atom" class="link-column">
            <div class="link-title">Github</div>
            <div class="link-item">thereal-atom</div>
        </a>
        <a target="_blank" rel="noopener" href="https://twitter.com/oscarfalll" class="link-column">
            <div class="link-title">Twitter</div>
            <div class="link-item">@oscarfalll</div>
        </a>
    </div>
</div>

<style>
    .footer-wrapper{
        width: calc(100vw - 96px);
        max-width: 1040px;
        padding: 2rem 48px 40px;
        margin: 1rem auto;
        box-sizing: content-box;
    }
    .link-list{
	    border-top: 1px solid rgba(255, 255, 255, 0.1);
        display: grid;
        grid-template-columns: repeat(3, minmax(85px, 220px));
        gap: 40px;
        padding: 40px 0 28px;
    }
    .link-column{
        display: flex;
        flex-direction: column;
        max-width: 220px;
        width: 100%;
    }
    .link-title{
        font-style: normal;
        font-weight: 600;
        font-size: 12px;
        line-height: 24px;
        text-transform: uppercase;
        color: rgba(255, 255, 255, 0.4);
        margin-bottom: 16px;
    }
    .link-item{
        font-size: 18px;
        line-height: 30px;
        color: rgba(255, 255, 255, 0.75);
        margin-bottom: 16px;
        transition: .3s ease;
        position: relative;
        left: 0;
    }
    @media screen and (max-width: 1024px) {
        .link-list{
		    padding: 32px 0 16px;
        }

    }
    @media screen and (max-width: 768px) {
        .link-item{
            font-size: 16px;
            line-height: 28px;
            display: flex;
        }
        .link-list{
            width: 100%;
            padding: 32px 0 16px;
            gap: 16px;
        }
    }
    @media screen and (max-width: 640px) {
        .footer-wrapper{
            padding: 0 16px 48px;
            width: calc(100vw - 32px);
        }
        .link-item{
            font-size: 8px;
            line-height: 14px;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
        }
        .link-list{
            width: 100%;
            padding: 32px 4px 16px;
            gap: 5px;
        }
        .link-title{
            font-size: 10px;
            line-height: 12px;
            margin-bottom: 8px;
        }
    }
</style>








<div class="background">
        <div class="layout">
            <div class="header">
                 <score score={0} />
                 </div>
            <div class="content" ></div>
            <slot />
        </div>
</div>
<style>
    .background{
        padding:32px;
        display: grid;
        position:absolute;
        inset: 0;
        background-color: var(--color-purple);
    }
    .layout {
        width: 100%;
        max-width:900px;
        margin:0 auto;
    }
</style>

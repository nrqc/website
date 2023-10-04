<script>
    let slackLink = "https://join.slack.com/t/nrqcworkspace/shared_invite/zt-23gpwc480-vp4a0ChQYvgnz1RC3e8Rwg";
</script>

<style>
    .container
    {
        font-family: 'Fira Code', monospace;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .logo
    {
        width: 512px;
        margin-bottom: 20px;
    }

    .description
    {
        text-align: center;
        font-size: 20px;
    }

    @media (max-width: 768px)
    {
        .logo
        {
            width: 80%;
        }
    }

</style>

<div class="container">
    <img class="logo" src="logo.png" alt="Numérique Responsable Québec" />
    <p class="description">
        Rejoindre la conversation sur <a href={slackLink}>Slack</a>
    </p>
</div>

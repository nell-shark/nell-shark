<style>
    .logo-container {
        z-index: 2;
        animation: anim 2s;
    }

    .stats-container {
        z-index: 1;
        animation: anim 4s;
    }

    .languages-container {
        z-index: 1;
        animation: anim 6s;
    }

    @keyframes anim {
        from {
            opacity: 0;
        }
        to {
            opacity: 1;
        }
    }
</style>

<a align="center" href="https://github.com/nell-shark?tab=repositories">
    <img src="./assets/logo.svg" alt="logo.svg" class="logo-container"/>
    <br>
    <br>
    <img width="100%"
    src="https://github-readme-stats.vercel.app/api?username=nell-shark&disable_animations=true&show_icons=true&rank_icon=github&custom_title=Github%20Stats" class="stats-container" />
    <br>
    <br>
    <img width="100%"
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=nell-shark&layout=compact&show_icons=true&disable_animations=true&custom_title=Top%20Languages" class="languages-container" />
</a>
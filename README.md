<!-- midnight-purple theme also looks really good -->
<style>
    body {
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe WPC', 'Segoe UI', system-ui, 'Ubuntu', 'Droid Sans', sans-serif;
        display: grid;
        gap: 10px;
        grid-template-columns: 3fr 1fr;
    }
	main {
		display: flex;
		flex-direction: column;
	}
    aside {
        box-sizing: border-box;
        border: 1px solid white;
        padding: 10px;
        border-radius: 5px; height: 100%;
        background-color: #0D1117;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .text {
        color: #4B8DDA;
        margin-bottom: -10px;
		font-weight: 600;
    }
    .name {
        font-size: 1.5em;
		transform: translateY(100%);
		animation: name 1s 1s ease-out;
		animation-fill-mode: forwards;
		opacity: 0;
    }
    .surname {
        font-size: 2em;
		transform: translateY(100%);
		animation: name 1s 1.6s ease-out;
		animation-fill-mode: forwards;
		opacity: 0;
    }
    #logo {
        margin-bottom: 20px
    }

	@keyframes name {
		to {
			transform: translateY(0%);
			opacity: 1;
		}
	}
</style>
<body>
    <main>
        <img alt="most used languages" src="https://github-readme-stats.vercel.app/api?username=MikhaD&show_icons=true&count_private=true&theme=github_dark&border_radius=5">
        <img alt="most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MikhaD&layout=compact&langs_count=10&theme=github_dark&border_radius=5&card_width=445">
    </main>
    <aside>
        <img alt="logo" src="https://raw.githubusercontent.com/MikhaD/MikhaD/main/logo.svg">
        <div class="name text">Mikha</div>
        <div class="surname text">Davids</div>
    </aside>
</body>
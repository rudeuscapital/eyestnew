<script>
	import Social from '../atoms/Social.svelte';
	import { TwitterIcon } from '@indaco/svelte-iconoir/twitter';
	import { TelegramIcon } from '@indaco/svelte-iconoir/telegram';
</script>

<div class="socials-container">
	<!-- Twitter -->
	<Social tip="Twitter" link="https://x.com/agisnoweyest">
	<svg
		width="22"
		height="22"
		viewBox="0 0 24 24"
		fill="var(--accent)"
		xmlns="http://www.w3.org/2000/svg"
		class="icon"
	>
		<path d="M18.244 2H21.5l-7.78 9.02L23 22h-7.406l-5.8-7.29L3.6 22H.333l8.327-9.67L1 2h7.594l5.243 6.63L18.244 2zM16.848 20.1h2.227L7.25 3.8H5.024l11.824 16.3z"/>
	</svg>
</Social>


	<!-- DexScreener -->
	<Social tip="DexScreener" link="https://pump.fun/coin/JEEv2QxjqGHyTwMjQzh3qnkLrWehk6Hrzqhgujg5pump">
		<img src="/dexscreener.svg" alt="DexScreener" class="icon" />
	</Social>

	<!-- Whitepaper (di samping kanan) -->
</div>

<style>
	.socials-container {
		display: flex;
		flex-direction: row; /* ikon sejajar ke samping */
		gap: 0.75rem;
		align-items: center;
	}

	.icon {
		width: 22px;
		height: 22px;
		object-fit: contain;
		vertical-align: middle;
		fill: var(--accent);
		opacity: 0.9;
		transition: transform 0.2s ease;
	}

	.icon:hover {
		transform: scale(1.05);
		opacity: 0.9;
	}
</style>

<script lang="ts">
	import { HeaderNavigation } from '../constants/navigation';
</script>

<header>
	<div class="w-[50px]">
		<img alt="Paul Dolden Cartoon" src="/PaulDolden.png" />
	</div>
	<nav>
        {#each HeaderNavigation as navItem}
            <a href={navItem.href} />       
        {/each}
	</nav>
</header>

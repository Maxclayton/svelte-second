<script>
  import { onMount } from 'svelte';
  import { fade, draw } from 'svelte/transition';

  let visible = false;

  onMount(() => {
    // Delay the transition by a certain amount of time (in milliseconds)
    setTimeout(() => {
      visible = true;
    }, 1000); // Adjust the delay time as needed
  });
</script>
<main>

{#if visible}
<div class='svg-container'>
<svg width="50" height="50" viewBox="0 0 321 406" fill="#000000" xmlns="http://www.w3.org/2000/svg">
<path in:draw={{ duration: 2000 }} out:draw={{ duration: 800}} d="M74.6074 404.493V310.712H89.8045V404.493H74.6074Z" fill="#000000"  stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path in:draw={{ duration: 2100 }} out:draw={{ duration: 900}} d="M200.121 392.051L241.538 392.169V404.61L181.341 404.492V391.028L221.538 346.578H182.522V334.137H240.318V345.909L200.121 392.091V392.051Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path in:draw={{ duration: 2200 }} out:draw={{ duration: 2200}} d="M320.87 404.493H305.673V392.446C300.633 400.635 292.169 405.162 280.948 405.162C260.712 405.162 247.208 390.477 247.208 369.06C247.208 347.642 260.83 333.469 280.672 333.469C292.051 333.469 300.515 338.114 305.673 346.303V310.712H320.87V404.493ZM305.673 369.571C305.673 355.949 296.814 346.421 284.098 346.421C271.381 346.421 262.523 356.067 262.405 369.571C262.523 382.918 271.263 392.446 284.098 392.446C296.932 392.446 305.673 382.918 305.673 369.571Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#000000"/>
<path in:draw={{ duration: 2300 }} out:draw={{ duration: 1100}} d="M36.1421 391.776C23.5829 391.776 13.4253 381.618 13.4253 369.059C13.4253 356.5 23.5829 346.342 36.1421 346.342C43.3469 346.342 49.7249 349.689 53.8982 354.886L54.1738 354.61L63.4653 345.319C56.851 337.681 47.0478 332.799 36.1421 332.799C16.1813 332.799 0 348.98 0 368.941C0 388.902 16.1813 405.083 36.1421 405.083C47.9139 405.083 58.3865 399.453 65.0007 390.713L55.3156 381.225C51.2998 387.524 44.2131 391.737 36.1421 391.737V391.776Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path in:draw={{ duration: 2400 }} out:draw={{ duration: 1200}} d="M137.6 346.224C150.159 346.224 160.396 356.461 160.396 369.02C160.396 381.579 150.159 391.815 137.6 391.815C125.041 391.815 114.805 381.579 114.805 369.02C114.805 356.461 125.041 346.224 137.6 346.224ZM137.6 332.838C117.639 332.838 101.458 349.02 101.458 368.981C101.458 388.941 117.639 405.123 137.6 405.123C157.561 405.123 173.742 388.941 173.742 368.981C173.742 349.02 157.561 332.838 137.6 332.838Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path in:draw={{ duration: 2500 }} out:draw={{ duration: 1300}} d="M141.183 38.8587V0C73.7809 8.62215 20.3551 62.048 11.7329 129.45H50.5916C58.6232 83.2687 95.0409 46.8509 141.223 38.8587H141.183Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path in:draw={{ duration: 2600 }} out:draw={{ duration: 1400}} d="M270.279 129.45H309.137C300.476 62.048 247.05 8.62215 179.647 0V38.8587C225.829 46.8903 262.247 83.3081 270.279 129.49V129.45Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path in:draw={{ duration: 2700 }} out:draw={{ duration: 1500}} d="M179.648 258.507V297.366C247.051 288.744 300.477 235.318 309.099 167.916H270.24C262.208 214.097 225.791 250.515 179.609 258.507H179.648Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path in:draw={{ duration: 2800 }} out:draw={{ duration: 1600}} d="M50.5916 167.915H11.7329C20.3551 235.318 73.7809 288.744 141.183 297.366V258.507C95.0016 250.475 58.5839 214.058 50.5523 167.876L50.5916 167.915Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path in:draw={{ duration: 2900 }} out:draw={{ duration: 1700}} d="M179.647 129.451H236.105C229.097 101.773 207.325 80.0011 179.647 72.9932V129.451Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
<path in:draw={{ duration: 3000 }} out:draw={{ duration: 1800}} d="M141.182 129.451V72.9932C113.505 80.0011 91.7331 101.773 84.7251 129.451H141.182Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
<path in:draw={{ duration: 3100 }} out:draw={{ duration: 1900}} d="M141.182 167.916H84.7251C91.7331 195.593 113.505 217.365 141.182 224.373V167.916Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
<path in:draw={{ duration: 3200 }} out:draw={{ duration: 2000}} d="M179.647 167.916V224.373C207.325 217.365 229.097 195.593 236.105 167.916H179.647Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
</svg>
<div class='svg2'>
	<svg in:fade={{ delay: 2500, duration: 2000}} out:fade={{ duration: 600}} width="50" height="50" viewBox="0 0 321 406" fill="#000000" xmlns="http://www.w3.org/2000/svg">
<path  d="M74.6074 404.493V310.712H89.8045V404.493H74.6074Z" fill="#000000"  stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path  d="M200.121 392.051L241.538 392.169V404.61L181.341 404.492V391.028L221.538 346.578H182.522V334.137H240.318V345.909L200.121 392.091V392.051Z" fill="#000000" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M320.87 404.493H305.673V392.446C300.633 400.635 292.169 405.162 280.948 405.162C260.712 405.162 247.208 390.477 247.208 369.06C247.208 347.642 260.83 333.469 280.672 333.469C292.051 333.469 300.515 338.114 305.673 346.303V310.712H320.87V404.493ZM305.673 369.571C305.673 355.949 296.814 346.421 284.098 346.421C271.381 346.421 262.523 356.067 262.405 369.571C262.523 382.918 271.263 392.446 284.098 392.446C296.932 392.446 305.673 382.918 305.673 369.571Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#000000"/>
<path  d="M36.1421 391.776C23.5829 391.776 13.4253 381.618 13.4253 369.059C13.4253 356.5 23.5829 346.342 36.1421 346.342C43.3469 346.342 49.7249 349.689 53.8982 354.886L54.1738 354.61L63.4653 345.319C56.851 337.681 47.0478 332.799 36.1421 332.799C16.1813 332.799 0 348.98 0 368.941C0 388.902 16.1813 405.083 36.1421 405.083C47.9139 405.083 58.3865 399.453 65.0007 390.713L55.3156 381.225C51.2998 387.524 44.2131 391.737 36.1421 391.737V391.776Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path d="M137.6 346.224C150.159 346.224 160.396 356.461 160.396 369.02C160.396 381.579 150.159 391.815 137.6 391.815C125.041 391.815 114.805 381.579 114.805 369.02C114.805 356.461 125.041 346.224 137.6 346.224ZM137.6 332.838C117.639 332.838 101.458 349.02 101.458 368.981C101.458 388.941 117.639 405.123 137.6 405.123C157.561 405.123 173.742 388.941 173.742 368.981C173.742 349.02 157.561 332.838 137.6 332.838Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path d="M141.183 38.8587V0C73.7809 8.62215 20.3551 62.048 11.7329 129.45H50.5916C58.6232 83.2687 95.0409 46.8509 141.223 38.8587H141.183Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path d="M270.279 129.45H309.137C300.476 62.048 247.05 8.62215 179.647 0V38.8587C225.829 46.8903 262.247 83.3081 270.279 129.49V129.45Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path  d="M179.648 258.507V297.366C247.051 288.744 300.477 235.318 309.099 167.916H270.24C262.208 214.097 225.791 250.515 179.609 258.507H179.648Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path  d="M50.5916 167.915H11.7329C20.3551 235.318 73.7809 288.744 141.183 297.366V258.507C95.0016 250.475 58.5839 214.058 50.5523 167.876L50.5916 167.915Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#0B0C10"/>
<path  d="M179.647 129.451H236.105C229.097 101.773 207.325 80.0011 179.647 72.9932V129.451Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
<path d="M141.182 129.451V72.9932C113.505 80.0011 91.7331 101.773 84.7251 129.451H141.182Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
<path  d="M141.182 167.916H84.7251C91.7331 195.593 113.505 217.365 141.182 224.373V167.916Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
<path d="M179.647 167.916V224.373C207.325 217.365 229.097 195.593 236.105 167.916H179.647Z" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="#993528"/>
</svg>
	
</div>
</div>
{/if}


<label>
	<input type="checkbox" bind:checked={visible} />
	toggle
</label>

</main>


<link href="https://fonts.googleapis.com/css?family=Overpass:100,400" rel="stylesheet" />

<style>


	svg {
		width: 100%;
		height: 100%;
	}

	path {
		fill: white;
		opacity: 1;
	}

	.svg2 path {
		fill: black;
	}

	.svg2 {
		width: 100%;
	}

	.svg-container {
		display: flex;
		position: relative;
	}

	.svg2 {
		position: absolute;
	}

	label {
		position: absolute;
		top: 1em;
		left: 1em;
	}
</style>

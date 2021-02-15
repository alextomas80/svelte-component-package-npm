<script>
	export let title = "Botón";
</script>

<div class="boton">{title}</div>

<style>
	.boton {
		background-color: coral;
		border-radius: 3px;
		cursor: pointer;
		display: inline-block;
		padding: 10px 20px;
		transition: 0.3s ease;
	}
	.boton:hover {
		background-color: darkorange;
	}
</style>

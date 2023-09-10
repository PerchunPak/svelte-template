<script>
	import '../app.css';
</script>

<main class="{% if cookiecutter.center_everything == 'y' -%}flex flex-col items-center justify-center{% endif %} m-0 p-5 w-full min-h-screen">
	<slot />
</main>

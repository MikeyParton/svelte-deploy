<script lang="ts">
  import { version } from '$app/environment';
</script>

<slot />
<p>{version}</p>
<script lang="ts">
  import { version } from '$app/environment';
  export const prerender = true;
</script>

{version}

<slot />
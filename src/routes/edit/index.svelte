<script>
  import EditorWindow from '$lib/editor/EditorWindow.svelte'
import Tiptap from '$lib/editor/Tiptap.svelte'

  let documentName = 'Hello World'
</script>

<svelte:head>
  <title>Edit document: {documentName}</title>
</svelte:head>

<main>
  <Tiptap />
</main>